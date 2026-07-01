# Universal Claude Code Guidelines (CCR)

A portable, machine-agnostic Claude Code setup kit — reusable guidelines plus two drop-in hooks — packaged as a single downloadable archive.

## Download

**→ [`ccr.zip`](../../raw/main/ccr.zip)** — click, then **Download raw**.

The archive is flat; unzip it into a folder of your choice (e.g. `claude-code-guidelines/`). Contents:

- `UNIVERSAL_CLAUDE_GUIDELINES.md` — all guidance as one self-contained file
- `README.md`, `TOC.md` — index + table of contents
- 7 topic files — `task-execution`, `multi-agent-orchestration`, `model-and-agent-tiers`, `external-cli-delegation`, `context-and-memory`, `environment-and-safety`, `documentation-toc`
- `.claude/` — two portable hooks (`hooks/toc-reminder.ps1`, `hooks/normalize-windows-paths.ps1`) plus `settings.json` registration and `.claude/README.md` install notes

## Apply on a new machine

1. Download and unzip.
2. Copy the files to a stable spot (e.g. `~/.claude/guidelines/`) and import them from your global memory — add to `~/.claude/CLAUDE.md`:
   ```
   @~/.claude/guidelines/UNIVERSAL_CLAUDE_GUIDELINES.md
   ```
3. (Optional) Install the hooks globally — copy `.claude/hooks/*.ps1` into `~/.claude/hooks/` and merge the blocks from `.claude/settings.json` into `~/.claude/settings.json`. See `.claude/README.md` inside the archive for details.

The full index and rationale are in the archive's own `README.md`.
