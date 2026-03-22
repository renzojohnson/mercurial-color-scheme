# Mercurial Color Scheme

[![License](https://img.shields.io/github/license/renzojohnson/mercurial-color-scheme.svg?style=flat-square)](https://github.com/renzojohnson/mercurial-color-scheme/blob/main/LICENSE)
[![Downloads](https://img.shields.io/packagecontrol/dt/Mercurial%20Color%20Scheme.svg?style=flat-square)](https://packagecontrol.io/packages/Mercurial%20Color%20Scheme)
[![Latest Release](https://img.shields.io/github/release/renzojohnson/mercurial-color-scheme.svg?style=flat-square)](https://github.com/renzojohnson/mercurial-color-scheme/releases/latest)

A dark and light color scheme for Sublime Text based on Warp Terminal's default palette. Clean, balanced, and easy on the eyes for long coding sessions.

## Variants

| Variant | Background | Best For |
|---------|-----------|----------|
| **Mercurial** (dark) | ![#181818](https://placehold.co/15x15/181818/181818.png) `#181818` | Low-light / night coding |
| **Mercurial Light** | ![#fafafa](https://placehold.co/15x15/fafafa/fafafa.png) `#fafafa` | Bright environments / daylight |

## Preview

### Mercurial (Dark)

![Mercurial Dark](preview.png)

### PHP

![PHP](screenshots/php.png)

### JavaScript

![JavaScript](screenshots/javascript.png)

### CSS

![CSS](screenshots/css.png)

### HTML

![HTML](screenshots/html.png)

## Installation

### Package Control (Recommended)

1. Open Command Palette (`Cmd+Shift+P` / `Ctrl+Shift+P`)
2. Select **Package Control: Install Package**
3. Search for **Mercurial Color Scheme**
4. Activate:
   - Dark: **Preferences > Color Scheme > Mercurial**
   - Light: **Preferences > Color Scheme > Mercurial Light**

### Manual Installation

1. Download the desired scheme files
2. Place in `Packages/User/` (Preferences > Browse Packages)
3. Activate via **Preferences > Color Scheme**

### Sublime Text < Build 3149

Use the `.tmTheme` files. Add to your settings:

```json
"color_scheme": "Packages/Mercurial Color Scheme/Mercurial.tmTheme"
```

## Colors (Dark)

| Role | Color | Hex |
|------|-------|-----|
| Background | ![#181818](https://placehold.co/15x15/181818/181818.png) | `#181818` |
| Foreground | ![#d8d8d8](https://placehold.co/15x15/d8d8d8/d8d8d8.png) | `#d8d8d8` |
| Comments | ![#585858](https://placehold.co/15x15/585858/585858.png) | `#585858` |
| Strings | ![#a1b56c](https://placehold.co/15x15/a1b56c/a1b56c.png) | `#a1b56c` |
| Keywords | ![#ba8baf](https://placehold.co/15x15/ba8baf/ba8baf.png) | `#ba8baf` |
| Functions | ![#7cafc2](https://placehold.co/15x15/7cafc2/7cafc2.png) | `#7cafc2` |
| Tags/Variables | ![#ab4642](https://placehold.co/15x15/ab4642/ab4642.png) | `#ab4642` |
| Classes/Types | ![#f7ca88](https://placehold.co/15x15/f7ca88/f7ca88.png) | `#f7ca88` |
| Numbers | ![#dc9656](https://placehold.co/15x15/dc9656/dc9656.png) | `#dc9656` |
| Library/Support | ![#86c1b9](https://placehold.co/15x15/86c1b9/86c1b9.png) | `#86c1b9` |

## Colors (Light)

| Role | Color | Hex |
|------|-------|-----|
| Background | ![#fafafa](https://placehold.co/15x15/fafafa/fafafa.png) | `#fafafa` |
| Foreground | ![#383838](https://placehold.co/15x15/383838/383838.png) | `#383838` |
| Comments | ![#909090](https://placehold.co/15x15/909090/909090.png) | `#909090` |
| Strings | ![#4d6820](https://placehold.co/15x15/4d6820/4d6820.png) | `#4d6820` |
| Keywords | ![#8b4d80](https://placehold.co/15x15/8b4d80/8b4d80.png) | `#8b4d80` |
| Functions | ![#2a6f8e](https://placehold.co/15x15/2a6f8e/2a6f8e.png) | `#2a6f8e` |
| Tags/Variables | ![#a03530](https://placehold.co/15x15/a03530/a03530.png) | `#a03530` |
| Classes/Types | ![#8a6d20](https://placehold.co/15x15/8a6d20/8a6d20.png) | `#8a6d20` |
| Numbers | ![#b06020](https://placehold.co/15x15/b06020/b06020.png) | `#b06020` |
| Library/Support | ![#247067](https://placehold.co/15x15/247067/247067.png) | `#247067` |

## Plugin Compatibility

Mercurial includes dedicated scopes for these popular Sublime Text plugins:

- **[GitGutter](https://packagecontrol.io/packages/GitGutter)** — colored gutter marks for insertions, deletions, and changes
- **[BracketHighlighter](https://packagecontrol.io/packages/BracketHighlighter)** — per-bracket-type coloring (curly, round, square, angle, tag, quote)
- **[SublimeLinter](https://packagecontrol.io/packages/SublimeLinter)** — error, warning, and info mark colors (SublimeLinter 4+)

## Supported Languages

Full syntax coverage for PHP, JavaScript, TypeScript, HTML, CSS, LESS, Sass/SCSS, JSON, YAML, Markdown, SQL, Python, Shell/Bash, CoffeeScript, Makefile, Twig, Handlebars, and all languages using standard TextMate scopes.

## Credits

- **Palette**: Based on [Warp Terminal](https://warp.dev) default dark theme
- **Author**: [Renzo Johnson](https://renzojohnson.com)
- **License**: MIT
