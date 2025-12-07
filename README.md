# TanStack Theme for Visual Studio Code

<div align="center">
<img src="./images/icon.png" alt="TanStack Theme for Visual Studio Code" width="200">
</div>

## Description

This is the non-official TanStack Theme for Visual Studio Code, inspired by the [TanStack](https://tanstack.com/) brand colors.

## Preview

### Base
<div align="center">
<img src="./images/screenshots/base.png" alt="TanStack Theme for Visual Studio Code" width="600">
</div>

### Soft
<div align="center">
<img src="./images/screenshots/soft.png" alt="TanStack Theme for Visual Studio Code" width="600">
</div>

## Color Palette

This theme uses a tropical-inspired color palette derived from the TanStack brand:

| Role | Color | Hex | Preview |
|------|-------|-----|---------|
| Background | Deep Ocean | `#0F2A35` | ![#0F2A35](https://via.placeholder.com/20/0F2A35/0F2A35) |
| Foreground | White | `#F3F3F3` | ![#F3F3F3](https://via.placeholder.com/20/F3F3F3/F3F3F3) |
| Selection | Ocean Highlight | `#1E4555` | ![#1E4555](https://via.placeholder.com/20/1E4555/1E4555) |
| Comments | Deep Teal | `#3B7E9F` | ![#3B7E9F](https://via.placeholder.com/20/3B7E9F/3B7E9F) |
| Cyan | Teal | `#50B195` | ![#50B195](https://via.placeholder.com/20/50B195/50B195) |
| Green | Grassy Green | `#6AAB2E` | ![#6AAB2E](https://via.placeholder.com/20/6AAB2E/6AAB2E) |
| Orange | Coral | `#F68453` | ![#F68453](https://via.placeholder.com/20/F68453/F68453) |
| Pink/Red | Red | `#D05952` | ![#D05952](https://via.placeholder.com/20/D05952/D05952) |
| Purple | Brown/Orange | `#BA704B` | ![#BA704B](https://via.placeholder.com/20/BA704B/BA704B) |
| Yellow | Lime | `#E7E659` | ![#E7E659](https://via.placeholder.com/20/E7E659/E7E659) |

### UI Variants

| Variable | Hex | Purpose |
|----------|-----|---------|
| BGDarker | `#061419` | Deepest background |
| BGDark | `#0A1D25` | Dark panels/sidebars |
| BG | `#0F2A35` | Main editor background |
| BGLight | `#163845` | Lighter panels |
| BGLighter | `#1E4555` | Hover states/highlights |

## Installation

### From VS Code Marketplace

1. Open **Extensions** sidebar in VS Code (`Ctrl+Shift+X` / `Cmd+Shift+X`)
2. Search for `TanStack Theme`
3. Click **Install**
4. Select the theme: `Ctrl+K Ctrl+T` → Choose **TanStack Theme** or **TanStack Theme Soft**

### Manual Installation

1. Download the `.vsix` file from [Releases](https://github.com/enBonnet/tanstack-theme-vscode/releases)
2. Run `code --install-extension tanstack-theme-x.x.x.vsix`

## Variants

- **TanStack Theme** - Standard version with vibrant colors
- **TanStack Theme Soft** - Softer, desaturated version for reduced eye strain

## Development

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+)
- [pnpm](https://pnpm.io/) or npm

### Setup

```bash
# Install dependencies
pnpm install

# Build the theme
pnpm run build

# Package the extension
pnpm run package
```

### Project Structure

```
├── src/
│   └── tanstack.yml      # Theme source file (YAML)
├── theme/
│   ├── tanstack.json     # Generated theme
│   └── tanstack-soft.json
├── scripts/
│   ├── build.js          # Build script
│   └── generate.js       # Theme generator
└── images/
    └── icon.png          # Extension icon
```

## Inspiration

This theme is based on the [Dracula Theme](https://draculatheme.com/) schema, with colors adapted from the TanStack brand palette featuring tropical/beach aesthetics.

## License

[MIT License](LICENSE)

---

Made with 🌴 by [Ender Bonnet](https://github.com/enBonnet)
