# LocalTAK

## Overview
LocalTAK is an extension to the Army's Cloud TAK infrastructure, designed to provide resilient TAK capabilities at the tactical edge. While Cloud TAK delivers robust centralized services, LocalTAK ensures continued operation when units are beyond reliable cloud connectivity or need to maintain strict emissions control. This complementary system enables sections and individual soldiers to maintain critical situational awareness capabilities even in disconnected, intermittent, and limited environments.

## Features
- Distributed architecture
- Peer-to-peer communication capabilities
- Simplified configuration and setup
- Offline and local first
- Syncs with Cloud TAK when internet connection is available

## Requirements
- ATAK installed on Android device
- ESP32 microcontroller

## HowTo
See the [HowTo](HowTo) folder for more information.
1. [Flashing ESP32](HowTo/FlashingESP32.md)
2. [Pairing With Phone](HowTo/PairingWithPhone.md)
3. [CloudTAK Bridge](HowTo/CloudTAKBridge.md) (Optional)


## Citations
- [Meshtastic](https://github.com/meshtastic)
- [Meshtastic-ATAK Plugin](https://github.com/meshtastic/ATAK-Plugin)
- [CivTAK](https://www.civtak.org/)