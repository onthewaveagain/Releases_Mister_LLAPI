
This is an alternative repository to the official MiSTer LLAPI repository.
It is a fork of MiSTer official cores. LLAPI implementation has been ported from the original LLAPI github.
This has been done during my spare time. I still need to figure out how to automate a little the process of updating the cores in order to keep up with the MiSTer developments.

If you want to contribute, please contact me.

## Cores source code

Consoles

* Gameboy            : https://github.com/onthewaveagain/Gameboy_MiSTer_LLAPI
* Gameboy Advance    : https://github.com/onthewaveagain/GBA_MiSTer_LLAPI
* Gameboy Advance 2P : https://github.com/onthewaveagain/GBA_MiSTer_LLAPI/tree/GBA2P
* Super Nintendo     : https://github.com/onthewaveagain/SNES_MiSTer_LLAPI
* NES                : https://github.com/onthewaveagain/NES_MiSTer_LLAPI
* Genesis            : https://github.com/onthewaveagain/Genesis_MiSTer_LLAPI
* Sega CD            : https://github.com/onthewaveagain/MegaCD_MiSTer_LLAPI
* Master System      : https://github.com/onthewaveagain/SMS_MiSTer_LLAPI
* Neo Geo            : https://github.com/onthewaveagain/NeoGeo_MiSTer_LLAPI
* Turbografx16       : https://github.com/onthewaveagain/TurboGrafx16_MiSTer_LLAPI

Arcade (MRA support)

* Pacman             : https://github.com/onthewaveagain/Arcade-Pacman_MiSTer_LLAPI
* Donkey Kong        : https://github.com/onthewaveagain/Arcade-DonkeyKong_MiSTer_LLAPI
* IremM62            : https://github.com/onthewaveagain/Arcade-IremM62_MiSTer_LLAPI

## How to install

* Place the content of _LLAPI into the _LLAPI folder on your SD card

## Features

* Improved some controllers mapping
* New Arcade core with MRAs support
* All cores have been updated to include all features developped during Q4 2021

## Future plans

* "Industrialize" release process including an custom update_llapi.sh script
* "Reverse engineer" LLAPI implementation and improve code documentation (started with GB core and need to extend this as some cores also have a specific LLAPI implementation)
* LLAPIze more cores including consoles, upcoming PS1 and Saturn, Arcade and Computer cores...
* Add Paddle support to Master System and Atari cores
* Add fast polling mode for nes zapper
* LLAPIze Controller Test core and enrich its functionalities to enable BliSTer firmware updates and configuration
