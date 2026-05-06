# AskSia Design System

Design tokens, component specs, and visual guidelines for the AskSia product — maintained as a single Markdown file so AI coding tools can consume it directly.

## How to use with AI coding tools

### Cursor
Add the raw file URL as a rule or paste it into context:
```
https://raw.githubusercontent.com/raejamm02-ai/asksia-design-system-/main/DESIGN.md
```
Or add it to `.cursorrules` at the top of your project:
```
Follow the AskSia design system: https://raw.githubusercontent.com/raejamm02-ai/asksia-design-system-/main/DESIGN.md
```

### Claude Code
Reference the file at the start of a session:
```
Use this design system as the visual contract for all UI work:
https://raw.githubusercontent.com/raejamm02-ai/asksia-design-system-/main/DESIGN.md
```

### GitHub Copilot
Copy the contents of `DESIGN.md` into a `design-system.md` file at your project root — Copilot will pick it up automatically as workspace context.

---

## What's inside `DESIGN.md`

| Section | Contents |
|---|---|
| `colors` | Full base palette (primary / neutral / success / error / warning / info, each 50–900) + semantic roles (text / surface / border / icon) |
| `typography` | Inter — heading h1–h8, body lg/md/sm × 4 weights, caption xs–lg |
| `rounded` | 9-step radius scale (none → 4px → full) |
| `spacing` | Complete scale from 0.5px to 256px |
| `components` | Button, Input, Search, Chip, Tab, Navigation, Card, Chat, Badge, Menu, Dialog, Snackbar, Tooltip, Progress, Avatar, Switch |
| `brand` | Logo, Logotype, IP Character (7 states), Lucide icon sizing |
| `patterns` | Surface layering rules, interactive states, border usage guide, chat layout, icon sizing |

---

## Key design tokens (quick reference)

| Token | Value | Usage |
|---|---|---|
| Primary | `#4e4df4` | Buttons, links, active states |
| Text primary | `#1a1a1d` | Main body text |
| Text secondary | `#34343b` | Supporting text |
| Text tertiary | `#818193` | Placeholders, captions |
| Surface lowest | `#ffffff` | Cards, modals, inputs |
| Surface lower | `#f8f8f9` | Page background |
| Surface low | `#f1f1f3` | Sidebar, panels |
| Border secondary | `#eaeaec` | Card borders |
| Border focus | `#4e4df4` | Focus ring (2px) |
| Font family | Inter | All UI text |
| Border radius md | `8px` | Inputs, buttons |
| Border radius lg | `12px` | Cards |
| Border radius full | `9999px` | Pills, avatars |

---

## Source of truth

This file is extracted from the **AskSia Team Library** in Figma. When the Figma library is updated, this file should be updated to match.

Figma Team Library → [AskSia Team Library](https://www.figma.com/design/ZEm9L8DlrXdHWuB1zpCZn4/Team-Library)
