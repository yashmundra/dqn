# Deep Q-learning
Basic implementation of the deep Q-networks applied to single atari game breakout 

I use keras, OpenAI gym, numpy.

![gif](demo.gif)


## Installation

Type the following command to install OpenAI Gym Atari environment.

`$ pip3 install opencv-python gym gym[atari]`

## How-to

Please don't revise `test.py`, `environment.py`, `agent_dir/agent.py`

training DQN:

- `$ python3 main.py --train_dqn`

testing DQN:

- `$ python3 test.py --test_dqn`
