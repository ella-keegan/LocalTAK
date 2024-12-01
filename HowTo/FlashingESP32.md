# Quick Guide: Flashing ESP32 with Meshtastic Firmware

⚠️ **IMPORTANT**: Always attach antenna before powering on the radio to avoid damage!

## Prerequisites

## Easy way

[web installer](https://flasher.meshtastic.org/)


## CLI (Linux)

### Install Python and esptool

#### Debian/Ubuntu

[Download](https://github.com/meshtastic/firmware/releases) the firmware and extract the zip file.

```bash
sudo apt-get install python3 python3-pip
sudo pip3 install --upgrade esptool
# Its best to be a sudo user to run the next command
cd path/to/firmware
./device-install.sh -f firmware-BOARD-VERSION.bin

```
#### Nix-OS

```bash
nix-shell -p esptool python3 
# Its best to be a sudo user to run the next command
cd path/to/firmware
./device-install.sh -f firmware-BOARD-VERSION.bin
```
