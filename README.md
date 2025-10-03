# UwU
my dots and themes for a very uwu rice
# My XFCE4 Customization Dotfiles

This package contains my personal XFCE4 desktop customizations, including themes, cursor, panels, and terminal appearance. You can use it to make your desktop look like mine!

## Included Customizations

* **Panel Layouts & Launchers**

  * XFCE4 panel positions, sizes, and plugins
  * Custom app launchers on the panel

* **Terminal Appearance**

  * Colors, transparency, background, font, etc.
  * Saved in `~/.config/xfce4/xfconf/xfce-perchannel-xml/xfce4-terminal.xml`

* **Themes & Cursor**

  * GTK theme: `Quartz-Chicle`
  * Cursor theme: `Oxygen-06-Magenta`

* **GTK2 Configuration**

  * `.gtkrc-2.0` settings for older apps

* **Icon Pack Notice**

  * The icon pack I use (MoePinkIcons) is **not included** in the file due to its large size.
  * You can download it here: [MoePinkIcons / Moebuntu Themes](https://moebuntu.web.fc2.com/moethemes_eng.html)

## Installation

> **Warning:** This will overwrite existing settings in XFCE, GTK, and your panels. Backup first if needed.

1. Extract the archive:

```bash
tar -xzf meus-dots.tar.gz -C ~
```

2. Restart XFCE session or log out and back in to apply:

* Panels, launchers, and terminal settings will be restored.
* Themes and cursor will be available in **Settings → Appearance**.

3. Optional: Set GTK theme and cursor manually in **Settings → Appearance**.
4. Download and install MoePinkIcons separately from the link above to fully replicate my setup.

## Notes

* Works on XFCE4 (tested on Linux Mint XFCE).
* Some paths may vary depending on your Linux distribution.
