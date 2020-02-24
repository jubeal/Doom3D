# Doom3D
The last graphical project of the C part of 42 school's curriculum

This project use SDL2 and OpenGL and is designed to work on MacOS, be sure to have it before trying to run it.

If you have Brew you can use the command make install to install the SDL2 library and the OpenGL library.

You will probably have to change the path of your ibraries in the Makefile.
If you have to, open the Makefile file and go to the IFLAGS and LFLAGS lines to change the path to your libraries repository (just after the find in IFLAGS line and the -L in LFLAGS line).

Then type make and it will create a executable file named wolf3D.
