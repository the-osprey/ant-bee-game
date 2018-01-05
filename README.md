# anthill-game
ants vs bee game from CS sixty-one A at Berkeley!

To start a text-based game, run:
python3 ants.py

To start a graphical game, run:
python3 gui.py

The game has several options, which you can view with python3 ants.py --help.

usage: ants.py [-h] [-d DIFFICULTY] [-w] [--food FOOD]

optional arguments:
  -h, --help     show this help message and exit
  -d DIFFICULTY  sets difficulty of game (test/easy/medium/hard/insane)
  -w, --water    loads a full layout with water
  --food FOOD    number of food to start with when testing




Here are the concepts, as elaborated on from the website:
A game of Ants Vs. SomeBees consists of a series of turns. In each turn, new bees may enter the ant colony. Then, new ants are placed. Finally, all insects (ants, then bees) take individual actions: bees sting ants, and ants throw leaves at bees. The game ends either when a bee reaches the ant queen (you lose), or the entire bee flotilla has been vanquished (you win).

The Colony. The colony consists of several places that are chained together. The exit of each Place leads to another Place.

Placing Ants. There are two constraints that limit ant production. Placing an ant uses up some amount of the colony's food, a different amount for each type of ant. Also, only one ant can occupy each Place.

Bees. When it is time to act, a bee either moves to the exit of its current Place if no ant blocks its path, or stings an ant that blocks its path.

Ants. Each type of ant takes a different action and requires a different amount of food to place. The two most basic ant types are the HarvesterAnt, which adds one food to the colony during each turn, and the ThrowerAnt, which throws a leaf at a bee each turn.

