# Avatar

Source and distributable files for Kieran Potts' online profile icon.

## Tech stack

- SVG source, edited with [Boxy SVG](https://flathub.org/apps/com.boxy_svg.BoxySVG).
- `.png` and `.webp` distributables exported from the SVG source.

## Project structure

- `src/avatar-2026-master.svg` \
  The master source file.

- `dist/` \
  Exported distributables, organized by color persona (`blue`, `cyan`,
  `green`, `magenta`, `orange`, `pink`, `purple`, `red`, `teal`, `yellow`).
  Per `dist/README.md`: `blue` is the personal persona, `purple` is the
  `hacksltd` persona.

## References

The following technical standards (TS) govern this project. Fetch and ingest
the relevant standards as-and-when required for the task at hand.

- [**TS-9: Version Control**](https://kieranpotts.com/standards/009) \
  Use when working with Git. Covers commits, branching, merging, integration
  strategies, cutting releases, and configuring Git/PR/CI tooling.
