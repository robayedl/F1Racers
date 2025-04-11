# F1Racers

# 🏎️ Car Racing Agent using Reinforcement Learning

An autonomous car racing agent trained using reinforcement learning algorithms (DQN, PPO, SAC) in the Gymnasium CarRacing-v3 environment. The project evaluates model performance based on rewards, convergence, and control efficiency for autonomous driving.

---

## 📁 Files Included

- `CarRacingDQN.ipynb` – DQN implementation with discretized action space  
- `CarRacingPPO.ipynb` – PPO implementation using continuous actions  
- `CarRacingSAC.ipynb` – SAC implementation for exploration-based control  
- `Project Report.pdf` – Full project report  

---

## 📌 Project Overview

This project explores reinforcement learning for autonomous vehicle control in a simulated environment. Three different RL algorithms—DQN, PPO, and SAC—are evaluated for their ability to drive a car around a racetrack using Gymnasium's `CarRacing-v3`.

---

## 🧠 Algorithms Compared

| Algorithm | Action Space | Type         | Performance Summary              |
|-----------|--------------|--------------|----------------------------------|
| **DQN**   | Discrete     | Off-policy   | ✅ Best performance, fastest convergence |
| **PPO**   | Continuous   | On-policy    | ⚠️ Moderate performance, stable but slower |
| **SAC**   | Continuous   | Off-policy   | ❌ Did not converge in training period |

---


## 👥 Authors

- Robayed Ashraf | robayedashraf@gmail.com
- Chong Fai Wong | jason1999689@gmail.com
- Asim Santos Poudel | asimsantospoudel@gmail.com
