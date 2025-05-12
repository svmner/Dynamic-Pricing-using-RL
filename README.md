# 💸 Dynamic Pricing using Reinforcement Learning

This project explores the application of **Reinforcement Learning (RL)** to dynamic pricing in a simulated retail environment. The goal is to enable an agent to learn an optimal pricing policy that maximizes long-term revenue by interacting with a changing demand environment.

## 🎯 Objective

To train an RL agent (via Deep Q-Learning) that learns how to:
- Set the right price for a product dynamically
- Balance short-term profits with long-term customer behavior
- Adapt to stochastic demand responses and inventory conditions

## 🧠 Techniques Used

- **Reinforcement Learning (RL)**  
  - Q-Learning  
  - Deep Q-Network (DQN)  
- **Reward Engineering**  
  - Revenue maximization  
  - Penalizing overpricing or stockouts  
- **State Design**
  - Incorporates demand, price level, time step, and inventory
- **Exploration Strategies**
  - ε-greedy policy

## 📊 Environment Design

- **States:** Current price, demand, inventory level, and time step  
- **Actions:** Discrete price points (e.g., ₹100 to ₹150 in ₹5 increments)  
- **Rewards:** Revenue earned – penalty for unsold inventory or low demand  
- **Episodes:** Each episode simulates one pricing cycle (e.g., 30 days)
