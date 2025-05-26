# kungfu-a3c-master
Train an AI agent to master Kung Fu using the Asynchronous Advantage Actor-Critic (A3C) algorithm in the classic Atari game using PyTorch and Gymnasium.
## 🚀 Overview

This project implements the A3C reinforcement learning algorithm to train an AI agent to play the Atari game **Kung-Fu Master**. Multiple worker agents asynchronously interact with their own environments and update a shared global network to learn faster and more robustly.

---

## 📦 Features

- ✅ Asynchronous A3C training
- ✅ Shared global actor-critic model
- ✅ Support for parallel workers using `multiprocessing`
- ✅ Frame preprocessing (grayscale + resize)
- ✅ TensorBoard support for training metrics
- ✅ Easy to extend for other Atari games

---

## 🧠 A3C: Asynchronous Advantage Actor-Critic

A3C is a reinforcement learning algorithm where multiple agents (threads) run in parallel, each interacting with its own copy of the environment. Gradients from these agents are applied asynchronously to a shared global network. This encourages diverse exploration and speeds up training.

---

## 🕹 Environment

- **Game**: `KungFuMaster-v0`
- **Framework**: [Gymnasium](https://gymnasium.farama.org/)
- **ROMs**: Installed using [AutoROM](https://github.com/Farama-Foundation/AutoROM)

---
