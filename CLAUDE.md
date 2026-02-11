# Tonverk Shortcuts — Project Instructions

## Sandbox Policy

This folder (`/Users/marcusestes/Websites/Music/tonverk-shortcurts`) is a **sandboxed workspace**. All file operations — reads, writes, edits, globs, greps — MUST stay within this directory tree.

### Allowed

- **This directory and all its subdirectories** — full read/write access.
- **Your own config and memory files** — `~/.claude/` (CLAUDE.md, memory, settings, keybindings, etc.).
- **Plugin/skill metadata** — read-only access to permissioned structures from installed plugins, MCP servers, and skills (e.g., `~/.claude/agents/`, `~/.claude/teams/`, `~/.claude/tasks/`).

### Forbidden

- **Everything else on the filesystem is off-limits.** Do not read, write, search, or reference files outside this sandbox or the allowed config paths above.
- Do not `cd` outside this directory.
- Do not glob, grep, or explore parent directories (`../`).
- Do not reference or read other projects, repos, or user files elsewhere on disk.

If a task would require accessing files outside the sandbox, stop and ask the user for explicit permission first.

## Autonomy & Iteration

- **Run long.** When given a task, iterate continuously until the work is complete or meets the stated requirements. Do not stop prematurely to check in, summarize progress, or ask "should I continue?" — just keep going.
- **Avoid unnecessary pauses.** Minimize stop hooks, confirmation prompts, and intermediate status reports unless something is genuinely ambiguous or blocked.
- **Self-assess completion.** Use your own judgment to determine when the work meets the user's requirements. Only stop when you believe the task is done, or when you've hit a genuine blocker that requires user input.
- **Bias toward action.** If you can make a reasonable decision yourself, do it rather than asking. Reserve questions for true ambiguities where the wrong choice would waste significant effort.
