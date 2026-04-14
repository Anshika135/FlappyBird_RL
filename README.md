# 🐦 Flappy Bird AI using Deep Q-Network (DQN)

This project implements an AI agent that learns to play Flappy Bird using Deep Reinforcement Learning (DQN). The agent improves its performance over time by interacting with the environment and maximizing rewards.

---

## 🚀 Project Overview

The goal of this project is to train an intelligent agent capable of playing Flappy Bird autonomously. The agent learns when to flap or not flap based on the current game state using a Deep Q-Network.

---

## 🎮 Environment

- Custom Flappy Bird environment (built using Pygame)
- State space includes:
  - Bird's vertical position
  - Bird's velocity
  - Distance to next pipe
  - Gap between pipes

---

## 🧠 Features

- Deep Q-Network (DQN) implementation
- Experience Replay Buffer
- Target Network for stable training
- Epsilon-Greedy exploration strategy
- Model saving and loading
- Training performance visualization

---

## 🛠️ Tech Stack

- Python
- PyTorch 
- NumPy
- Matplotlib
- Pygame

---





## 📊 Results

- The agent initially performs random actions.
- Over time, it learns optimal timing for flapping.
- Performance improves significantly after training.

## 🧠 How It Works

The DQN algorithm works as follows:

1. Observe current state
2. Choose action using epsilon-greedy policy
3. Execute action and receive reward
4. Store experience in replay memory
5. Sample random batch for training
6. Update Q-network
7. Periodically update target network

---

## 📈 Hyperparameters

| Parameter        | Value |
|----------------|------|
| Learning Rate   | 0.001 |
| Gamma           | 0.99 |
| Batch Size      | 64 |
| Replay Buffer   | 10000 |
| Epsilon Start   | 1.0 |
| Epsilon End     | 0.01 |
| Epsilon Decay   | 0.995 |

---

## 🧪 Future Improvements

- Double DQN
- Dueling DQN
- Prioritized Experience Replay
- Better state representation
- Deploy as a web application

---

## 🤝 Contributing

Feel free to fork the repository and submit pull requests.

----

## 👤 Author

Anshika Agarwal  
GitHub: https://github.com/Anshika135
