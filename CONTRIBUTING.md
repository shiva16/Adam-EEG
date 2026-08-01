# Contributing to Adam-EEG

Thanks for your interest in this board. This is a small open-hardware repository — contributions of any size are welcome.

## Ways to contribute

- **Bug reports**: found an error in the schematic or board (wrong footprint, missing connection, wrong part value)? Open an issue with the net/part name and what's wrong.
- **Build reports**: fabricated and assembled a board? Open an issue or PR describing what worked, what didn't, and any BOM substitutions you made — real build data is the most valuable contribution to a hardware repo.
- **KiCad / other CAD conversions**: this board is native EAGLE 6.6.0. A faithful conversion to KiCad or another open format is very welcome.
- **Routing / layout improvements**: if you improve noise performance, layer stackup, or component placement, open a PR with before/after reasoning.
- **Documentation**: clarifications to the README, added datasheets/reference links, or BOM sourcing notes.

## Before opening a PR

1. Open an issue first for anything non-trivial, so the change can be discussed before you spend time on it.
2. Keep schematic/board edits in the native EAGLE format (`.sch`/`.brd`) unless the PR *is* a format conversion.
3. Describe what you changed and why in the PR description — for hardware changes, include which nets/parts were touched.
4. If you've physically built and tested the change, say so — verified changes are prioritized.

## Code of Conduct

This project follows the [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you agree to abide by it.
