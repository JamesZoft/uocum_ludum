You'll need Ruby installed. 
This comes by default on Mac, and is easy to install on Linux.
https://www.ruby-lang.org/en/documentation/installation/

You also need to install sdl2:

On Mac:

brew install sdl2

On linux:

Please follow the instructions here: https://github.com/gosu/gosu/wiki/Getting-Started-on-Linux

As this game uses Curses to print text to the terminal, this will not work on 
Windows unless you run it inside a terminal emulator, as windows' cmd.exe
is not a real terminal.

To run:

ruby play_sokoban.rb

in the command prompt.