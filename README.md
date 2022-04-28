# ML_RL-TicTacToe
A game of tic-tac-toe with a RL agent.

## How to run
Run the notebook in colab or copy the notebook to experiment with the code. 

## Implementation
Implementation is done in three classes: State, ComputerPlayer and HumanPlayer class.

### State
The state class acts as the board as well as the judge. The three major components that make up this algorithm are state, action and reward. The state is the state of the board which is essentially a 2D matrix, the action is the moves made by the players and reward is given at the end of each game.

### Computer Player
The Player represents our agent and has everything responsible for choosing actions, recording the state of the board, updating the state-value estimations and save and load policy.

### Human Player 
The human player is the user, so we take the input for the row and column for the user’s next move, check whether that position is empty and update the board accordingly.

### Training
The state handles the board training and the player handles our agent and learning, so we can now start our training process. We put two players against each other for training. The agent is trained for 200000 iterations

```
Run the 'training' code block in the notebook
```

### Play (vs computer)
There are two players to play against, the agent trained with another RL agent which performs moderately. And the agent trained with a minimax player which performs worse since the learning is less.

```
Run the 'human vs computer' code block in the notebook
```

### Play (vs human)

```
Run the 'human vs human' code block in the notebook
```

## Report
Full report available [here](https://github.com/saurabhburewar/ML_RL-TicTacToe/blob/main/AAI%20project%20-%20Report.pdf)
