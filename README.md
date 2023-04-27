# NEAT-Asteroid-Dodger
Genetic algorithm used to teach AI with NEAT to play Asteroid Dodger game on python.
I taught an AI to play the asteroid dodger game in python by using a NEAT module and Pygame.
The player ship and asteroid images are in the folder do not delete them.
Install both modules using - (pip install NEAT) and (pip install Pygame)
NEAT - "Neural Evolution through Augmented Topologies", if you dont know what neural networks are then i advise you to go research them before getting in to this.
A config file is attached which can be edited to change how the algorithm runs.
I used a population of 10 for my program, 12 input nodes (takes in the distance between the first 5 obstacles that are seen and the ship and also the X and Y coordiantes of the ship) and 3 outputs (left, right or still)
I decided to use a sigmoid as my activation function but a RelU also works well in this.
The timer for obstacles spawning can also be changed i made it so that its every 1 second.
