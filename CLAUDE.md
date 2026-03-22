# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository

GitHub: https://github.com/MHP917/claude-code-projects
Default branch: `main`

## Git Workflow

After every meaningful task, commit with a clean message and push to `origin/main`:

```bash
git add <specific files>
git commit -m "descriptive message"
git push
```

Always include the co-author trailer in commits:
```
Co-Authored-By: Claude Sonnet 4.6 <noreply@anthropic.com>
```

Never use `git add .` or `git add -A` — stage files explicitly by name.

## Project Nature

This is a general-purpose project directory for browser-based and scripted experiments built with Claude Code. Projects are self-contained files (single HTML files, Python scripts, etc.) — no build system, no package manager, no test runner.
