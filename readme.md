# NEAT AI Flappy Bird

# Instructions

- cmd/pip:
  - pip install pygame
  - pip install neat-python

# NEAT (NeuroEvolution of Augmenting Topologies)

**Documentation:**

- https://neat-python.readthedocs.io/en/latest/neat_overview.html

### NEAT method

- **Input:** BirdY, Top pipe, Bottom pipe
- **Output neuron:** Jump or not to jump
- **Activation function:** TanH (-1, 1)
- **Population size:** 5 birds each generation
- **Fitness function:** X distance (further is better)
- **Max generations:** Program cancels after 30 gens with no perfect bird
