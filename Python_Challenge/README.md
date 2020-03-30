# Python Challenge

## Cronways Game of Life

Here I have uploaded my solution which generates a random life pattern in a 64x64 grid and the user can see 10 iterations of the lifeform.

The iterations are also stored as png files to view later.


## Rules

The rules of the game are simple, and describe the evolution of the
grid:

Birth: a cell that is dead at time t will be alive at time t + 1
if exactly 3 of its eight neighbors were alive at time t.

Death: a cell can die by:

1.  Overcrowding: if a cell is alive at time t + 1 and 4 or more of
its neighbors are also alive at time t, the cell will be dead at
time t + 1.
2. Exposure: If a live cell at time t has only 1 live neighbor or no
live neighbors, it will be dead at time t + 1.
3. Survival: a cell survives from time t to time t + 1 if and only
if 2 or 3 of its neighbors are alive at time t.

## APPLICATION

The Game of Life exhibits a property we call universality, meaning that
it can theoretically compute anything that can be computed.

A real life application of Game of Life is Image restoration on Triangular Tessellations

![Image Restoration](link-to-image)

