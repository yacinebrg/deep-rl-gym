# deep-rl-gym
Implementation of Deep Q-Network (DQN) and Proximal Policy Optimization (PPO) on Gym environments
# Deep Reinforcement Learning with Gymnasium

This project demonstrates two reinforcement learning algorithms applied to classic Gym environments:

- **DQN** (Deep Q-Network) on *CartPole-v1* (implemented from scratch in PyTorch)  
- **PPO** (Proximal Policy Optimization) on *LunarLander-v2* (trained with Stable-Baselines3)  

---

## 📂 Project Structure

- `dqn_cartpole.py` → DQN implementation from scratch in PyTorch  
- `ppo_lunarlander.py` → PPO training using stable-baselines3  
- `requirements.txt` → dependencies  
- `README.md` → project description  

---

## 🎯 Results
- The **DQN agent** learns to balance the CartPole after training.  
- The **PPO agent** successfully lands the LunarLander.  

*(You can add GIFs or videos here for better visualization of the trained agents — e.g., using `gymnasium.utils.save_video`.)*  

---

## ⚙️ Installation

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
pip install -r requirements.txt
