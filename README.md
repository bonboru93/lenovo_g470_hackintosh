# lenovo_g470_hackintosh

| Product | Lenovo g470 |
| - | - |
| CPU | Intel i5 2450m |
| MEM | ADATA DDR3 1333 2GB * 2 |
| HDD | TOSHIBA 500GB |
| GPU | HD6370m (disabled) |
| Ethernet | Qualcomm Atheros AR8152 |
| WIFI | Broadcom 943224 (replaced) |

# BIOS settings
| Item | Value |
| - | - |
| Intel Virtualization Technology | Disabled |
| Graphic Device | UMA Graphic|


# OSX version tested
10.13.6 High Sierra (current EFI)

# Not Working
* BatteryManagement
* g470 has no UEFI, need BootInstall_X64.tool to patch your usb installer for legacy boot, see [legacy setup](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/mac-install.html#legacy-setup)

# Thanks
[Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
