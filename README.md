# Deep Reinforcement Learning
## Project: Train AI to play Snake
*UPDATE:*

This project has been recently updated and improved:
- It is now possible to optimize the Deep RL approach using Bayesian Optimization.
- The code of Deep Reinforcement Learning was ported from Keras/TF to Pytorch. To see the old version of the code in Keras/TF 

## Introduction
The goal of this project is to develop an AI Bot able to learn how to play the popular game Snake from scratch. In order to do it, I implemented a Deep Reinforcement Learning algorithm. This approach consists in giving the system parameters related to its state, and a positive or negative reward based on its actions. No rules about the game are given, and initially the Bot has no information on what it needs to do. The goal for the system is to figure it out and elaborate a strategy to maximize the score - or the reward. \
We are going to see how a Deep Q-Learning algorithm learns how to play Snake, scoring up to 50 points and showing a solid strategy after only 5 minutes of training. \
Additionally, it is possible to run the Bayesian Optimization method to find the optimal parameters of the Deep neural network, as well as some parameters of the Deep RL approach.
