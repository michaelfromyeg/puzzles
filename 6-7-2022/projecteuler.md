# Today&#39;s Puzzle (by [Puzzles](https://github.com/michaelfromyeg/vscode-puzzles))

Created: 7&#x2F;6&#x2F;2022

Source: projectEuler

ID: 502

## Puzzle

We define a block to be a rectangle with a height of 1 and an integer-valued length. Let a castle be a configuration of stacked blocks. Given a game grid that is w units wide and h units tall, a castle is generated according to the following rules: Blocks can be placed on top of other blocks as long as nothing sticks out past the edges or hangs out over open space. All blocks are aligned/snapped to the grid. Any two neighboring blocks on the same row have at least one unit of space between them. The bottom row is occupied by a block of length w. The maximum achieved height of the entire castle is exactly h. The castle is made from an even number of blocks. The following is a sample castle for w=8 and h=5: Let F(w, h) represent the number of valid castles, given grid parameters w and h. For example, F(4,2) = 10, F(13,10) = 3729050610636, F(10,13) = 37959702514, and F(100,100) mod 1 000 000 007 = 841913936. Find (F(1012,100) + F(10000,10000) + F(100,1012)) mod 1 000 000 007.
