# 2048 game

This project was implementend following next rules:
- The game field is 4 x 4
- Each cell can be empty or contain one of the numbers: 2, 4, 8 ... 2^n
- All the numbers should be moved in the selected direction until all empty cells are filled in
- 2 equal cells should be merged into a doubled number
- The merged cell can’t be merged twice during one move
- The move is possible if at least one cell is changed after the move
- After move 2 or 4 appears in a random empty cell. 4 probability is 10%
- When 2048 value is displayed in any cell, win message will be shown.
- The `game over` message will be shown if there are no more available moves.
- Score increases with each move. The score will be increased by the sum of all merged cells.
- You can move cells using arrow buttons on your keyboard, or using swipes if you use touchscreen