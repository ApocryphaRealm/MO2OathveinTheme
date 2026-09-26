# Oathvein MO2 Theme

A Mod Organizer 2 theme in the look of the Apocrypha Menu Framework theme "Oathvein": charcoal panels, thin grey lines with crossed scratch marks at the corners, a blood-red highlight and dark red separators. Made to sit beside [Oathvein UI](https://www.nexusmods.com/skyrimspecialedition/mods/160916) by Nithog; that mod is not required.

Separators and mods are coloured separately (separators are the mod list's parent rows; MO2's conflict highlight on mods stays visible), the theme's frame art sits around panels and group boxes, buttons, check boxes and arrows are drawn in the theme's shape, and the toolbar and MO2's small buttons carry the Njordlinger icon set in the theme's line colour.

## Install

Extract into your Mod Organizer 2 folder (the one with ModOrganizer.exe) so `stylesheets\Oathvein.qss` and the `stylesheets\Oathvein\` folder land in MO2's own `stylesheets` folder, then pick **Oathvein** in Settings > General > Style. Restart MO2 once so the toolbar picks up the icons.

## Building

`python tools\build_theme.py` (Python 3 with Pillow) writes `stylesheets\` from `src\theme.qss.in`, `src\theme.json` (the palette), the art in `src\` and the icons in `src\icons\`.

Licence: GPL-3.0-or-later (`LICENSE`, `NOTICE.md`).
