# Udacity-Continuous-control

![image-20230620225457569](png\image-20230620225457569.png)

## Project details

This project is part of the Udacity Deep Reinforcement Learning nanodegree.
The goal of this project is to solve the Reacher environment. In this environment, a double-jointed arm can move to target locations. A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of your agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

The environment is considered solved if a reward of +100 is obtain for 30 consecutive episodes.

Two methods are used and compared:

- an actor-critic algorithm, the Deep Deterministic Policy Gradients (DDPG) algorithm
- an actor-critic algorithm, the Proximal Policy Optimization (PPO) algorithm

## Getting started

1. `conda env create -n drlnd --file drlnd.yml`,  Install the necessary environment.
2. `conda activate drlnd`
3. The first deployment requires a unity environment,  find directory and unzip the `Reacher_Windows_x86_64.zip` to the current directory
4. `jupyter notebook Continuous_Control.ipynb`
5. The training can be run directly in the notebook