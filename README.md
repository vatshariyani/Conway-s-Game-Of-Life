# Conway-s-Game-Of-Life
Simple Conway's Game Of Life written in Python3.


**Rules:**

The universe of the Game of Life is an infinite, two-dimensional orthogonal grid of square cells, each of which is in one of two possible states, live or dead (or populated and unpopulated, respectively). Every cell interacts with its eight neighbors, which are the cells that are horizontally, vertically, or diagonally adjacent. At each step in time, the following transitions occur:

1. Any live cell with fewer than two live neighbors dies, as if by underpopulation.
2. Any live cell with two or three live neighbors lives on to the next generation.
3. Any live cell with more than three live neighbors dies, as if by overpopulation.
4. Any dead cell with exactly three live neighbors becomes a live cell, as if by reproduction.

The initial pattern constitutes the seed of the system. The first generation is created by applying the above rules to every cell in the seed, live or dead; births and deaths coincide, and the discrete moment at which this happens is sometimes called a tick.[nb 1] Each generation is a pure function of the preceding. The rules continue to be applied repeatedly to create further generations.
