# Connect Four (AI Game)

Connect Four is a game where two players alternate turns dropping colored discs into a vertical grid. Each player uses a different color (usually red or yellow), and the objective of the game is to be the first player to get four discs in a row.
![connect Four Game](https://github.com/jaya6400/Connect-Four/assets/66017717/e79071c1-e672-4499-9d3e-ba8b2bfb13c0)


```
obs contains two pieces of information:

obs.board - the game board (a Python list with one item for each grid location)
obs.mark - the piece assigned to the agent (either 1 or 2)
obs.board is a Python list that shows the locations of the discs, where the first row appears first, followed by the second row, and so on. We use 1 to track player 1's discs, and 2 to track player 2's discs. For instance, for this game board:


obs.board would be [0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 1, 0, 0, 0, 0, 0, 2, 2, 0, 0, 0, 0, 2, 1, 2, 0, 0, 0, 0, 1, 1, 1, 0, 0, 0, 0, 2, 1, 2, 0, 2, 0].

config
config contains three pieces of information:

config.columns - number of columns in the game board (7 for Connect Four)
config.rows - number of rows in the game board (6 for Connect Four)
config.inarow - number of pieces a player needs to get in a row in order to win (4 for Connect Four).
```
