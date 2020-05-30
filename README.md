# AI-based-game
Trying to develop a game where the enemy evolves as the AI model trains.\
Changelog0.1 : Ignore the basics file, it was just me getting familiar with the environment.\
               Game file has a basic game with a MC, a blob enemy and your ability to kill it. An OOP based approach was found to be the                   best one and hence initial approach seen in basics file was discarded.\
Once a basic game env is developed am starting work on different types of AI models which I can introduce.

Changelog0.2 : Forking the possible game AIs based on(hence 4 files with 4 AI implementations of blob):
1. FSM
2. Monte Carlo Search Tree
3. Genetic/Generational NN
4. Behavioural Decision Trees

Changelog0.4 : MCTS is a pretty decent algo but seems like you've hardcoded all possible scenarios and are just trying to search through them in an efficient manner. But the algorithm is a pretty hefty one, mine is inspired by minimalistic MCTS implementation by John Harold Miles on GitHub. The TicTacToe example was an experiment to check out my implementation of MCTS and it works well. I had implemented a very shabby code for decalration of the tree nodes. Abstract Classes helped in improving the code alot. Current MCTS has a usage for playing a tic-tac-toe game. Further will implement it for the states of my game.
