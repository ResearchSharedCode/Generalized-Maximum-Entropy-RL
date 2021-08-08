# Generalized-Maximum-Entropy-RL
This is the implementation code for the Paper "Generalized Maximum Entropy Reinforcement Learning via Reward Shaping"."

## Env set up (create a virtual env in Anaconda)

* $conda create -n env_name python=3.6$
* $conda install pytorch torchvision torchaudio cudatoolkit=10.2 -c pytorch$
* $pip install gym$
* $pip install mujoco_py==2.0.2.8$
* $conda install pandas$
* $pip install seaborn$

Make sure to add license txt to .mujoco folder

## Experiment
```
python main.py --env-name Humanoid-v2 --alpha 0.1
```



## The code is modified based on the SAC implementation 
https://github.com/pranz24/pytorch-soft-actor-critic
