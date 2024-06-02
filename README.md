# Reinforcement Learning Project

This project simulates user interactions to predict posture changes based on window position changes on the screen using reinforcement learning (RL) algorithms.

## Environment Setup

### ExperimentEnv Class

- **Grid Representation:** A 6x6 grid (36 positions) representing the screen.
- **User Position:** The user starts at a specific position and can move within the grid.
- **State and Action Spaces:** Defines the possible states and actions for the user.

## Agents

### Expected SARSA Agent

- **Purpose:** Effective in stochastic environments.
- **Key Features:** Balances exploration and exploitation using an epsilon-greedy strategy and updates Q-values based on expected future rewards.

### Double Q-Learning Agent

- **Purpose:** Reduces overestimation bias in stochastic environments.
- **Key Features:** Maintains two Q-tables to decouple action selection from evaluation, providing more stable learning.
