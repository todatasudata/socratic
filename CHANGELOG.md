# Changelog

## 1.3.5 — 2026-07-18

### Changed
- Category tags in `docs/socratic.md` are now derived from the existing `docs/<category>/` folder structure instead of a hardcoded list.
- Updated `socratic-merge` to discover valid categories from `docs/` subdirectories and fall back to `docs/decisions/`.

## 1.3.3 — 2026-07-18

### Changed
- Switched install instructions to `npx skills add todatasudata/socratic --global --yes`.
- Updated `.gitignore` to ignore agent-generated directories (`.agents/`, `.claude/`, `.cursor/`, `.windsurf/`) and `skills-lock.json`.

## 1.3.2 — 2026-07-18

### Changed
- Refactored `SKILL.md` with write-cut principles: removed fillers, tightened prose, converted explanations to lists, kept active voice.
- Updated `README.md` install instructions to cover local path and GitHub install via `skillport add`.

## 1.3.1 — 2026-07-18

### Changed
- Renamed frontmatter `name` from `socratic_architect` to `socratic` to match directory and satisfy `skillport` naming rules.
- Simplified install: use `skillport add /home/tdsd/agent_skills/socratic --yes`.

## 1.3.0 — 2026-07-18

### Added
- Invocation parameter `string` for the initial request description.
- `docs/socratic.md` artifact format: H2 topic + H3 datetime.
- `socratic-merge` CLI command and Python helper that distributes tagged discoveries into `docs/<category>/index.md`.

## 1.2.0 — 2026-07-18

### Changed
- Updated architect persona: from harsh to wise and slightly ironic.
- Replaced conflict-themed example with a creativity/cooperation example (collaborative interactive fiction platform).
- Added rules for respecting intent and handling blind spots gently.

## 1.1.0 — 2026-07-18

### Changed
- Rewrote `SKILL.md`: removed meta-commentary and fluff.
- Added skillport-compatible YAML frontmatter.
- Tightened dialogue rules and output format.
- Replaced long-form example with a concise, structured one.

## 1.0.0

### Added
- Initial draft of the Socratic Architect skill.
