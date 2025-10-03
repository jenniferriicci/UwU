# UwU
my dots and themes for a very uwu rice
# My XFCE4 Customization Dotfiles

This package contains my personal XFCE4 desktop customizations, including themes, icons, cursor, panels, and terminal appearance. You can use it to make your desktop look like mine!

## Included Customizations

* **Panel Layouts & Launchers**

  * XFCE4 panel positions, sizes, and plugins
  * Custom app launchers on the panel

* **Terminal Appearance**

  * Colors, transparency, background, font, etc.
  * Saved in `~/.config/xfce4/xfconf/xfce-perchannel-xml/xfce4-terminal.xml`

* **Themes & Icons**

  * GTK theme: `Quartz-Chicle`
  * Cursor theme: `Oxygen-06-Magenta`
  * Icon pack: `MoePinkIcons`

* **GTK2 Configuration**

  * `.gtkrc-2.0` settings for older apps

## Installation

> **Warning:** This will overwrite existing settings in XFCE, GTK, and your panels. Backup first if needed.

1. Extract the archive:

```bash
tar -xzf meus-dots-completos.tar.gz -C ~
```

2. Restart XFCE session or log out and back in to apply:

* Panels, launchers, and terminal settings will be restored.
* Themes and icons will be available in Appearance and Settings.

3. Optional: Set GTK theme and cursor manually in **Settings → Appearance**.

## Notes

* Works on XFCE4 (tested on Linux Mint XFCE).
* Some paths may vary depending on your Linux distribution.
