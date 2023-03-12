# AlphaZeroFromScratch

![tictactoe](https://raw.githubusercontent.com/tomasbourdain/AlphaZeroFromScratch/master/assets/tictactoe.gif)
![connectfour](https://raw.githubusercontent.com/tomasbourdain/AlphaZeroFromScratch/master/assets/connectfour.gif)

Implementation of AlphaZero for Tic-Tac-Toe and ConnectFour

This project aims to create an intelligent game-playing agent using the AlphaZero algorithm, which combines deep neural networks and Monte Carlo tree search to learn and improve its play over time. Specifically, we focused on implementing AlphaZero for two classic board games: TicTacToe and ConnectFour.

To achieve this, we first defined the game rules and created a game environment that could simulate the games and keep track of their state. Then, we trained a deep neural network to predict the value of a game state and the probability of selecting each possible move. We used self-play to generate training data and update the neural network parameters, gradually improving the agent's play.

## Model Architecture

![modelArchitecture](https://raw.githubusercontent.com/tomasbourdain/AlphaZeroFromScratch/master/assets/Model_Architecture.jpeg)


### Resources:
- Monte Carlo Tree Search (https://www.cs.swarthmore.edu/~meeden/cs63/s19/reading/mcts.html)
- AlphaZero Paper (https://arxiv.org/pdf/1712.01815.pdf)
- AlphaZero Tutorial (https://www.youtube.com/watch?v=wuSQpLinRB4&t=2722s&ab_channel=freeCodeCamp.org)
