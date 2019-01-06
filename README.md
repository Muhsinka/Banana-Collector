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

Navigation.ipynb: Learning from vector observations with fully functional code, all code cells executed and displaying output.

Navigation_pixels.ipynb: Learning from visual observations partially functinal code needs further improvements. 

dqn_agent.py: Definition of the Agent

model.py: The Qnetwork model.

checkpoint.pth:saved trained model to use

README.md: Description of the project.

Report.md: Description of the model and results

# Required Modules

This project requires Python 3.5 or higher, following Python libraries are required:

NumPy

Torch

UnityAgents

OpenAI Gym

# Install Guide For Win-64bit

Create new conda enviroment and activate enviroment

Open Anaconda promt and type following:
```
conda create -n ml-agents python=3.6
```
```
activate ml-agents
```
Install tensorflow
```
pip install tensorflow==1.7.1
```
Download ML-Agents Toolkit Github Repository
```
git clone https://github.com/Unity-Technologies/ml-agents.git
```
Type in the Anaconda Prompt within ml-agents subdirectory
```
cd C:\Downloads\ml-agents\ml-agents
```
To complete the installation of all the required Python packages to run the ML-Agents toolkit type in the following.
```
pip install -e .
```
# How to get started

Step 1:Install unity banana enviroment and place it in ml-agents file that we have downloaded

Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)

Step 2:Open Navigation.ipynb and follow the instructions
