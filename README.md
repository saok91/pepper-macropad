# pepper – Custom Macropad PCB

This repository contains the **source design files** for **pepper**, a custom mechanical macropad designed using **KiCad**.

## Repository Contents

### Source files (tracked)
These files are the **source of truth** for the design and are version-controlled:

- `pepper.kicad_sch` – Schematic
- `pepper.kicad_pcb` – PCB layout
- `pepper.kicad_pro` – KiCad project configuration

### Generated files (ignored)
The following files are intentionally **not tracked** via `.gitignore`:

- 3D exports: `*.stl`, `*.step`, `*.stp`, `*.wrl`, `*.obj`
- Fabrication outputs: Gerbers, drills, pick-and-place files
- KiCad autosave, backup, and cache files
- BOM exports (`.csv`, `.xlsx`)
- OS / editor temporary files

Generated outputs may be shared separately (e.g. releases) when the design is ready.

## Tools

- **EDA**: KiCad (v7+ recommended)
- **Version control**: Git

## Project Status

- Work in progress (WIP)
- Not yet released for manufacturing

## Notes

- This repository contains **design sources only**
- Do not manufacture or modify outputs without validating against the KiCad source files

## License

TBD
