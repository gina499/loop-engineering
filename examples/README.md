# Examples

Same patterns, different tools. Skills and state schemas are shared; only this page documents the per-tool mapping. See [docs/primitives-matrix.md](../docs/primitives-matrix.md) for the full cross-tool matrix.

| Tool | Directory |
|------|-----------|
| Grok | [grok/](./grok/) |
| Claude Code | [claude-code/](./claude-code/) |
| Codex | [codex/](./codex/) |
| Cursor | [cursor/](./cursor/) |
| Windsurf | [windsurf/](./windsurf/) |
| OpenClaw | [openclaw/](./openclaw/) |
| Opencode | [opencode/](./opencode/) |
| Hermes Agent | [hermes/](./hermes/) |

## Hermes

| Pattern | Example |
|---------|---------|
| Daily Triage (L1) | [hermes/daily-triage.md](./hermes/daily-triage.md) |
| PR Babysitter (L1 → L2) | [hermes/pr-babysitter.md](./hermes/pr-babysitter.md) |
| CI Sweeper (L1 → L2) | [hermes/ci-sweeper.md](./hermes/ci-sweeper.md) |
| Issue Triage (L1) | [hermes/issue-triage.md](./hermes/issue-triage.md) |
| Loop Verifier (L2) | [hermes/loop-verifier.md](./hermes/loop-verifier.md) — independent maker/checker split |

## Tool mappings

- **MCP** — [examples/mcp/](./mcp/) see also [tools/mcp-server/](../tools/mcp-server/)
- **GitHub Actions** — see [README](../.github/workflows/README.md) for CI loops

L2 patterns ship multi-tool skills inside one starter folder — see `starters/<pattern>/`.

**Copy-paste starters:** table in `starters/README.md`.
