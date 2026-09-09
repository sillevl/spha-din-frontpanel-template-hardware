# Front-panel template

Reusable KiCad design used as the basis for SPHA module front panels.

> **Lifecycle: retain as a template or historical design.** Its schematic is shared with an input front panel, but its PCB, project settings, and final backup are unique; outright removal is not currently valid. See `../../docs/hardware-project-lifecycle-review.md`.

## Design files

- `frontpanel-template.kicad_pro` — KiCad project
- `frontpanel-template.kicad_sch` — top-level schematic
- `frontpanel-template.kicad_pcb` — PCB layout

## Working with the project

Open the `.kicad_pro` file in KiCad. The design includes files originating from an older KiCad workflow; review schematic links, footprints, design rules, zones, and manufacturing outputs after any conversion or upgrade.

KiCad source files and project-specific libraries are the source of truth. Generated BOM, Gerber, assembly, and fabrication-house outputs are excluded from the repository; regenerate and verify them before manufacturing.

## Repository notes

Temporary KiCad state, locks, autosaves, and backup directories are excluded by `.gitignore`. Board revision, tested KiCad version, manufacturing revision, and hardware/firmware compatibility still need to be recorded when provenance is confirmed.
