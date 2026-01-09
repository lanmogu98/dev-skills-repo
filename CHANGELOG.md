# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.3.0] - 2025-01-09

### Added
- Pre-flight Checklist: branch creation, task status, code reading — visible immediately
- "Relationship with Plan Mode" section: clarifies how to use with IDE planning tools
- Imperative language in description: "REQUIRED", "MUST load FIRST"

### Changed
- Description rewritten for stronger agent triggering
- "When to Load This Skill" now uses "MUST" instead of "Load immediately"
- Moved critical steps (branch, status) from exploration.md to SKILL.md top

### Fixed
- Agent skipping workflow when entering Plan Mode first (now explicitly addressed)

## [1.2.0] - 2025-01-08

### Changed
- Make skill language-agnostic: multi-language test commands, generic terminology
- "Type hints" → "Type annotations" (universal terminology)
- Remove Python-specific examples (DataFrame, pyproject.toml hardcoding)

## [1.1.0] - 2025-01-08

### Added
- `bugfix.md`: Dedicated bug fix workflow (reproduce → test → fix → verify)
- Version field in SKILL.md frontmatter
- Prerequisites checklist in `implementation.md` as gate
- Navigation links (`→ Next`) to `review.md` and `multi-agent.md`
- "Integration with Main Workflow" section in `multi-agent.md`

### Changed
- `exploration.md`: Fix navigation to point to `design.md` (was `implementation.md`)
- Make `FUTURE_ROADMAP.md` references conditional ("if project uses task tracking")
- Update Task Router to include bug fix entry

## [1.0.0] - 2025-01-08

### Added
- `design.md`: Separate design phase emphasizing "tests are design"
- "When to Load This Skill" section in SKILL.md for better agent discovery
- Refactoring test rules: coverage verification before refactoring

### Changed
- Simplify `implementation.md`: focus on coding standards only
- Unify test requirements across `design.md` and `refactoring.md`
- Update Task Router to include design phase

## [0.1.0] - Initial Release

### Added
- Initial dev-workflow skill
- Core references: exploration, implementation, precommit, pullrequest, refactoring, review, multi-agent
