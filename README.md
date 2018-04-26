# Policy_Gradients_to_beat_Pong
This is the code for the "How to Beat Pong Using Policy Gradients (LIVE)" by Siraj Raval on Youtube
I only adapted it for Python 3 (Siraj's code works on Python 2).

## Overview

This is the code for [this](https://www.youtube.com/watch?v=PDbXPBwOavc) video by Siraj Raval on Youtube. We're going to beat the game of Pong using Policy Gradients (a type of reinforcement algo). PG outperformed DeepMind's Deep Q Network, so its a worthy algo to look into. 

## Dependencies

* gym (https://gym.openai.com/docs)
* numpy 
* pickle

Install dependencies with [pip](https://pip.pypa.io/en/stable/installing/)

I also put some conda environment file (env.yml).
One can install it with:

```
conda env create -f env.yml
```

I also had to install cmake (on ubuntu 17.10).
```
sudo apt-get install cmake
```

## Usage

Run `python demo.py` and the AI will start playing the game

## Credits

Credits go to [AndrejK](https://github.com/karpathy) from whom the initial code comes from.
Credits go to [Siraj Raval](https://github.com/llSourcell) I just modified some bits of the code to make it compatible with python 3.

## After a few days training

After 6 days of training on Dell XPS 9560 15'' Nvidia GTX 1050, the trained agent could compete...  (see below: positive rewards = wins, negative rewards = losses) 
![screenshot from 2018-04-26 08-39-43](https://user-images.githubusercontent.com/684574/39289723-932b02d4-492d-11e8-8062-bc45b0cf7896.png)
