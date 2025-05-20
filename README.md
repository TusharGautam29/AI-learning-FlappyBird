# NEAT-based AI Trainer for Flappy Bird 🧠🕊️

[![View on GitHub](https://img.shields.io/badge/View%20on-GitHub-000?logo=github&style=flat-square)](https://github.com/TusharGautam29/AI-learning-FlappyBird)

https://github.com/user-attachments/assets/b610112e-092b-4b90-b777-a9b48d251e8d

An AI that learns to play Flappy Bird using NEAT (NeuroEvolution of Augmenting Topologies). It evolves neural networks across generations to optimize performance through genetic algorithms.

## 🚀 Features

- **Evolutionary AI**: Neural networks evolve over 50+ generations using a fitness function based on survival time and score.
- **Neural Inputs**: Each bird receives its own input vector: vertical position and pipe distances.
- **Jump Prediction**: Network output determines if the bird should jump or stay.
- **Pixel-Perfect Collisions**: Uses Pygame masks to avoid sloppy hitboxes.
- **Real-Time Visualization**: Shows alive birds, current generation, score, and AI decisions.
- **Configurable Parameters**: Adjust pipe spacing, scroll speed, gravity, and NEAT settings.

## 🧠 How It Works

Each bird is controlled by a unique neural network. Using the NEAT algorithm:
- The population evolves by selecting top performers.
- Mutation and crossover generate the next generation.
- Fitness is scored by how long and how well a bird survives.

## 🛠️ Tech Stack

- Python 3
- [Pygame](https://www.pygame.org/)
- [NEAT-Python](https://github.com/CodeReclaimers/neat-python)

## 🧪 Installation
If you have Visual Studio (Not Visual Studio Code) just open the .sln file and run the local Windows Debugger(or Press f5), if not then follow the steps below
- keep in mind you need to have the prerequisites installed, which are python 3, pygame and neat-python

```bash
git clone https://github.com/TusharGautam29/AI-learning-FlappyBird.git
cd AI-learning-FlappyBird
cd aiflappybird
python flappy_bird_neat.py
