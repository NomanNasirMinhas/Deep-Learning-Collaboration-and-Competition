# Deep-Learning-Collaboration-and-Competition
In this environment, two agents control rackets to bounce a ball over a net. If an agent hits the ball over the net, it receives a reward of +0.1. If an agent lets a ball hit the ground or hits the ball out of bounds, it receives a reward of -0.01. Thus, the goal of each agent is to keep the ball in play. The observation space consists of 8 variables corresponding to the position and velocity of the ball and racket. Each agent receives its own, local observation. Two continuous actions are available, corresponding to movement toward (or away from) the net, and jumping.

# Task and Goal
The task is episodic, and in order to solve the environment, your agents must get an average score of +0.5 (over 100 consecutive episodes, after taking the maximum over both agents). Specifically,

- After each episode, we add up the rewards that each agent received (without discounting), to get a score for each agent. This yields 2 (potentially different) scores. We then take the maximum of these 2 scores.
- This yields a single score for each episode.
**The environment is considered solved, when the average (over 100 episodes) of those scores is at least +0.5**.

# Dependencies
We will require following packages to run this project. We can install each package by following instructions below respective package.
1. **deep-reinforcement-learning  (DRLND)**
- git clone https://github.com/udacity/deep-reinforcement-learning.git
- cd deep-reinforcement-learning/python
- pip install 

3. **Unity environment _Tennis_**
We can download unity environment from below link and extract them into our project directory
- Windows (64-bit), [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)    
- Windows (32-bit), [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)   

# How to train agent
Run each cell of the notebook sequentially to train the agent.

# Weights of the trained agent
The **weights** of the trained agent are saved into the files **checkpoint_actor_0.pth,  checkpoint_actor_1.pth,  checkpoint_critic_0.pth, checkpoint_critic_1.pth** into directory **'dir_chk_5000d_episodes'**.

# Acknowledgements
This code has been improved with help from code provided by Udacity and from Udacity Knowledge forum discussions.