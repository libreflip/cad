# Libreflip — CAD

CAD and mechanical design data for Libreflip, an open-source, automated
book scanner built at c-base Berlin.

## Contents

| Directory/File | Contents |
|---|---|
| `3d-printed/FDM/` | 3D-printable parts for standard FDM printers |
| `3d-printed/SLA/` | 3D-printable parts for resin/SLA printers |
| `drawings/` | Technical drawings (PDF) of major assemblies (backplate, suction box, fan shroud, electronics housing, bookholder, connector plate, light assembly, overview) |
| `img/` | Photos of the assembled machine |
| `plot/` | Parts list plots/exports |
| `bom_neu.ods` | Bill of materials |

## File naming

Printable parts are prefixed with the quantity needed, e.g.
`2pcs-camera-holder-movable.stl` means two of that part are required.

## ⚠️ Outdated files

`drawings/` (last updated 2018-12-31) and `plot/` (last updated 2017-07-17)
have not been updated since. Current changes and ongoing development are
**not** reflected in these files — check the individual 3D-printed part
files and their commit history for the current state instead.

## Related repositories

- [`sans`](https://github.com/libreflip/sans) — command & control software
- [`serif`](https://github.com/libreflip/serif) — web frontend
- [`monospace`](https://github.com/libreflip/monospace) — bookscanner controller firmware
- [`kerning`](https://github.com/libreflip/kerning) — deployment utilities
