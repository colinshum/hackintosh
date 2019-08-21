# Hackintosh

[CAUTION] Use at your own risk!

## Gallery

![Picture](./images/1.jpg)
![Picture2](./images/2.jpg)
![Specs](./images/3.png)

---

## Components

| Parts List    | Peripherals |
| ------------- | ----------- |
| Intel i7 8700K | Alienware AW3418DW 34" 1440p Ultrawide Monitor |
| ASUS Strix Z370-I | LG 27UD59P-B 27" 4K IPS Monitor |
| 32GB G.Skill Trident Z RGB DDR4-2400 | Logitech MX Master 2S |
| XFX Vega 64 8GB | Apple Magic Trackpad 2 |
| Dell M.2 DW 1650 Wireless AC/BT Card | TOFU 60 - Tealios v2 |
| Ghost S1 - Ash |
| Noctua NH-L12 |
| Corsair SF750 |

---

## Getting Started

This repository contains the necessary information to run macOS on the listed hardware above. It is tested and working with macOS Mojave 10.14.5.

In order to use my `config.plist`, ensure that you fill in all sections of the file that are `[REDACTED]` as they must be unique for each installation.

## Kexts

Since kexts get updated all the time, here's a list of every kext I used to get this setup to work. Mount your EFI partition and place these kexts under `EFI/Clover/Kexts/Other`.

| Kexts |
| ----- |
| AirportBrcmFixup.kext |
| AppleALC.kext |
| FakeSMC.kext |
| IntelMausiEthernet.kext |
| Lilu.kext |
| USBInjectAll.kext |
| WhateverGreen.kext |
