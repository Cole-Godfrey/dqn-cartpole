# DQN Agent for CartPole-v1

Minimal deep reinforcement learning example that trains a DQN agent on the
Gymnasium `CartPole-v1` environment using TensorFlow/Keras and `keras-rl2`.

## Files

- `dqn-cartpole.ipynb` - notebook for creating, training, saving, and reloading
  the DQN agent.
- `dqn_cart_pole_v1.weights.h5` - saved model weights produced by the notebook.

## Setup

Install the main Python dependencies:

```bash
pip install gymnasium tensorflow keras-rl2 numpy pygame jupyter
```

Then open the notebook:

```bash
jupyter notebook dqn-cartpole.ipynb
```

## Notes

`keras-rl2` may need local compatibility patches with newer TensorFlow/Keras and
Gymnasium versions. See the compatibility note inside the notebook before
running the training cells.
