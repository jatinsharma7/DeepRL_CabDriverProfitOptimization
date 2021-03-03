# Deep Reinforement Learning - Cab Driver Profit Optimization

## Problem Statement
SuperCabs, a leading app-based cab provider is looking for retention of good cab drivers in a large Indian metro city. In this highly competitive travel industry, retention of good cab drivers is a crucial business driver.

Most drivers get a healthy number of ride requests from customers throughout the day. But with the recent hikes in electricity prices (all cabs are electric), many drivers complain that although their revenues are gradually increasing, their profits are almost flat. Thus, it is important that drivers choose the 'right' rides, i.e. choose the rides which are likely to maximise the total profit earned by the driver that day.

There are some basic rules governing the ride-allocation system. If the cab is already in use, then the driver won’t get any requests. Otherwise, he may get multiple request(s). He can either decide to take any one of these requests or can go ‘offline’, i.e., not accept any request at all.

## Goal
Cab drivers are incentivised by a healthy growth in income. The **goal of this project is to build an RL-based algorithm which can help cab drivers maximise their profits by improving their decision-making process on the field**.

1. **Create the environment**
2. **Build an agent that learns to pick the best request using DQN.**
3. **Convergence**

## Solution
This problem can be solved using a sound RL-based system for assisting cab drivers that can potentially retain and attract new cab drivers.Taking long-term profit as the goal, we propose a method based on reinforcement learning to optimize taxi driving strategies for profit maximization. This optimization problem is formulated as a Markov Decision Process.

We will create the environment and an RL agent that learns to choose the best request. We also need to train an agent using vanilla Deep Q-learning (DQN) 
![Architecture](https://github.com/jatinsharma7/DeepRL_CabDriverProfitOptimization/blob/main/image.png)
