# Cellular Sandbox

Paint living cells and discover how four simple rules can create motion, growth, and stillness.


## Try it

Run the glider, pause and toggle cells, then compare a random board with a hand-built still life.

## How it works

This implements Conway’s Game of Life with synchronous updates on a finite 32×32 board. Every next-generation cell is calculated from the previous generation, so update order does not affect the rules. Cells outside the board are dead. Timers stop when a preset or single-step action is selected.

