# MazeEscaper
This is a game written in jack language for nand2tetris course. You try to escape from the maze by reaching to circle. 
In the Jack language does not have any random function, I used Linear congruential generator to create RNG.
First key user pressed is used as the seed for the rng. Maze creation algorithm is Recursive Backtracking which is described at 
https://weblog.jamisbuck.org/2010/12/27/maze-generation-recursive-backtracking
