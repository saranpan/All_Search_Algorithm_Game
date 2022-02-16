# Search Algorithm Game

Using Blind or Heuristic Search Algorithm like A* to find the optimal solution for that game 




## Available Games
- [Maze Runner](#Maze-Runner)
- [24 Game](#24-Game)
- [Pokemon Boulder Puzzle](#Pokemon-Boulder-Puzzle)



## Maze Runner
[![open in colab](https://camo.githubusercontent.com/52feade06f2fecbf006889a904d221e6a730c194/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/drive/1kUlh2VSk3N3npCS_RneXjXSsjBhGI9yx?usp=sharing)

Find the best path solution useing <b>A* Algorithm</b>
![mazegame](https://camo.githubusercontent.com/d01b2178f6e8671b0f649c8618e849ad9c40584ca538ceee05ead01483de9f6d/68747470733a2f2f692e6962622e636f2f5a4777345651592f494d472d383131312e6a7067)

### Instruction
This game is on the 10✕10 array
> Start : The Player starts at the top left (at the first row and column)
> End : The Player wins if they reach at the last row, column 9 

The Action list that the player is allowed to use is
> Move Left
> Move Right
> Move up
> Move down

The Player cannot move their action if...
> The index that the player stand have an obstacle 
> If the player got shot by the laser
<u>Note</u> : Laser will turn on when the user's step is even (2,4,...,2n)

- Every Action's costs is 1, but 0.5 when the player obtain the fast shoe
- The Obstacle at the row and column = (8,8) are cracked when the player press the unlocking lever at the row and column = (3,10)





## 24 Game
[![open in colab](https://camo.githubusercontent.com/52feade06f2fecbf006889a904d221e6a730c194/68747470733a2f2f636f6c61622e72657365617263682e676f6f676c652e636f6d2f6173736574732f636f6c61622d62616467652e737667)](https://colab.research.google.com/drive/1072XzxX9XOkb6u9_L8etAWnnqJHC2jnI?usp=sharing)

The Action list that the player is allowed to use is
> +
> -
> ×
> ÷ 

The Player cannot move their action if...
> The result is negative eg. 6-9 = -3
> The result is indivisible (Not integer) eg. 6/9 
> Divide by zero eg. 6÷0

- This game also collects the statistics of the time players spent on solving. You can check out what is the fastest time 
- Autoplay mode is available, you can play wihtout have to type command line by line 

```sh
game = game24(autoplay=True)
```


## Pokemon Boulder Puzzle
"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."
