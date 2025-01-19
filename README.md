# Predictive Maintenance Optimization using Reinforcement Learning and RUL Estimation

## Description
This project presents an innovative approach to optimize predictive maintenance by combining Remaining Useful Life (**RUL**) estimation with **Reinforcement Learning (RL)**. Leveraging the NASA CMAPSS dataset, the objective is to dynamically adapt maintenance strategies, reduce costs, and minimize unexpected failures. The proposed solution utilizes the **Double Deep Q-Network (D3QN)** algorithm enhanced with **Prioritized Experience Replay (PER)** for efficient decision-making in complex environments.

---

## Features
- Accurate **RUL estimation** based on sensor data.
- Custom environment simulation for equipment degradation.
- Implementation of **D3QN** with Prioritized Experience Replay (PER).
- Dynamic optimization of maintenance strategies.
- Visualization of training metrics, including cumulative rewards, critical failures, and total costs.

---

## Technologies Used
- **Languages and Libraries**:
  - Python 3.x
  - TensorFlow / Keras
  - NumPy, Pandas, Matplotlib
  - Gym (for environment simulation)
- **Dataset**:
  - NASA CMAPSS dataset

---
## Installation

### 1. Prerequisites
Ensure the following are installed:
- Python 3.x
- Package manager pip

### 2. Clone the Repository and Install Dependencies
```bash
git clone https://github.com/ELFAKIRChaimae/predicitve-maintenance-optimization.git
cd predicitve-maintenance-optimization
pip install -r requirements.txt
