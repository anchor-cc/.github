<p align="center">
  <img src="./banner.png" alt="Anchor" width="600" />
</p>

<p align="center"><strong>The system of record for AI agents.</strong></p>

<p align="center">A collaborative file system for humans and AI agents. MCP-native. Read, write, audit.</p>

---

Anchor is a single-image CRUD platform with three first-class file types: documents, tables, and apps. Every operation goes through one permission model, one audit log, and one MCP surface, so any agent that speaks MCP (Claude, ChatGPT, Gemini, Codex) operates with the same access semantics as a human user.

## 🧱 Primitives

- **OTHER files.** Anything textable: PDFs, markdown, code, transcripts. Parsed on upload, indexed, MCP-readable via `read_file`.
- **TABLE files.** Typed schemas with row-level access. Agents query with `query_table`, mutate with structured ops.
- **APP files.** Executable JS bundles with persistent state and exported functions. Agents invoke them via `call_app_function`.
- **Folders.** Per-folder ACLs. Private, hidden, temporary, and shared variants.
- **Orgs.** Top-level container for billing, members, and audit retention.

## 🔌 MCP surface

Every primitive is exposed through the [Model Context Protocol](https://modelcontextprotocol.io). Available tools: `ls`, `read_file`, `write_file`, `query_table`, `describe_table`, `call_app_function`, `unpack_app`, `build_app`, `file_upload_link`, and more. One connection, the agent inherits the user's full permission set.

## 🤖 Supported clients

- Claude Desktop, Claude Code
- ChatGPT (via Connectors)
- Gemini CLI
- Cursor
- Codex
- Any MCP-compatible client. See [anchor.cc/supported-agents](https://anchor.cc/supported-agents).

## 🔗 Links

- 🌐 [anchor.cc](https://anchor.cc)
- 📘 [Docs](https://anchor.cc/docs)
- 🔌 [MCP setup](https://anchor.cc/mcp)
- 💼 [LinkedIn](https://www.linkedin.com/company/anchor-cc)
- 🏢 [Crunchbase](https://www.crunchbase.com/organization/anchor-3cbe)

## 📧 Contact

[hello@anchor.cc](mailto:hello@anchor.cc) · New York, NY
