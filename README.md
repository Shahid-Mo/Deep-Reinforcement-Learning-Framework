# Deep Reinforcement Learning Framework

This project implements Deep Q-Network (DQN) and Double Deep Q-Network (DDQN) algorithms for reinforcement learning in various environments. It is designed to be modular, allowing for easy experimentation with different network architectures, configurations, and environments.

## Project Structure

- `config.py`: Contains the configuration class `Config` that holds hyperparameters and settings.
- `model.py`: Defines the neural network architecture for the DQN and DDQN.
- `replay_memory.py`: Implements the replay memory, a crucial component for efficient learning.
- `dqn.py`: The main script for training an agent using the DQN algorithm.
- `ddqn.py`: The main script for training an agent using the DDQN algorithm, an improvement over DQN that aims to reduce overestimation of Q-values.

## Installation

Ensure you have Python 3.6 or newer installed. Clone this repository and install the required Python packages:

```bash
git clone https://github.com/yourusername/deep-reinforcement-learning-framework.git
cd deep-reinforcement-learning-framework
pip install -r requirements.txt

