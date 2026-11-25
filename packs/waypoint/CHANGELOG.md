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

## 0.1.0 — first release by The Linux Workbench (was Waypoint KDE 0.5.0)
- Now built together with Vice Horizon and Natura: fixes and new
  features reach every theme. Global Themes are `org.thelinuxworkbench.waypoint.dark|light`;
  an install of 0.5.0 (`org.waypoint.*`) is moved over when you agree.
- Icons redrawn by the shared generator in Waypoint's style: graphite tiles with the amber bar,
  grey folders, file types told apart by colour.
- Panel looks are the shared ones in Waypoint's colours; Cards and Pills have no bar behind them;
  the top panel is 32 px (was 36).
- GTK 4: the widget images and the dark stylesheet are included now (check marks showed blank).
- The installer, Setup, Settings and the `waypoint` command are the shared programs: components,
  `--full`, checks what your choices need, About and Uninstall in Settings. 0.5's options still work.
- Licence texts in every installed folder.
- Icons readable in the panel: up to 32 px, app tiles use a bigger glyph (and no bar); tiles have
  no light edge; the top panel's margins are slimmer, so Task Manager icons are bigger.
- Light has its own icon theme (Waypoint Light), so toolbar and tray symbols are dark on light.
