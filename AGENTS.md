# Project

A collection of color presets for [Minimal Theme](https://github.com/kepano/obsidian-minimal) applied via the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin.

## Theme structure

Each theme lives in `themes/{name}/` with two files:
- `style-settings.json` — exported from Style Settings plugin
- `README.md` — description, Settings section, Preview section, Installation section

Folder naming: `{mood/base}-{accent-color}` in lowercase kebab-case (e.g. `dark-amber`, `dark-pink`).

## README structure for a theme

```
# Theme Name

One-line description.

## Settings

Table of required settings (accent color, color scheme, etc.), or a note that all Minimal Theme Settings are left at defaults.

## Preview

<screenshot>

## Installation

1. Follow the general [installation steps](../../README.md#installation)
2. Apply the settings from the table above
```

## What not to add

- Color tables listing hex values — not useful
- Comments explaining what code does

## Commits

Short and calm. No big explanations, no bullet breakdowns. One line is enough.