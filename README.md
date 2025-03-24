# Tabular Reinforcement Learning – Dynamic Programming & Model-Free Methods

## About
This repository contains our work for the Tabular Reinforcement Learning assignment. We implemented:
- **Dynamic Programming:** Q-value iteration using a complete model of the Stochastic Windy Gridworld.
- **Model-Free Methods:** Q-learning, SARSA, n-step Q-learning, and Monte Carlo methods.
All experiments are conducted in the Stochastic Windy Gridworld environment. The project report (RL_A1.pdf) details our methodology, experimental setup, and analysis.

## Repository Structure
- **SARSA.py:** Implementation of the SARSA algorithm.
- **Agent.py:** Base agent class with exploration methods.
- **DynamicProgramming.py:** Q-value iteration implementation for Dynamic Programming.
- **Environment.py:** The Stochastic Windy Gridworld environment.
- **Experiment.py:** Script to run various RL experiments.
- **Helper.py:** Helper functions for plotting and smoothing.
- **MonteCarlo.py:** Monte Carlo reinforcement learning algorithm.
- **Nstep.py:** n-step Q-learning algorithm.
- **Q_learning.py:** Q-learning algorithm implementation.
- **RL_A1.pdf:** The full project report.
- **README.md:** This file, providing an overview and instructions.

## How to Run
1. **Install Dependencies:**  
   Ensure you have Python 3.8+ installed. Then install required packages (e.g., numpy, matplotlib, torch, etc.):
   ```bash
   pip install -r requirements.txt
