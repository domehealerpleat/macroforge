# Usage Guide — macroforge

## Main Window

The dashboard shows live status and the primary action. *(Screenshot:
`assets/screenshots/main.png`)*

## Core Workflow

1. Launch macroforge
2. Configure options in the Settings tab
3. Use the main action (or global hotkey)
4. Status icon turns green when active

## Global Hotkeys (defaults, editable)

| Hotkey | Action |
|---|---|
| `Ctrl + Alt + X` | Toggle macroforge on/off |
| `Ctrl + Alt + S` | Open settings |
| `Shift + F9` | Panic key — restore defaults instantly |

## Profiles

Create per-scenario profiles in the Profiles tab, save to
`%APPDATA%\macroforge\profiles\`, share as files. Community presets live in
[`data/profiles/`](../data/profiles/).

## CLI Mode

```powershell
macroforge.exe --help        # all commands
macroforge.exe --version
```

All GUI actions are available as CLI flags for scripting and automation.
