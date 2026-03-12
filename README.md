# Reinforcement Learning Trading Framework

This project implements a **Deep Reinforcement Learning framework** for financial trading using a **Deep Q-Network (DQN)** built with **PyTorch** and a custom **OpenAI Gym environment**.

The framework models trading as a **Markov Decision Process (MDP)** where an agent learns optimal trading policies by interacting with a simulated market environment.

## Framework Overview

The reinforcement learning system consists of the following components:

* **Environment** – A custom OpenAI Gym environment that simulates trading dynamics.
* **Agent** – A Deep Q-Network (DQN) that learns trading policies from market data.
* **State Space** – A feature representation combining technical indicators and macroeconomic variables.
* **Action Space** – Discrete actions representing trading decisions (buy, hold, sell).
* **Reward Function** – A Sharpe ratio–based reward designed to encourage risk-adjusted performance.

The agent is trained on historical financial data to learn policies that maximize long-term reward through sequential decision-making.

## My Contribution

I was responsible for the **full development of the reinforcement learning framework**, including:

* Designing and implementing the **DQN agent in PyTorch**
* Building the **custom OpenAI Gym trading environment**
* Defining the **state space, action space, and reward function**
* Training and evaluating the agent on historical financial data
* Implementing **Explainable AI (XAI)** methods to interpret the model’s decisions

## Tech Stack

* Python
* PyTorch
* OpenAI Gym
* NumPy / Pandas
* Matplotlib

