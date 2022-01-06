Pair-Programming Assignment
Partners: Valeriy Nehovora, Hatem Rakkad

Main file
  - Instantiate new game
  - Call the game.start method

3 classes
  - Game
  - Question
  - Player

Game
  - Turn
  - Players (Instantiate 2) -- in the initialize method 
  - Array of players
  - gameOver (boolean, default false) Private
  - Method
    - start

Question
  - Random generated numbers (two of them) Private
  - Sum of the numbers Private
  - Method
    - question(returns strings)
    - answerCheck?(returns boolean)
  
Player
  - Name (Player1, Player2) -- read access
  - Score/Lives -- read access
  - Method 
    - Decreasing Lives/Score
    - alive?