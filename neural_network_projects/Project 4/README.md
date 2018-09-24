# Assignment 4 Description
In this assignment, you will implement a basic version of the two main algorithms in Deep Reinforcement Learning: Deep Q Learning (DQN) and Policy Gradient (PG, REINFORCE). The goals of this assignment are as follows:

- Implement feed-forward Multi Layer Perceptrons for policies.
- Implement action-sampling methods: epsilon-greedy and using stochastic policies.
- Build the loss function for both algorithms.
- Compute returns and baselines.

## Q1: DQN (50 points)
The Jupyter notebook simple_dqn-release.ipynb will walk you through implementing the DQN algorithm and training a policy to solve a GridWorld (should take under 5min). You can also use it to train a policy to play the Atari game of Pong (could take up to a few hours, but it is not considered for grading). 

## Q2: Policy Gradients (50 points)
The Jupyter notebook simple_pg-release.ipynb will walk you through implementing a simple Policy Gradient algorithm (REINFORCE) with time-dependent baseline. You will train a point-mass agent to reach a goal and can visualize training as it happens (should take under 5min).