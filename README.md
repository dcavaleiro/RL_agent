# 🤖 RL_agent: Reinforcement Learning Agent for Continuous Control

This project implements a Reinforcement Learning (RL) agent designed to solve continuous control tasks. Leveraging deep learning techniques, the agent learns optimal policies through interaction with dynamic environments. The goal of this RL agent is to be capable of solving an environment for decision-making in Autonomous Driving.

## 📁 Repository Contents

- `RL_Project.ipynb`: Jupyter Notebook containing the implementation of the RL agent, including environment setup, model architecture, training loop, and evaluation metrics.
- `README.md`: Project documentation.

## 🛠️ Technologies & Tools

- **Programming Language**: Python
- **Libraries**:
  - Data Handling: `pandas`, `numpy`
  - Reinforcement Learning: `gym`, `stable-baselines3`
  - Deep Learning: `PyTorch`
  - Visualization: `matplotlib`, `seaborn`
- **Environment**: Jupyter Notebook

## 🎯 Project Overview

The objective of this project is to develop an RL agent capable of performing in continuous action spaces. The agent is trained using policy-based methods to maximize cumulative rewards in simulated environments.

### Key Features

- **Environment Interaction**: Utilizes OpenAI Gym environments for simulation.
- **Policy Learning**: Implements algorithms like Proximal Policy Optimization (PPO) for stable learning.
- **Performance Evaluation**: Includes tools for monitoring training progress and evaluating agent performance.

### Solutions

* **Environment Observation Type:**
  - Kinematics;
  - OccupancyGrid.

* **Agent Action Type:**
  - DiscreteMetaAction;
  - ContinuousAction.

* **Algorithm Used:**
  - Random;
  - Deep Q-network (DQN);
  - Q-learning;
  - SARSA.

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.8 or higher
- Jupyter Notebook
- [PyTorch](https://pytorch.org/get-started/locally/)
- [Stable Baselines3](https://stable-baselines3.readthedocs.io/en/master/)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/dcavaleiro/RL_agent.git
   cd RL_agent
