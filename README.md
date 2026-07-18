# Socratic Architect

Agent skill for turning vague ideas into structured technical specs through Socratic dialogue.

## Install

```bash
skillport add /home/tdsd/agent_skills/socratic --yes
ln -sf /home/tdsd/agent_skills/socratic/socratic-merge ~/.local/bin/socratic-merge
```

## Usage

Invoke the skill with a `string` parameter describing the initial request. During the dialogue the agent writes key discoveries to `docs/socratic.md`. After the dialogue run:

```bash
socratic-merge
```

This distributes tagged entries from `docs/socratic.md` into `docs/<category>/index.md`.

## Files

- `SKILL.md` — skill instructions
- `CHANGELOG.md` — version history
- `socratic-merge` — CLI helper for merging dialogue artifacts into docs
