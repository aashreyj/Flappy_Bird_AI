# Flappy Bird AI
This AI is using NEAT(Neuro-Evolution using Augmented Topologies) algorithm. It is intelligent enough, and learns to play the game of Flappy Bird on its own.

# Basic logic behind the training of the AI:

1. As the AI goes though it's training , the first generation is populated with 'bots' having random weights and biases to a total of 50 in number.

2. As this generation progresses, and after all bot have "died" in the game , the bot with the best fitness is used to produce another 50 bots for the next generation.

3. This process repeats till it is clear that the AI has learnt how to play the game and can continue indefinitely.

# Real World applications:

Though this is a simple AI to play a fairly simple game of flappy bird, it can be complicated and made to be trained on a humaniod robot and teach it to walk and run, and thereby help humans reach places where it is phisically life threatening for humans to go.

# Requirements :
The game can be viewed by running the flappy_bird.py file.
Before running that file, do install the modules mentioned in the requirements.txt file via pip install or run the following command in your terminal or CMD prompt:

pip install -r requirements.txt
