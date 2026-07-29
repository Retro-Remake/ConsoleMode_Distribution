# ConsoleMode Distribution

Installer, update metadata, and release binaries for **Console Mode** on MiSTer FPGA.

## Guide

[Video Guide](https://youtu.be/1sfifOftuFE) 

[Console Mode Wiki](https://github.com/Takiiiiiiii/SuperStation-Documentation/wiki/Console-Mode)

## Discord Server

[Console Mode Channel](https://discord.gg/74pb5PJRxX)

## Install

Run `Install_Console_Mode.sh` from the MiSTer Scripts menu. Some releases also need
the Linux image and kernel from the [Supplementary Files release](https://github.com/Retro-Remake/ConsoleMode_Distribution/releases/tag/supplementary).
Copy `linux.img` and `zImage_dtb` to `/media/fat/linux/`.

## Contents

| File | Purpose |
|---|---|
| `Install_Console_Mode.sh` | Installer (frontend, host, core, inis, fonts) |
| `ConsoleMode_arm` | Frontend |
| `MiSTer_ConsoleMode` | Host |
| `menu_ConsoleMode.rbf` | Menu core |
| `version.txt`, `notes.txt` | Update version and changelog |

## Licensing

The `ConsoleMode_arm` frontend is Apache-2.0 ([`LICENSE`](LICENSE)). The other
binaries are GPL. Their corresponding source is available:

| Component | License | Source |
|---|---|---|
| `MiSTer_ConsoleMode` | GPL-3.0 | https://github.com/Retro-Remake/MiSTer_ConsoleMode |
| `menu_ConsoleMode.rbf` | GPL-3.0 | https://github.com/Retro-Remake/menu_ConsoleMode |
| `zImage_dtb` | GPL-2.0 | https://github.com/MiSTer-devel/Linux-Kernel_MiSTer |
| `linux.img` | GPL-2.0 + others | https://github.com/MiSTer-devel/Linux_Image_creator_MiSTer |

Bundled libraries and fonts are listed in `licenses/00-NOTICES.txt`.

Copyright 2026 Retro Remake.
