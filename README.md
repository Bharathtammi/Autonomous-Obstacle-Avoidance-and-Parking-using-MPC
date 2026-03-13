# 🚗 Autonomous Obstacle Avoidance and Parking using Model Predictive Control (MPC)

This project implements an autonomous driving system focused on obstacle avoidance and automated parking using Model Predictive Control (MPC). This project demonstrates two autonomous driving applications — **Obstacle Avoidance** and **Parking** — using **Model Predictive Control (MPC)** in Python. It includes a custom 2D simulation environment for visualizing the vehicle's motion. The system is designed to make real-time decisions based on the vehicle's current state, surrounding environment, and predefined goals.

https://github.com/user-attachments/assets/49b9a4d3-4122-444b-a8a5-2c1635cf6748



https://github.com/user-attachments/assets/bebcd3cf-b0c5-4c75-83f4-c48c6c4a316a

## 🗺️ Project Structure

| File Name | Description |
|---|---|
| `sim2d.py` | Simulation environment and visualization engine |
| `mpc_obstacle_avoidance.py` | Implements MPC for autonomous obstacle avoidance |
| `mpc_parking.py` | Implements MPC for autonomous parallel parking |

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/Bharathtammi/Autonomous-Obstacle-Avoidance-and-Parking-using-MPC.git
cd Autonomous-Obstacle-Avoidance-and-Parking-using-MPC
```

### 2. Install Dependencies

```bash
pip install numpy scipy matplotlib casadi
```

### 3. Run Obstacle Avoidance

```bash
python mpc_obstacle_avoidance.py
```

### 4. Run Parking

```bash
python mpc_parking.py
```
