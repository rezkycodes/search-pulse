<br/>
<p align="center">
  <h3 align="center">Search Pulse</h3>

  <p align="center">
    A GNOME Shell Extension - Spotlight-style Search for GNOME
    <br/>
    <br/>
  </p>
</p>

![Contributors](https://img.shields.io/github/contributors/rezkycodes/search-pulse?color=dark-green) ![Forks](https://img.shields.io/github/forks/rezkycodes/search-pulse?style=social) ![Stargazers](https://img.shields.io/github/stars/rezkycodes/search-pulse?style=social) ![Issues](https://img.shields.io/github/issues/rezkycodes/search-pulse) ![License](https://img.shields.io/github/license/rezkycodes/search-pulse) 

## About

Search Pulse is a GNOME Shell extension that brings the apps search widget out of Overview, similar to macOS Spotlight or Alfred. Access your applications and files instantly with a keyboard shortcut.

**✨ Now supports the latest GNOME Shell versions: 48, 49, and 50!**

### Features

* 🔍 Popup search box accessible from anywhere
* 🎨 Customizable colors, background, and borders
* 🌫️ Blurred background effect
* 🖥️ Multi-monitor support
* ⚡ Fast and lightweight
* 🎯 Keyboard-driven workflow

## Compatibility

- ✅ GNOME Shell 48
- ✅ GNOME Shell 49
- ✅ GNOME Shell 50 (Latest)

## Installation

### From GNOME Extensions Repository

Visit [extensions.gnome.org](https://extensions.gnome.org/) (Coming soon)

### Manual Installation

1. Clone this repository:
```bash
git clone https://github.com/rezkycodes/search-pulse.git
cd search-pulse
```

2. Copy to extensions directory:
```bash
cp -r search-pulse@rezkycodes@gmail.com ~/.local/share/gnome-shell/extensions/
```

3. Enable the extension:
```bash
gnome-extensions enable search-pulse@rezkycodes@gmail.com
```

4. Restart GNOME Shell:
   - **X11**: Press `Alt+F2`, type `r`, press Enter
   - **Wayland**: Log out and log back in

## Usage

### Default Keybinding

`Ctrl+Super+Space` (Customizable in preferences)

> **Note**: `Super` is the Windows key on most keyboards, or the Command key on Mac keyboards.

## Configuration

Access preferences through GNOME Extensions app or by clicking the extension icon in the top panel (if enabled).

### Customization Options

- Search box position and size
- Background color and opacity
- Border radius and thickness
- Text and icon colors
- Animation speed
- Window effects (tint, monochrome, blur)
- Keyboard shortcuts

### Blurred Background

The blurred background feature requires **imagemagick** to be installed:

```bash
sudo dnf install ImageMagick  # Fedora
sudo apt install imagemagick  # Ubuntu/Debian
```

## Credits

- Original concept inspired by [Search Light](https://github.com/icedman/search-light) by icedman
- Blur-My-Shell for background blurring code
- Modified and maintained by [rezkycodes](https://github.com/rezkycodes)

## License

This project is licensed under the GPL-2.0-or-later License - see the LICENSE file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Support

If you encounter any issues or have suggestions, please [open an issue](https://github.com/rezkycodes/search-pulse/issues) on GitHub.
