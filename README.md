# Omarchy Vesper Theme Port

This project is a port of the **Vesper Theme**, which I personally use in **Visual Studio Code**.

The goal of this port is to bring the same aesthetics, color scheme, and overall visual experience of the Vesper Theme to other environments where it is not natively available.

## 🎨 Theme Structure

This theme follows the **Omarchy theme standard** and includes:

- **colors.toml** - Base color definitions (primary, accent, all 16 ANSI colors)
- **alacritty.toml** - Alacritty terminal configuration
- **btop.theme** - System monitor theme
- **icons.theme** - Icon theme identifier
- **neovim.lua** - Neovim colorscheme configuration
- **vscode.json** - VS Code theme settings
- **waybar.css** - Status bar styling
- **walker.css** - App launcher styling
- **mako.ini** - Notification daemon styling
- **ghostty.conf** - Ghostty terminal configuration
- **kitty.conf** - Kitty terminal configuration
- **chromium.theme** - Chromium browser theme
- **backgrounds/** - Theme wallpapers

## Screenshots

![Fastfetch + Btop](img/fastf+btop.png)

![Neovim + VS Code](img/nvim-vsc.png)


## Installation

1. Press **Super + Alt + Space** to open the Omarchy menu.  
2. Select: **Install > Style > Theme**  
3. Paste the link below and press **Enter**:

```bash
https://github.com/Zheonatan/omarchy-vesper-theme.git
```

The theme will be installed to `~/.config/omarchy/themes/vesper/` and can be activated with:

```bash
omarchy theme set vesper
```

## 🎯 Supported Applications

This theme provides styling for:
- **Terminals**: Alacritty, Ghostty, Kitty
- **Editors**: Neovim, VS Code
- **System**: Waybar (status bar), Walker (launcher), Mako (notifications)
- **Utilities**: Btop (system monitor)
- **Browsers**: Chromium-based browsers

---

## Special Thanks

A very special thanks to [**dotsilva**](https://github.com/dotsilva) for the incredible help in configuring **Ghostty**, **Kitty**, **Neovim**, and **Visual Studio Code**.

