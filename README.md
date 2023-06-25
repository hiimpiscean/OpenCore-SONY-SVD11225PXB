# SONY VAIO SVD11225PXB Hackintosh

## Images

![Screen Shot 2023-06-25 at 22 34 25](https://github.com/hiimpiscean/OpenCore-SONY-SVD11225PXB/assets/106610508/f5063b47-fa4b-4c0d-8122-c443510b9b72)

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
- For wifi: install to /Library/Extensions, require disabling csrutil first (Cannot inject due to OpenCore throws prelink error).

## Current Status

- OpenCore version: 0.9.3
- **Apple TV+ not working due to dGPU not supported**
- **NFC not supported**
- Everything else works, except Airdrop.
- Audio patched and working correctly.
- Ensure to edit the **config.plist** and add valid  **PlatformInfo Generic** and **SMBIOS** values.

## To-do

- Touchscreen testing (my laptop has its display broken thus cannot test).
