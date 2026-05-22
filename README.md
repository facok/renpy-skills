# renpy-skills

Claude Code skills for Ren'Py visual novel development.

## Structure

| Skill | File | Trigger |
|---|---|---|
| `renpy` | `skills/main-renpy-skill.md` | Core VN development (script, characters, branching, saves) |
| `renpy-rpg` | `skills/renpy-rpg.md` | RPG systems (stats, battles, progression, HUD) |
| `renpy-maps` | `skills/renpy-maps.md` | World navigation and location systems |
| `renpy-minigames` | `skills/renpy-minigames.md` | Reusable minigame patterns and implementations |
| `renpy-screens` | `skills/renpy-screens.md` | Screen language, UI patterns, and components |

## Installation

### Via CC Switch

1. Open **CC Switch** → Skills → Add Repository
2. Enter: `https://github.com/facok/renpy-skills`
3. Install to **Claude Code**

### Manual

Clone to your Claude Code skills directory:

```bash
git clone https://github.com/facok/renpy-skills.git ~/.claude/skills/renpy-skills
```

## Purpose

This repository serves as a structured reference for organizing knowledge about Ren'Py, focusing on scalable project architecture and reusable patterns.

### Core topics covered

* Canonical project folder structure
* Naming conventions (labels, variables, flags, images, screens)
* Character definition patterns
* Story/script standards (label hierarchy, branching, Python usage)
* Centralized flags and variables (`systems/flags.rpy`)
* Image and sprite naming (auto-detection, `LayeredImage`)
* Transforms and transitions (named, reusable, no magic numbers)
* Audio management (including fade helpers)
* Save system and chapter boundary handling
* Branching patterns (flat labels vs nested menus)
* Quality checklist for consistency and maintainability

Content is exploratory and may evolve over time.

## License

Apache 2.0
