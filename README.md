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

Changelog0.3 : FSM implementation done. You'll have 2 enemies to beat. The first one statrs following you mindlessly when you're close to it and you die if it touches you, but it can be beaten pretty easily. The second one is a bit advanced and it blocks attacks when you're close to it...but allows attacks when you're close enough, should be a little difficult to beat as it is pretty quick.  

Gen views on FSM : Not really an AI. Just a smart manner of saving yourselves from writing too many if-else ladders. Still pretty boring as some if-else cannot be avoided looking forward to MCST, after cleaning the FSM code a little.
