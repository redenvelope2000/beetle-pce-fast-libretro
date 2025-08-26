This is for adding mouse input to PC-Engine Shanghai and PC-Engine CDROM Shanghai II. The game code that accepts user inputs is trapped into the emulated CPU handler, mouse input states are translated into proper actions there.

## Changes from the original code

libretro.cpp - ROM patches and the mouse state reader.

hu6280.c - the trap handler code.

## Building
make

For your convenience, a reference build for Windows is added.
