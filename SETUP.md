# Host Setup

## Machine
Ubuntu 26.04 LTS, 0x86-64, ~100 GB free (Yocto is hungry).

## Packages
sudo apt install gawk wget git diffstat unzip texinfo gcc build-essential \
  chrpath socat cpio python3 python3-pip python3-pexpect xz-utils \
  debianutils python3-git python3-jinja2 libsdl1.2-dev bmap-tools picocom

## Cross-toolchain
How I got it (distro package / crosstool-NG / Yocto SDK) - record which, and the tuple.

## Serial terminal
picocom - see scripts/serial.sh