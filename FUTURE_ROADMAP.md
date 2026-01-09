# Future Roadmap

Development tasks for this project. This is the **single source of truth** for what to work on.

## How This Works

```
GitHub Issues (external)  →  FUTURE_ROADMAP.md (internal)  →  Implementation
      ↓                              ↓                              ↓
 User reports bug            Human triages & adds           Agent reads roadmap,
 or requests feature          to roadmap with GH#           PRs close issues
```

- **Users** report bugs/features via GitHub Issues
- **Maintainers** triage and add confirmed items here with `GH` reference
- **Agents** read this file to find tasks; never parse GitHub Issues directly
- **PRs** include `Closes #123` to auto-close issues on merge

## Current Tasks

| ID | Priority | Item | Status | GH |
|----|----------|------|--------|-----|
| 1 | P1 | Example: Critical bug in auth flow | In Progress | #123 |
| 2 | P2 | Example: Add dark mode support | Pending | #45, #67 |
| 3 | P3 | Example: Refactor logging module | Pending | — |

### Priority Levels

| Priority | Meaning | SLA |
|----------|---------|-----|
| P0 | Critical / Security | Immediate |
| P1 | High / Blocking users | This sprint |
| P2 | Medium / Important | Next sprint |
| P3 | Low / Nice to have | Backlog |

### Status Values

| Status | Meaning |
|--------|---------|
| Pending | Not started |
| In Progress | Being worked on |
| In Review | PR submitted |
| Done | Merged (move to archive) |

## GH Column Reference

| Format | Meaning |
|--------|---------|
| `#123` | Single GitHub issue |
| `#123, #45` | Multiple related issues |
| `—` | Internal task, no external issue |

## Backlog

Lower priority items or ideas for future consideration.

| ID | Item | GH |
|----|------|-----|
| 100 | Example: Explore GraphQL migration | #89 |

## Archive

Completed items. Move here after Done status.

| ID | Item | Completed | GH |
|----|------|-----------|-----|
| — | — | — | — |

---

**Note:** When starting a task, update status to "In Progress" and follow `dev-workflow` skill.
