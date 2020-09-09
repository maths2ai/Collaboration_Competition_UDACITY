# Collaboration_Competition_DRL_Udacity

In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play.

The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). Specifically,

After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores. This yields a single score for each episode. The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5.

Installation

Install deep reinforcement learning repository

Clone deep reinforcement learning repository
Fallow the instructions to install necessary dependencies
Download the Unity Environment

Download environment for your system into this repository root
Linux: click here

Mac OSX: click here

Windows (32-bit): click here

Windows (64-bit): click here

Headless: click here

Unzip (or decompress) the archive
Run the project

Start the jupyter server
Open the Tennis.ipynb notebook
Change the kernel to drlnd 
Run cells from top to bottom