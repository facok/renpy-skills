# Ren'Py Skills Pack

A collection of Claude Code skills for Ren'Py visual novel development.

## Skills Overview

| Skill | File | Trigger |
|---|---|---|
| `renpy` | `skills/main-renpy-skill.md` | General Ren'Py development, project scaffolding, script writing, dialogue, branching, characters, transitions, audio, saves |
| `renpy-rpg` | `skills/renpy-rpg.md` | RPG stats, leveling, XP, equipment, turn-based combat, skill checks |
| `renpy-maps` | `skills/renpy-maps.md` | World maps, location navigation, travel systems, area unlocks |
| `renpy-minigames` | `skills/renpy-minigames.md` | Embedded minigames: puzzles, rhythm, cards, timed prompts |
| `renpy-screens` | `skills/renpy-screens.md` | Screen Language, custom UI, HUDs, menus, modal dialogs |

## Routing Rules

- Start with `renpy` (main skill) for any Ren'Py project discussion.
- Route to subsystem skills only when the user explicitly asks about or is implementing that specific feature.
- Main skill references subsystem skills by file path in `skills/` directory.
- All skills are self-contained; no cross-file dependencies at runtime.
