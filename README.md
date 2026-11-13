# Blue View OS theme for Omarchy

A dark navy Omarchy theme with a bright blue accent, blue-to-gold window borders, and Blue View wallpapers for day, golden hour, and night.

## Install the theme

```bash
omarchy theme install https://github.com/frank-blueview-ai/omarchy-blue-view-os-theme.git
```

Omarchy applies the theme after installing it. The installer replaces any existing theme directory named `blue-view-os`; back up a local theme with that name before installing. The theme sets `Yaru-blue-dark` as its icon theme; install that icon theme separately if needed.

## Add the Blue View desktop controls

The theme repository contains appearance files and wallpapers. The living sky, screensaver, Blue View settings window, title-bar controls, and taskbar controls are provided by the separate [Blue View Window Theme plugin](https://github.com/frank-blueview-ai/Blue-View-Window-Theme-Omarchy). Omarchy's theme installer does not install or run those plugins.

On an existing Omarchy installation, follow that repository's installation instructions. To install its controls while keeping your currently selected theme, use its `--no-theme` option:

```bash
git clone https://github.com/frank-blueview-ai/Blue-View-Window-Theme-Omarchy.git
cd Blue-View-Window-Theme-Omarchy
./install.sh --no-theme
```

The plugin installer downloads and builds Hyprland title-bar and window-snapping plugins, adds user-level configuration, and installs the Blue View shell plugins. Review its [README](https://github.com/frank-blueview-ai/Blue-View-Window-Theme-Omarchy#readme) before installing. Afterward, click the Blue View icon in the bar for screensaver, clock, location, window appearance, and taskbar settings. Use the title-bar opacity button to adjust an individual window.

The [Blue View Omarchy fork](https://github.com/frank-blueview-ai/omarchy/tree/quattro/contrib/blue-view) also includes an optional copy of this desktop integration.

## License

Copyright (c) 2026 The Blue View Group Corporation. Theme colors are marked as licensed under the PolyForm Noncommercial License 1.0.0; see [LICENSE](LICENSE). Please review the license before use, particularly for commercial use. The separately installed desktop plugin has its own license.
