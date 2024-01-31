## suko generator

Suko (a modified Sudoku game) is a popular logic-based number-placement puzzle where the objective is to fill a 3x3 grid with digits that compose the grid (often called regions or boxes) contain all of the digits from 1 to 9 without repetition.

Position:

 1, 2, 3

 4, 5, 6

 7, 8, 9

Array: [1, 2, 3, 4, 5, 6, 7, 8, 9]

Color: [G, G, G, O, O, O, Y, Y, Y]

This generator is able to generate a random pattern (digits) with sums and color hints.

### install via pip:
```
pip install suko
```
### check user manual:
```
suko -h
```
### execute generator:
```
suko g
```

#### output sample
Random Pattern (answer): [6, 9, 8, 4, 7, 3, 5, 2, 1]

Sums: [26, 27, 18, 13]

Color Pattern (sorting): [9, 7, 4, 3, 1, 2, 8, 6, 5]

Green : 10

Orange: 23

Yellow: 12
