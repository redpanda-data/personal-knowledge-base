# Personal Knowledge Base

A minimal, markdown-first system for capturing and connecting your thinking. Fork it, clone it, start writing.

inspired by alex gallego and karpathy's wikis. designed to stay LLM-friendly.

---

## Structure

```
index.md           ← global nav map — update this every session
CHANGELOG.md       ← what changed and when
CLAUDE.md          ← naming conventions for AI agents
notes/             ← atomic notes, daily captures, meeting notes
projects/          ← active work, goals, initiatives
resources/         ← books, papers, links, references
areas/             ← ongoing life domains (health, finance, learning)
```

---

## 3 Rules

**1. Date-prefix all files.**
Every note starts with `YYYY-MM-DD-`: `2026-04-13-idea-for-blog-post.md`
Exceptions: `README.md`, `CHANGELOG.md`, `index.md`, `CLAUDE.md`

**2. Hyphens, not underscores.**
`my-meeting-notes.md` ✅ &nbsp; `my_meeting_notes.md` ❌

**3. Update `index.md` every session.**
It's your routing map. One line per note. Takes 30 seconds. Worth it.

---

## Getting Started

1. Fork or clone this repo
2. Open `index.md` — this is your home base
3. Create your first note: `notes/YYYY-MM-DD-your-first-note.md`
4. Add a line for it in `index.md`
5. Update `CHANGELOG.md`

That's it.

---

## Conventions

### Frontmatter (optional but recommended)

```yaml
---
date: YYYY-MM-DD
tags: [topic, subtopic]
status: draft | active | archived
---
```

### CHANGELOG format

Each folder has its own `CHANGELOG.md`. Update it when you add or change files there.

```markdown
## YYYY-MM-DD

### Added
- `YYYY-MM-DD-title.md` — one-line description

### Changed
- `YYYY-MM-DD-title.md` — what changed
```

---

## Why This Structure

- **`notes/`** — The inbox. Atomic captures that don't fit elsewhere yet.
- **`projects/`** — Active work. Archive when done.
- **`resources/`** — Reference material you return to. Books, papers, saved links.
- **`areas/`** — Ongoing domains with no end date. Health, finances, a skill you're building.

---

## License

Apache 2.0
