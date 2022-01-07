# CGZ-CPU-01

![](https://github.com/Zekfoo/CGZ/blob/main/Images/CGZ_Front.jpg)
![](https://github.com/Zekfoo/CGZ/blob/main/Images/CGZ_Back.jpg)

As a follow-up to my [AGZ](https://github.com/Zekfoo/AGZ) project, I have once again redesigned original Game Boy hardware, this time with the Game Boy Color. Following my naming conventions for the AGZ, I've dubbed the PCB the *"CGZ-CPU-01"*, and the console itself the *"CGZ-001"*. This is a one-off production of what I envisioned as my ideal GBC.

Unlike my AGZ repo, I do not have a lengthy write-up for this design, since I didn't have any grievances with the original GBC hardware and my only design goal was to bring the same features of the AGZ over to the Game Boy Color.

![](https://github.com/Zekfoo/CGZ/blob/main/Images/PCB_Front.jpg)

### Features

+ 4-layer 1.2mm PCB, purple silkscreen, ENIG surface finish
![](https://github.com/Zekfoo/CGZ/blob/main/Images/PCB_Front_Bare.jpg)
![](https://github.com/Zekfoo/CGZ/blob/main/Images/PCB_Back_Bare.jpg)
+ GBC CPU

+ 1700mAh LiPo battery

  + USB-C rechargeable with charge LED indicator

  + Supports safe charge-and-play

  + On-board battery protections – short-circuit, over-charge, over-discharge, over-temperature
![](https://github.com/Zekfoo/CGZ/blob/main/Images/CGZ_Charging.jpg)

+ Completely redesigned power delivery

  + Power switch debouncing

  + 5V boost converter

  + 3.3V buck converter

  + Full ground plane
  
+ Completely redesigned audio circuits

  + Stereo volume potentiometer

  + Dedicated speaker and headphone amplifiers

  + 1W 8-ohm speaker

+ Tactile buttons

  + Snaptron tactile domes for DPAD and A/B

  + Tactile switches for START/SELECT

+ FunnyPlaying Retro Pixel IPS 2.0 display

+ Hand-polished atomic purple shell

### Acknowledgements

Thanks to all the members of the [Gameboy Discord](https://discord.gg/gameboy) community for their continued support.

Special thanks to [HDR](https://martinrefseth.com/) for compiling the [CGB circuit schematics and board scans](https://nintenfo.github.io/repository/systems/GBC/documentation/schematics/).

Special thanks to [b23n](https://mmm.page/b_2_3_n) for sharing his [shell polishing method](https://mmm.page/b_2_3_n.mod_polishing).