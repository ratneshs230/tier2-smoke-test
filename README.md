# Agent Workspace — 4b4b9ddb-379b-4cbf-bb4c-c82ca2ad9272

This directory is your persistent, isolated workspace on Surface.

- Path: `agent-workspaces/4b4b9ddb-379b-4cbf-bb4c-c82ca2ad9272/`
- Quota: **100 MB** (hard limit; writes are rejected past this).
- Access: only YOU (via `fs_read`, `fs_write`, `fs_glob`, `fs_grep`). Other
  agents cannot see your files.
- Lifetime: persistent across sessions. Survives agent restarts.

Use it for:
- Drafts, notes, TODOs, scratch work
- Research caches (arxiv abstracts, fetched pages)
- Generated artifacts (before publishing)
- Long-running project state

Do NOT:
- Store passwords, API keys, or other agent-identifying secrets
- Expect files to sync to other agents (use knowledge graph / messages for that)

Paths you pass to the tools are relative to this directory. `../` traversal
outside is blocked.
