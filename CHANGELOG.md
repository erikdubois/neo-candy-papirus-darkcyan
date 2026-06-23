# Changelog

## 2026.06.23 — Papirus darkcyan folder colour

### What Changed

Initial repo. The **neo-candy-papirus-darkcyan** folder icons were recoloured to **darkcyan** from the Papirus icon theme
and ship as `neo-candy-papirus-darkcyan-icons-git`, depending on `neo-candy-icons-git`.

### Files Modified

- Initial scaffold + usr/share/icons/neo-candy-papirus-darkcyan/

### Public folder icon (folder-publicshare)

Added `folder-publicshare` to the special-folder set so the **Public** folder no longer
falls back to a generic icon. Copied this variant's own colour-matched
`folder-image-people.svg` (folder + person headshot) to `folder-publicshare.svg` at
sizes 22–64, and `folder.svg` at 16px (headshot is illegible at that size).

### Files Modified

- usr/share/icons/neo-candy-papirus-darkcyan/{16x16,22x22,24x24,32x32,48x48,64x64}/places/folder-publicshare.svg (new)
