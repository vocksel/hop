---
bump: minor
---

Hop now runs on Windows and Linux, and releases include a binary for each. It finds Cursor's data in each platform's settings folder, matches worktrees and sessions whatever path separator or drive-letter case they report, and opens VS Code with `xdg-open` on Linux and the URL protocol handler on Windows. Without `sqlite3`, `hop recent` lists Claude Code sessions only.
