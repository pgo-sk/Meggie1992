# Meggie1992
ZX Spectrum graphics utility

Meggie v. 1.0 by Pego & FAY-FE 28 Jan 1992
==========================================
The hackers utility (for finding and grabbing graphisc from data blocks)

This utility was programmed to grab different graphics out ouf the games data files.
The 3 modes support byte-by-byte, mask/sprite coding etc. formats of storing the graphics/fonts in ZX Spectrum software.

This version supports loading tapes and saving the choosen graphics on tapes. Tested to run OK in Fuse. Just change the tape file to export your graphics.


Demo file:
There is a demo file on the TZX - "DEMO.dat "
Press load (L) on the same tape/TZX until you see a distorted image (demo file was loaded)
Now make the viewing window smaller (O) until a ship appears on top
-Meggie_Man_ROM_demo_4x12_mode_1.png

Usage/Functions:
A - display currently viewed address (beginning byte)
R - display the X/Y width of viewing window

1234 - viewing modes

L - loads next tape data block
K - saves the current wieving window

Q/S & O/P - make viewing window bigger/smaller
-this enables you to see the graphic in correct format, for example sprites 6x3 characters/sprites (48x24 pixels) are displayed correctly only in 6x3 format.

W/D - scroll sprite up/down one pixel line (depends on mode & width)

Cursor keys - move viewing window's start
E/F - -//-


How to see the ROM font:
Use Address 15616 in one character wide mode 1
-Meggie_Man_ROM_font_addess.png

Switch to mode 3, 32 wide, 3 high
-Meggie_Man_ROM_font_whole.png

================================================
originally programmed by Pego & FAY-FE on ZX Spectrum using Slavomit Labsky's MRS software in assembler.
Contact: pegosys at gmail dot com
