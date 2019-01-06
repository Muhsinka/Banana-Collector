# Project Report

## Model Architecture
The local neural-network have the following structure defined in file model.py:

A fully connected layer with 37 inputs and 128 outputs using ReLU activations

A fully connected layer with 128 inputs and 256 outputs using ReLU activations

A fully connected layer with 256 inputs and 4 outputs

# Parameters used in DQN algorithm

BUFFER_SIZE = int(1e5) # replay buffer size. 

BATCH_SIZE = 64 # minibatch size

GAMMA = 0.99 # discount factor

TAU = 1e-3 # for soft update of target parameters

LR = 5e-4 # learning rate 

UPDATE_EVERY = 4 # how often to update the network

# Results

![indir](https://user-images.githubusercontent.com/43606874/50734667-68686100-11b3-11e9-889c-b5f558cf8073.png)

Episode 100	Average Score: 0.75

Episode 200	Average Score: 3.92

Episode 300	Average Score: 7.34

Episode 400	Average Score: 10.74

Episode 500	Average Score: 12.53

Episode 516	Average Score: 13.04

Environment solved in 416 episodes!	Average Score: 13.04

# Possible Future Improvements

This project used the basic DQN algorithm. For further improvements following methods can be applied.

prioritized experience replay

double DQN

dueling DQN
