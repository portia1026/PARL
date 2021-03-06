## Reproduce DQN with PARL
Based on PARL, the DQN model of deep reinforcement learning is reproduced, and the same level of indicators of the paper is reproduced in the classic Atari game.

+ DQN in
[Human-level Control Through Deep Reinforcement Learning](http://www.nature.com/nature/journal/v518/n7540/full/nature14236.html)

### Atari games introduction
Please see [here](https://gym.openai.com/envs/#atari) to know more about Atari game.

### Benchmark result
- Pong
<img src=".benchmark/DQN_Pong.png"/>  

## How to use
### Dependencies:
+ python2.7 or python3.5+
+ [paddlepaddle>=1.0.0](https://github.com/PaddlePaddle/Paddle)
+ [parl](https://github.com/PaddlePaddle/PARL)
+ gym
+ tqdm
+ opencv-python
+ atari_py
+ [ale_python_interface](https://github.com/mgbellemare/Arcade-Learning-Environment)


### Start Training:
```
# To train a model for Pong game
python train.py --rom ./rom_files/pong.bin
```
> To train more games, you can install more rom files from [here](https://github.com/openai/atari-py/tree/master/atari_py/atari_roms).
