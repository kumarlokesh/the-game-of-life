# the-game-of-life
A web app with an implementation of John Conway's Game of Life.
Following rules govern whether a live or dead cell is going to live or die in the next generation:
- Any live cell with fewer than two live neighbors dies, as if caused by under-population
- Any live cell with two or three live neighbors lives on to the next generation
- Any live cell with more than three live neighbors dies, as if by overcrowding
- Any dead cell with exactly three live neighbors becomes a live cell, as if by reproduction
