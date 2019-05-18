# JHU Ai Course Resources

AI course resources created during my Teaching Assistantship with Prof. Philipp Koehn at Johns Hopkins University.

During my assisntanship, I gave a lecture on game playing (enclosed below) and created materials which are provided in this repository.

## Game playing [[colab notebook]](https://colab.research.google.com/github/warmspringwinds/jhu-ai-course-teaching/blob/master/game_playing/notebook.ipynb) [[jupyter notebook]](game_playing/notebook.ipynb) [[slides]](game_playing/lecture_slides.pdf)

<p align="center">
  <img src="https://github.com/warmspringwinds/jhu-ai-course-teaching/blob/master/game_playing/chess_puzzle_solution.gif" width="40%" align="middle">
</p>

Jupyter notebook guides a student through:

<p align="center">

1. Minimax algorithm.
2. Completely solving the game in checkmate puzzle (feasible since it only requires looking a couple of moves ahead).
3. Evaluation function (allows to avoid exploring the full game tree by approximating desirability of a board positions).
4. Alpha-beta prunning algorithm (prunes nodes that are known to not affect the final decision in mini-max).
5. Combines all introduced concepts into chess-playing agent.
6. Allows students to play against the agent or observe the agent playing against itself.
    
</p>

## Uninformed Search [[colab notebook]](https://colab.research.google.com/github/warmspringwinds/jhu-ai-course-teaching/blob/master/uninformed_search/notebook.ipynb) [[jupyter notebook]](uninformed_search/notebook.ipynb)

<p align="center">
  <img src="https://github.com/warmspringwinds/jhu-ai-course-teaching/blob/master/uninformed_search/search_viz.gif" width="40%" align="middle">
</p>

Jupyter notebook guides a student through:

<p align="center">

1. Implementation of search tree (allows us to recover the solution once a target node is found).
2. Implementation of breadth-first algorithm.
3. Implementation of uniform-cost search algorithm.
4. Application of this algorithms for the problem of finding the shortest path on the map of Hopkins Homewood campus.
5. Explanation on why breadth first search is not optimal when applied to this problem (nodes on the map graph are not placed uniformly) and why uniform-cost search is optimal in this case.
    
</p>


## Deep Reinforcement Learning [[colab notebook]](https://colab.research.google.com/github/warmspringwinds/jhu-ai-course-teaching/blob/master/deep_rl/notebook.ipynb) [[jupyter notebook]](deep_rl/notebook.ipynb)

<p align="center">
  <img src="https://github.com/warmspringwinds/jhu-ai-course-teaching/blob/master/deep_rl/deep_rl_graph.png" width="40%" align="middle">
</p>

Jupyter notebook guides a student through:

<p align="center">

1. Implementation of a simple deep neural network that takes chess board as input.
2. Stochastic environment which is represented by a weak stockfish engine that will play against our agent. Starting position of the chess game was greatly simplified to adjust to limited computational resources of students.
3. Reward discounting.
4. Policy gradients.
5. Optimization loop where we use policy gradients to adjust weights of our network and improve our decisions as a result of that.
    
</p>