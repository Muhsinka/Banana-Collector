# Enviroment

For this project, I will train an agent to navigate (and collect bananas!) in a large, square world.

![banana](https://user-images.githubusercontent.com/43606874/50734578-31458000-11b2-11e9-8cbc-fcdd84d17277.gif)

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around the agent's forward direction. Given this information, the agent has to learn how to best select actions. Four discrete actions are available, corresponding to:

0 - move forward.

1 - move backward.

2 - turn left.

3 - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

# Files

The project includes 6 files:

Navigation.ipynb:learning from vector observations with fully functional code, all code cells executed and displaying output.

Navigation_pixels.ipynb: Learning from visual observations partially functinal code needs further improvements 

dqn_agent.py:The Agent class

model.py:The DQN models checkpoint.pth:saved trained model to use

README.md:Description of the project.

Report.md:Description of the model and results

# Required Modules

This project requires Python 3.5 or higher, the Banana Collector Environment (follow the instructions to download here) and the following Python libraries installed:

NumPy

Torch

UnityAgents

OpenAI Gym
