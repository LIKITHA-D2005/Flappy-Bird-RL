# 🐦 Flappy Bird Smart Agent: Deep Q-Learning Agent

## 📌 Overview
This project implements a **Deep Q-Learning (DQN)** agent to play Flappy Bird using Reinforcement Learning.  
The agent learns to navigate through pipes by maximizing rewards through trial-and-error interactions, improving its performance over time.

---

## ⚙️ Core Components
- **Deep Q-Network (DQN)**  
  - Built with PyTorch  
  - Architecture: Input → Hidden (256, ReLU) → Output (Q-values)  
  - Predicts optimal action (Flap / No Flap)

- **Experience Replay**  
  - Stores past experiences `(state, action, reward, next_state, done)`  
  - Uses random mini-batch sampling for stable training  

- **Training Strategy**  
  - ε-greedy exploration  
  - Policy Network + Target Network  
  - Periodic target network updates  

---

## ✨ Features
- Deep Reinforcement Learning with DQN  
- Experience Replay & Target Network  
- Configurable hyperparameters (`parameters.yaml`)  
- Model saving & training logs  
- CPU / GPU / MPS support  

---

## 📊 Results & Insights
- Learns optimal jump timing over episodes  
- Improves survival time with training  
- Demonstrates exploration vs exploitation trade-off  
- Stable learning achieved using replay buffer and target network  

---

## 👩‍💻 Author
**Likitha D**

---

## ⭐ Support
If you found this project useful, consider giving it a ⭐ on GitHub!
