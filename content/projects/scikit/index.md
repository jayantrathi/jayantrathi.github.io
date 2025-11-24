---
title: Reinforcement Learning Algorithms for Atari & Custom Game Environments 
date: 2023-10-26
links:

tags:
  - Northeastern
  - HugoBlox
  - Markdown
---

Technologies: PyTorch, Gymnasium, DQN/PPO/DDPG, frame stacking, CNN encoders, Replay Buffers

A series of advanced RL models trained from pixels and low-dimensional states:

•	Built full RL training pipelines, including:
CNN encoders, frame-stacking, NoisyNets, target networks, multi-step returns, and epsilon-schedule strategies.

•	Implemented algorithms from scratch:

•	DQN, Double-DQN, Dueling-DQN

•	PPO with clipped objectives

•	Deterministic policy gradients (DDPG)

•	Designed visual preprocessing (grayscale, downsampling, cropping) to match Atari RL conventions.

•	Tuned training stability through reward scaling, gradient clipping, and replay-buffer priority sampling.

•	Evaluated agents with return curves, variance metrics, and generalization tests across seeds.

• Then moved onto a childhood favourite called CubeField to test a RL agents capabilities using multiple RL techniques to see which fared best as showcased

<!--more-->
