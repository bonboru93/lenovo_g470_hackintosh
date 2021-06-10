# lenovo_g470_hackintosh

| Product | Lenovo g470 |
| - | - |
| CPU | i5 2450m |
| MEM | DDR2 2GB * 2 |
| HDD | TOSHIBA 500GB |
| GPU | HD6370m (disabled) |
| WIFI & BLE | Broadcom 943224 (replaced) |

# BIOS setting
| Item | Value |
| - | - |
| Intel Virtualization Technology | Disabled |
| Graphic Card | UMA |


# OSX version tested
10.14.6 Mojave (current EFI)

# Not Working
* HD3000 is not originally supported by mojave, try [Fix-Graphics-HD-3000-Mojave-10.14](https://github.com/chris1111/Fix-Graphics-HD-3000-Mojave-10.14)
* g470 had no UEFI, need BootInstall_X64.tool to patch your usb installer for legacy boot, see [legacy setup](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/mac-install.html#legacy-setup)

# Thanks
[Dortania's OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/)
