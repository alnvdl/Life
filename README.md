Life
====

A simple implementation of [Conway's Game of Life](http://en.wikipedia.org/wiki/Conway%27s_game_of_life) in C. Made just for fun.



# Building and running
Just run `make` to build it, and then run `game_of_life`. Type `h` in the command line to get help.

# About the game
It uses a 40x20 board represented by a Cartesian coordinate system. The origin is at the bottom left corner.

The status bar the the top shows the number of iterations (generations) and the number of active cells.

The command line is located at the bottom. There are four posible commands:
* n: run the (n)ext iteration. The Return key performs the same action.
* t: (t)oggle the state of a given cell. Further input will be needed for the coordinates in the form x,y.
* i: display (i)nformation about a given cell
* h: display this (h)elp text.
* q: (q)uit the game.

The first argument to the executable is optional, and should point to a text file that contains coordinates (in the form x,y) for active cells. In case the file cannot be opened, it will be ignored.

There are three example files: `glidergun`, `pulsar` and `test`. See the [Wikipedia page](http://en.wikipedia.org/wiki/Conway%27s_game_of_life) for these and more patterns.
