# B550 Desktop Ryzentosh (R5 5600G)

OpenCore bootloader config files for my workstation hackintosh.

`RX 580` support arrived on macOS Monterey 12.6

## What about 12.0 Monterey?


This repo only works with Monterey due to that issue.


## System Information

| Name     |                     Model |
| :------- | ------------------------: |
| CPU      |             Ryzen 5 5600G |
| GPU      |               AMD RX 580  |
| SSD      | Samsung 970 Evo Plus NVMe |
| Board    |    MSI B550m Steel Legend |
| Ethernet |  2.5G Realtek Gaming      |

- OpenCore: v0.8.5
- MacOS: macOS Monterey 12.6

## Guide

<https://dortania.github.io/OpenCore-Install-Guide/prerequisites.html>
<https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html>

### SMBIOS

Selected: `MacPro7,1`

Don't forget to change device uuid, board serials and network mac address
Go to <https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html#platforminfo> For information on setting up SMBIOS platform info


## What works

- [x] Graphics
- [x] iServices
- [x] USB
- [x] Bluetooth
- [x] Sleep
- [x] Audio
- [x] iOS Simulator

  
