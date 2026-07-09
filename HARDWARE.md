# Beaglebone Black - Hardware notes

## Specs
TI AM335x - 1 GHzz Cortex-A8 (ARMv7-A, NEON, 32-bit) - 512 MB DDR3 - 4 GB eMMc - microSD.

## Serial console
6-pin J1 header. **3.3v FTDI only - never 5 V.** GND=1, board-TX=4, board-RX=5. 115200 8N1 -> /dev/ttyUSB0

## Booting
- Boots from eMMC by default.
- Hold **S2** while applying power to boot from microSD.

## Reference docs
- BBB System Reference Manual (SRM): https://cdn-shop.adafruit.com/datasheets/BBB_SRM.pdf
- AM335x TRM + datasheet: https://www.ti.com/lit/ug/spruh73q/spruh73q.pdf

## vs the book's boards
|            | BBB              | RPi4               | BeaglePlay        |
|------------|------------------|--------------------|-------------------|
| SoC / core | AM335x · 1× A8   | BCM2711 · 4× A72   | AM625 · 4× A53    |
| Bits       | 32               | 64                 | 64                |
| Yocto MACHINE | beaglebone-yocto (in poky) | raspberrypi4-64 (meta-raspberrypi) | beagleplay (meta-ti) |