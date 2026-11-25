# Changelog

## 0.1.2
- The installer can now download Panel Colorizer and KVitals from the KDE Store for you (it asks first; your user only, no password; checks the Store's checksum) on distros without an AUR helper, such as Fedora. Exit-and-come-back and manual install still work.
- Fixed: the top panel is now built for the edition you switch on. Before, it followed whichever colour scheme was active before the install, so a Dark install could get the Light panel look.
- Fixed: hints no longer point to AUR-only options on other distros; the "get it yourself" lines no longer look like commands.

## 0.1.1 — widgets are no longer bundled
- Panel Colorizer (Luis Bocanegra) and KVitals (Yassine Amjad) are not included in the zip any more.
  The installer checks for them, installs from the AUR if you use yay or paru, and otherwise lists
  where to get them (KDE Store, the authors' repositories). You can exit the installer, install them
  yourself, and run it again. The theme installs without them; the panel is plainer.
- Removed `<command> widget` and the `--widgets` option.

## 0.1.0 — first release
- Natura, Dark and Light: ink, sage and vermillion, from the Natura wallpapers.
- Everything the other The Linux Workbench themes have: Global Themes, Plasma Style, colours,
  window borders, Kvantum, GTK 3/4, icons, cursors, Konsole, the top panel with six looks,
  Fastfetch colours and design, Settings, Setup and the `natura` command.
- Icons readable in the panel: up to 32 px, app tiles use a bigger glyph (and no bar); tiles have
  no light edge; the top panel's margins are slimmer, so Task Manager icons are bigger.
