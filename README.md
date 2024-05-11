## Recreating Conway's Game of Life using JavaScript

Inspired by The Coding Train

https://www.youtube.com/watch?v=FWSR_7kZuYg&t=6s

### Steps

1. Create grid
2. Populate grid
3. create new grid
4. populate new grid based on rules for each cell
5. Check rules for each cell (x, y)
   row above
   up left (x-1, y-1)
   up
   up right
   current row
   left
   right
   next row
   down left
   down
   down right
6. create new grid
7. replace previous grid with new grid

###Rules

Birth Rule
Empty cell with exactly 3 live neighbors will become live

Death Rule

1. A live cell with 0 or 1 live neighbors will die from isolation
2. A live cell with 4 or more live neighbors will die from overcrowding

Survival Rule
A live cell with 2 or 3 live neighbors will remain alive
