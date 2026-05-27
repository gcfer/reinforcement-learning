# Reinforcement Learning

TensorFlow 2 notebooks implementing classic reinforcement-learning algorithms.
The examples are written for Google Colab and use the CartPole environment from
OpenAI Gym.

## Notebooks

| File | Algorithm | Description |
| --- | --- | --- |
| `RL_DQN_TF2.ipynb` | DQN | Deep Q-Network with memory and replay. |
| `RL_REINFORCE_TF2.ipynb` | REINFORCE | Policy-gradient method. |
| `RL_A2C_2N_TF2.ipynb` | A2C | Actor-critic method with separate actor and critic networks. |
| `RL_A2C_2N_CL2_TF2.ipynb` | A2C | Actor-critic variant using a custom loss. |
| `RL_PPO_TF2.ipynb` | PPO | Proximal Policy Optimization. |

Each notebook follows roughly the same structure:

- overview of the algorithm
- setup for running Gym in a remote notebook
- TensorFlow/Keras implementation
- training loop
- final test episode with rendered output

## How to run

Open a notebook in Google Colab and run the cells from top to bottom. The
notebooks install the extra packages needed for rendering Gym environments in
Colab, including `gym`, `pyvirtualdisplay`, `xvfb`, and `ffmpeg`.

If a Colab runtime uses newer Gym or TensorFlow versions, minor compatibility
edits may be needed.
