<div align="center">
<h1>TanStack Theme for Visual Studio Code</h1>

[![Version](https://img.shields.io/github/package-json/v/enBonnet/tanstack-theme-vscode?color=3ECF8E&style=for-the-badge&label=VS%20Marketplace)](https://marketplace.visualstudio.com/items?itemName=enbonnet.tanstack-theme)
[![Open VSX Version](https://img.shields.io/static/v1?label=Open%20VSX&message=Download&color=9B8AE0&style=for-the-badge&logo=open-vsx)](https://open-vsx.org/extension/enBonnet/tanstack-theme)
[![Downloads](https://img.shields.io/visual-studio-marketplace/d/enbonnet.tanstack-theme?color=33B074&style=for-the-badge&label=Downloads)](https://marketplace.visualstudio.com/items?itemName=enbonnet.tanstack-theme)

<img src="./images/icon.png" alt="TanStack Theme for Visual Studio Code" width="200">
</div>

## 📋 Table of Contents

- [✨ Features](#-features)
- [🎨 Preview](#-preview)
- [🚀 Installation](#-installation)
- [🎛️ Using the Theme](#-using-the-theme)
- [🎨 Color Palette](#-color-palette)
- [🛠️ Development](#-development)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [💖 Credits](#-credits)

## ✨ Features

- 🎨 Beautiful dark theme inspired by TanStack's brand colors
- 👀 Optimized for long coding sessions
- 🖥️ Supports all major programming languages
- 🎯 Perfect for TanStack developers
- 🌙 Two variants: Standard and Soft

## Description

This is the non-official TanStack Theme for Visual Studio Code, inspired by the [TanStack](https://tanstack.com/) brand colors.

## 🎨 Preview

### Base Theme
<div align="center">
<img src="./images/screenshots/base.png" alt="TanStack Theme Base" width="600">
</div>

### Soft Variant
<div align="center">
<img src="./images/screenshots/soft.png" alt="TanStack Theme Soft" width="600">
</div>

## 🎨 Color Palette

This theme uses a tropical-inspired color palette derived from the TanStack brand with ocean/beach aesthetics:

| Role | Color | Hex | Preview |
|------|-------|-----|---------|
| Background | Deep Ocean | `#0F2A35` | ![#0F2A35](https://via.placeholder.com/20/0F2A35/0F2A35) |
| Foreground | White | `#F3F3F3` | ![#F3F3F3](https://via.placeholder.com/20/F3F3F3/F3F3F3) |
| Selection | Ocean Highlight | `#1E4555` | ![#1E4555](https://via.placeholder.com/20/1E4555/1E4555) |
| Comments | Deep Teal | `#3B7E9F` | ![#3B7E9F](https://via.placeholder.com/20/3B7E9F/3B7E9F) |
| Cyan | Teal | `#50B195` | ![#50B195](https://via.placeholder.com/20/50B195/50B195) |
| Green | Grassy Green | `#6AAB2E` | ![#6AAB2E](https://via.placeholder.com/20/6AAB2E/6AAB2E) |
| Orange | Coral | `#F68453` | ![#F68453](https://via.placeholder.com/20/F68453/F68453) |
| Red | Coral Red | `#D05952` | ![#D05952](https://via.placeholder.com/20/D05952/D05952) |
| Purple | TanStack Purple | `#9B8AE0` | ![#9B8AE0](https://via.placeholder.com/20/9B8AE0/9B8AE0) |
| Yellow | Lime | `#E7E659` | ![#E7E659](https://via.placeholder.com/20/E7E659/E7E659) |

### UI Variants

| Variable | Hex | Purpose |
|----------|-----|---------|
| BGDarker | `#061419` | Deepest ocean |
| BGDark | `#0A1D25` | Dark panels/sidebars |
| BG | `#0F2A35` | Main editor background |
| BGLight | `#163845` | Lighter panels |
| BGLighter | `#1E4555` | Hover states/highlights |

### ANSI Terminal Colors

| ANSI | Name | Hex | Bright Hex |
|------|------|-----|------------|
| 0/8 | Black | `#0A1D25` | `#3B7E9F` |
| 1/9 | Red | `#D05952` | `#F68453` |
| 2/10 | Green | `#6AAB2E` | `#50B195` |
| 3/11 | Yellow | `#E7E659` | `#F0F5A0` |
| 4/12 | Blue | `#3B7E9F` | `#50B195` |
| 5/13 | Magenta | `#9B8AE0` | `#B8A8FF` |
| 6/14 | Cyan | `#50B195` | `#7AD9D0` |
| 7/15 | White | `#F3F3F3` | `#FFFFFF` |

## 🚀 Installation

### VS Code Marketplace
[![VS Code Marketplace](https://img.shields.io/visual-studio-marketplace/v/enbonnet.tanstack-theme?style=for-the-badge&label=VS%20Code%20Marketplace&color=3ECF8E)](https://marketplace.visualstudio.com/items?itemName=enbonnet.tanstack-theme)

### Open VSX Registry
[![Open VSX Registry](https://img.shields.io/open-vsx/v/enBonnet/tanstack-theme?style=for-the-badge&label=Open%20VSX%20Registry&color=9B8AE0)](https://open-vsx.org/extension/enBonnet/tanstack-theme)

## 🎨 Using the Theme

1. Open the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`)
2. Type "Preferences: Color Theme" and press Enter
3. Search for "TanStack Theme"
4. Select either "TanStack Theme" or "TanStack Theme (Soft)" from the list

### Recommended Settings

For the best experience, add these to your `settings.json`:

```json
{
  "workbench.colorTheme": "TanStack Theme",
  "editor.fontFamily": "'Victor Mono', Monaco, Menlo, 'Courier New', monospace",
  "editor.fontSize": 16,
  "editor.lineHeight": 1.5,
  "editor.fontWeight": "600",
  "editor.wordWrap": "on",
}
```

- [Victor Mono](https://rubjo.github.io/victor-mono/)

## 🎨 Theme Variants

- **TanStack Theme** - Standard version with vibrant colors
- **TanStack Theme Soft** - Softer, desaturated version for reduced eye strain

## 🛠 Development

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

## 🤝 Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to:

1. Open an [issue](https://github.com/enbonnet/tanstack-theme-vscode/issues)
2. Submit a pull request
3. Share your feedback

## 📬 Stay Updated

For updates, star this repository and follow me on [GitHub](https://github.com/enbonnet).

## 💖 Credits

- Inspired by the beautiful TanStack brand colors and design
- Special thanks to the VS Code community for their amazing theming support
- This theme is based on the [Dracula Theme](https://draculatheme.com/) schema, with colors adapted from the TanStack brand palette featuring tropical/beach aesthetics.
- Thanks to all contributors who help improve this theme

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">
Made with 💚 by <a href="https://enbonnet.com">Ender Bonnet</a>
</div>

