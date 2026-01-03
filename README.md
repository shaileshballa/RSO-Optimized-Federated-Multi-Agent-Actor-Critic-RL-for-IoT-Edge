# 🧠 RSO-Optimized Federated Multi-Agent Actor-Critic RL for IoT Edge
This repository contains an implementation of a **Federated Multi-Agent Actor-Critic (FMAC) Reinforcement Learning model**, enhanced using **Rat Swarm Optimization (RSO)** for hyperparameter tuning and stabilization. The objective is to dynamically optimize **latency, energy consumption, and throughput** across IoT edge devices during real-time computation and task scheduling.

---

## 🚀 Project Motivation
Edge-IoT systems face major challenges such as:
- High latency due to offloading and bandwidth fluctuation
- Increased energy consumption on low-capacity edge devices
- Poor efficiency when devices run independent models without coordination

💡 To address this, we build:
✔ Multi-agent RL for adaptive decision-making  
✔ Federated training to share learning across devices  
✔ RSO algorithm to tune hyper-parameters (learning rate, gamma, hidden size, etc.)  
✔ Latency-aware inference logging for real-time deployment  
