# SONY VAIO SVD11225PXB Hackintosh

## Images

(Add image here)

## Configuration

| Specifications | Details                                                  |
| ------------------- | ------------------------------------------- |
| Computer model      | SONY VAIO SVD11225PXB     |
| Processor           | Intel Core i5 Dual-Core 3537U  |
| RAM                 | 8GB DDR3 1866MHz |
| SSD                 | MSATA 256GB PM841 MZMTD256HAGM |
| OS                  | macOS Catalina 10.15.7 + Windows 10 |
| Integrated Graphics | Intel HD Graphics 4000      |
| Monitor             | FHD 1920x1080 touchscreen (13.7" - Broken, not tested) |
| Sound Card          | Realtek ALC275          |
| Wireless Card       | Intel Centrino Advanced-N 6235 + Bluetooth |
| Ethernet Card       | Realtek PCIe Gigabit Ethernet |

## Misc after install:
- Use ssdtPRgen tool to generate power management SSDT.
- Rename bootmgfw.efi file to bootmgfw.efi_ for dual-booting OpenCore.

## Current Status

- OpenCore version: 0.9.3
- **Apple TV+ not working due to dGPU not supported**
- **NFC not supported**
- Everything else works, except Airdrop.
- Audio patched and working correctly.
- Ensure to edit the **config.plist** and add valid  **PlatformInfo Generic** and **SMBIOS** values.

## To-do

- (none)
