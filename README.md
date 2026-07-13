# 🐦 Flappy Bird AI using Deep Q-Network (DQN)

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/PyTorch-Deep%20Learning-red?style=for-the-badge&logo=pytorch">
  <img src="https://img.shields.io/badge/Gymnasium-Reinforcement%20Learning-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Pygame-Game%20Development-yellow?style=for-the-badge">
</p>

---

## 📖 Project Overview

Flappy Bird AI is a Deep Reinforcement Learning project where an intelligent agent learns to play the Flappy Bird game using the **Deep Q-Network (DQN)** algorithm.

Instead of being manually programmed, the agent improves its gameplay through trial and error by interacting with the environment, receiving rewards, and continuously updating its neural network to maximize future rewards.

This project demonstrates practical implementation of Reinforcement Learning concepts including Experience Replay, Target Networks, and Epsilon-Greedy Exploration using **PyTorch** and **Gymnasium**.

---

# 🎯 Objectives

- Train an AI agent to play Flappy Bird autonomously.
- Learn optimal actions using Deep Q-Learning.
- Improve performance through Experience Replay.
- Reduce instability using a Target Network.
- Save and reload trained models for inference.

---

# ✨ Features

- 🧠 Deep Q-Network (DQN)
- 🎮 Human Play Mode
- 📚 Experience Replay Memory
- 🎯 Target Network
- 🔄 Epsilon-Greedy Exploration
- 💾 Automatic Model Saving
- 📂 Model Loading for Testing
- ⚡ Configurable Hyperparameters
- 🎮 Real-time Game Rendering
- 📊 Reward-Based Learning

---

# 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| PyTorch | Deep Learning Framework |
| Gymnasium | Reinforcement Learning Environment |
| Pygame | Game Rendering |
| NumPy | Numerical Computation |
| YAML | Hyperparameter Configuration |

---

# 🧠 Deep Q-Network Workflow

```
Environment
      │
      ▼
Current State
      │
      ▼
Neural Network (DQN)
      │
      ▼
Choose Action
      │
      ▼
Game Environment
      │
      ▼
Reward + Next State
      │
      ▼
Experience Replay
      │
      ▼
Train Neural Network
```

---

# 📂 Project Structure

```
Flappy_Bird/
│── agent.py
│── dqn.py
│── experience_replay.py
│── flappy_bird_game.py
│── parameters.yaml
│── requirements.txt
│── README.md
│── .gitignore
└── screenshots/
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/Pranita-kolte/Flappy-Bird-AIML-project-.git
```

```
cd Flappy-Bird-AIML-project-
```

## Create Virtual Environment

```bash
python -m venv .venv
```

Windows

```bash
.venv\Scripts\activate
```

Linux/Mac

```bash
source .venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🚀 Running the Project

## Train the AI Agent

```bash
python agent.py
```

The training process will:

- Initialize the environment
- Train using Deep Q-Learning
- Store experiences
- Update the neural network
- Save the trained model

---

## Play Flappy Bird Manually

```bash
python flappy_bird_game.py
```

Controls

| Key | Action |
|------|--------|
| Space | Flap |
| Close Window | Exit |

---

# 🧠 Reinforcement Learning Concepts Used

## Deep Q-Network (DQN)

Approximates the Q-value function using a neural network instead of a Q-table.

---

## Experience Replay

Stores previous experiences and samples random batches for training to improve learning stability.

---

## Target Network

Uses a separate target network that is periodically updated to stabilize Q-value predictions.

---

## Epsilon-Greedy Strategy

Balances exploration and exploitation by selecting random actions initially and gradually relying on learned policies.

---

# ⚙️ Hyperparameters

Configured in:

```
parameters.yaml
```

Examples include:

- Learning Rate
- Discount Factor (Gamma)
- Replay Memory Size
- Batch Size
- Epsilon
- Target Network Update Frequency

---

# 📈 Training Process

1. Observe current state.
2. Predict Q-values using the DQN.
3. Select an action using Epsilon-Greedy.
4. Execute the action.
5. Receive reward and next state.
6. Store transition in replay memory.
7. Sample random experiences.
8. Train the neural network.
9. Update target network periodically.
10. Save the trained model.

---

# 📷 Screenshots

Add screenshots in:

```
screenshots/
```

Example:

```markdown
![Gameplay](screenshots/gameplay.png)
```

---

# 📊 Future Improvements

- Double DQN
- Dueling DQN
- Prioritized Experience Replay
- Rainbow DQN
- TensorBoard Integration
- Performance Dashboard
- Hyperparameter Optimization

---

# 🎓 Learning Outcomes

This project helped in understanding:

- Reinforcement Learning
- Deep Q-Learning
- Neural Networks
- Experience Replay
- Exploration vs Exploitation
- PyTorch Implementation
- AI Game Agents

---

# 🤝 Contribution

Contributions are welcome!

1. Fork the repository.
2. Create a new branch.
3. Commit your changes.
4. Submit a Pull Request.

---

# 👩‍💻 Author

**Pranita Kolte**

Third-Year Information Technology Student

Interested in:

- Artificial Intelligence
- Machine Learning
- Reinforcement Learning
- Full Stack Development

GitHub:
https://github.com/Pranita-kolte

---

# ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.

It helps others discover the project and motivates further development.
