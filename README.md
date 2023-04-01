# SuperLibretroDroid
SuperLibretroDroid is a simple C++ Libretro frontend library for Android. It originated from [LibretroDroid 0.9.0](https://github.com/Swordfish90/LibretroDroid/tree/0.9.0) and, in a few months, it will be powering [Emulair](https://github.com/RaduBratan/Emulair). The prefix "Super" is a nod to the Super Nintendo Entertainment System.

## Supported Features
- 2D Cores
- GL Cores
- Core variables
- Audio
- Gamepad events
- Touchscreen input
- Serialization and deserialization of game states
- Serialization and deserialization of SaveRAM
- Simple shader effects (such as CRT and LCD)
- Multiple disks

## Upcoming Features
[COMING SOON]

## Tested, Working Libretro Cores
- [FinalBurn Neo](https://docs.libretro.com/library/fbneo/)
- [MAME 2003-Plus](https://docs.libretro.com/library/mame2003_plus/)
- [Stella](https://docs.libretro.com/library/stella/)
- [ProSystem](https://docs.libretro.com/library/prosystem/)
- [Handy](https://docs.libretro.com/library/handy/)
- [Beetle Cygne](https://docs.libretro.com/library/beetle_cygne/)
- [Beetle PCE FAST](https://docs.libretro.com/library/beetle_pce_fast/)
- [Mupen64Plus](https://docs.libretro.com/library/mupen64plus/)
- [DeSmuME](https://docs.libretro.com/library/desmume/)
- [melonDS](https://docs.libretro.com/library/melonds/)
- [Citra](https://docs.libretro.com/library/citra/)
- [Gambatte](https://docs.libretro.com/library/gambatte/)
- [mGBA](https://docs.libretro.com/library/mgba/)
- [FCEUmm](https://docs.libretro.com/library/fceumm/)
- [Snes9x](https://docs.libretro.com/library/snes9x/)
- [Genesis Plus GX](https://docs.libretro.com/library/genesis_plus_gx/)
- [Beetle NeoPop](https://docs.libretro.com/library/beetle_neopop/)
- [PCSX ReARMed](https://docs.libretro.com/library/pcsx_rearmed/)
- [PPSSPP](https://docs.libretro.com/library/ppsspp/)

## Library Implementation
SuperLibretroDroid can be added to a standard build.gradle file by including the following piece of code:
```
dependencies {
    ...
    implementation 'com.github.radubratan:superlibretrodroid:<version>'
    ...
}
```

## Disclaimer
SLD is still in development. It cannot actually be used in a project, for now.
