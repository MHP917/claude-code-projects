# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository

GitHub: https://github.com/MHP917/claude-code-projects
Default branch: `main`

## Git Workflow

Commit and push to `origin/main` continuously as work progresses — after every meaningful change, not just at the end of a task. This ensures work is never lost and the repo always reflects current state.

```bash
git add <specific files>
git commit -m "descriptive message"
git push
```

- Commit at logical checkpoints: new file created, feature working, bug fixed, significant edit made
- Never batch up large amounts of work into a single commit — prefer small, focused commits
- Always include the co-author trailer:
  ```
  Co-Authored-By: Claude Sonnet 4.6 <noreply@anthropic.com>
  ```
- Never use `git add .` or `git add -A` — stage files explicitly by name
- Write commit messages that describe *what changed and why*, not just "update file"

## Project Nature

This is a general-purpose project directory for browser-based and scripted experiments built with Claude Code. Projects are self-contained files (single HTML files, Python scripts, etc.) — no build system, no package manager, no test runner.
