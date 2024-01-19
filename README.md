# Game of Life
 
Conway's Game of Life:

This is a cellular automaton devised by mathematician John Conway in 1970.
It's a zero-player game, meaning its evolution is determined by its initial state, with no further input.
The "game" is played on a grid of cells, each of which can be alive or dead.
The state of the cells evolves over time based on simple rules. A dead cell with exactly three live neighbors becomes a live cell, and a live cell with fewer than two or more than three live neighbors becomes a dead cell.
The Game of Life has no players, as the outcome is entirely determined by the initial state.

How to run:
Call the Jar file with appropriate parameters
java -jar Game_of_Life.jar [int iteration numbers] [pattern]
Valid pattern keywords are: "r" for Random, "C" for crab and "b" for by-flops.