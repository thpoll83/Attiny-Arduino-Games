Games for the AttinyArcade+ 
===========================
by Thomas Pollak

What is AttinyArcade+?

It is the Attiny Arcade Standard with more buttons:left/right/up/down and action button instead of only two buttons.

The original games have been writen by Andy Jackson, I just changed them to work with multiple buttons.

Note from Andy Jackson - Twitter: @andyhighnumber
------------------------------------------

Info on programming the Attiny85 chip can be found online, here's an example: https://create.arduino.cc/projecthub/arjun/programming-attiny85-with-arduino-uno-afb829 - don't forget to burn the bootloader (it's a menu option under 'Tools' on the Arduino IDE) the first time you flash the chip and if you need to change between 8Mhz and 16Mhz clocks (all my games are 8Mhz, except Pacman which is 16Mhz).

See www.webboggles.com for details of the AttinyArcade hardware.

These games are based on the Attiny85 device running at 8Mhz on its internal clock, or 16Mhz for pac-man (don't forget to burn the bootloader when you first flash a new chip- the option to do this is in the "Tools" menu on the Arduino IDE).

The following games have been modified for the AttinyArcade+
=====================================================================================
- Pacman_Attiny_Arcade: PacMan clone for the original Attiny. This is the best of the lot in my opinion. Unlike the other games here, this needs to be flashed with a 16Mhz internal clock bootloader (all the others are 8MHz). Send me a message via twitter if this presents any problems.
- SpaceAttackAttiny: Space Invaders clone for the original Attiny (also allows for modified version of hardware with fire button - see circuit diagram in folder)
- Frogger_Attiny_Arcade: Frogger clone for the original Attiny (also allows modified version of hardware with jump button - same hardware config as SpaceAttack above - see schematic in folder)
- UFO_Stacker_Attiny: Two games in one sketch - UFO (from www.webboggles.com) and Stacker (from me).
- Tetris_Multi_Button: A Tetris cline, as above but designed for multi-button pad (see circuit schematic in folder for details of the hardware)
