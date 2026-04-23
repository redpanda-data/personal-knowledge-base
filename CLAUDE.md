# Naming Conventions

Rules for AI agents working in this repository.

---

## Files

- **All generated files must be Markdown (`.md`)** — no `.txt`, `.json`, `.yaml`, or other formats unless the content is inherently non-prose (e.g., a config file required by a tool)
- **No files may be created in the root directory** — every generated file must live inside a subfolder
- Prefix all dated notes with `YYYY-MM-DD-`: `2026-04-13-meeting-notes.md`
- Use hyphens, never underscores
- Never put version numbers in filenames — use git instead
- No date prefix for: `README.md`, `CHANGELOG.md`, `index.md`, `CLAUDE.md`

## Folders

- Hyphens only, lowercase, no spaces
- Place new notes in the most relevant existing folder; create a new folder only when no existing folder fits

## Changelog

Every folder has a `CHANGELOG.md`. Update it when you add or modify files in that folder.

```markdown
## YYYY-MM-DD

### Added
- `filename.md` — description

### Changed
- `filename.md` — what changed

### Removed
- `filename.md` — why removed
```

## Index

- `index.md` is the global navigation map
- Update it every session — add one line per new note/project
- Format: `- [title](path/to/file.md) — one-line summary`

## Frontmatter

Recommended fields:

```yaml
---
date: YYYY-MM-DD
tags: []
status: draft | active | archived
---
```
