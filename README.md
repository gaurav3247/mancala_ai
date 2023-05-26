Mancala AI.

The board game of Mancala implemented in python with two types of bots/computer players.
1. Randy_ai: randomly selects a possible move.
2. Agent: Mancala bot that uses minimax or alpha-beta and a heuristic to select a move.

How to play-
Use command line with following command

$python3 mancala_gui.py -d <dimension> -a <player A> -b <player B>

Parameters-
  1. -h: help
  2. -d: dimensions of the board (# of pockets)
  3. -a: Player A (agent.py or randy_ai.py, leave blank to play as player A yourself)
  4. -b: Player B (agent.py or randy_ai.py, leave blank to play as player B yourself)
  5. -c: Enable caching (speeds up minimax/alpha-beta algorithm over time)
  6. -l: depth limit for minimax/alpha-beta search tree
  7. -t: type of agent for agent.py; 0 (minimax), 1 (alpha-beta)

Mancala game gui and set up provided by course CSC384 (Introduction to AI) at UTM.
