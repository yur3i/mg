# Mg
This is my fork of the OpenBSD `mg` text editor. It's mainly for personal use and its pretty complete but feel free to suggest anything or open any issues if you feel it is neccessary. 

# Changes

Altering much of the kill ring functionality such that C-w is the main was to interact with the kill ring. Things like C-k and M-d do not.

Altering many keybindings to my preferences. Eg M-s and M-a for saving and opening respectively.

To change keys yourself edit `keymap.c` and recompile.
