# Mastering Embedded Linux Development - on Beaglebone Black

Worked-through notes for *Mastering Embedded Linux Development* (4th edition), ported form the book's boards (RPi4 / Beagleplay) to the **Beaglebone Black** (AM335x, Cortex-A8, 32-bit ARMv7, 512 MB). The interesting part is the *delta*:
what changes when the target is a single-core 32-bit board.

## Board
Beaglebone Black rev C - TI AM335x, 1 GHz Cortex-A8, 512 MB DDR3, 4 GB, eMMc.

## Repo map
- `notes/`   — chapter-by-chapter writeups (start here)
- `configs/` — my U-Boot / kernel / Buildroot / Yocto configs & fragments
- `patches/` — patches I had to apply
- `scripts/` — flashing, serial, build helpers
- `SETUP.md` · `HARDWARE.md` · `VERSIONS.md` — reproduce my environment

## Progress
| Ch | Topic | Status | Notes |
|----|-------|--------|-------|
| 1  | Elements of embedded Linux | ☐ | |
| 2  | Toolchains | ☐ | |
| 3  | Bootloaders (U-Boot) | ☐ | |

Legend: ☐ todo · 🔄 in progress · ✅ done

## License
Code/scripts: MIT. Notes/docs: CC BY 4.0. Not affiliated with the book; no book text reproduced.