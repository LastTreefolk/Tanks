# Tanks
Tanksgame

Compiling on Linux:

1) Ubuntu:

sudo apt-get install g++ ncurses-dev

g++ tanks.cpp -lncurses -o tanks

2) OpenSuse 

sudo zypper install g++ ncurses-devel

g++ tanks.cpp -lncurses -o tankS

3)Fedora

sudo apt-get install g++ ncurses-devel

g++ tanks.cpp -lncurses -o tanks

4) Arch:

sudo pacman -S g++ ncurses

g++ tanks.cpp -lncurses -o tanks

Windows:

You need MinGw with curses-library

g++ tanks.cpp -lpdcurses -o tanks
