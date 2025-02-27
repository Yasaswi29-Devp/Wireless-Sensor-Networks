# 🌍 Optimizing Energy Efficiency in Wireless Sensor Networks  
### **Using Multi-hop Communication & Adaptive Machine Learning-Based Clustering**  

## 📌 Project Overview  
Wireless Sensor Networks (WSNs) are widely used in **smart cities, environmental monitoring, and industrial automation**. However, their efficiency is **limited by battery life and energy consumption**. This project proposes an **energy-efficient WSN model** integrating:  
- **Multi-hop communication** using a modified **Dijkstra’s Algorithm**  
- **Adaptive clustering** through **reinforcement learning**  

By optimizing **data transmission and cluster head selection**, this approach extends network lifetime, reduces energy consumption, and improves network reliability.  

## 🔥 Key Features  
✔ **Energy-Efficient Multi-hop Routing** – Uses a **modified Dijkstra’s Algorithm** to minimize energy use.  
✔ **Adaptive Clustering with Machine Learning** – Dynamically selects **cluster heads** based on energy levels, node density, and distance to base station.  
✔ **Reinforcement Learning-based Optimization** – Ensures efficient **energy balancing** for **longer network lifetime**.  
✔ **Fault-Tolerant Network Design** – Nodes adapt to failures and energy constraints dynamically.  
✔ **Simulation-Based Performance Evaluation** – Metrics include **energy consumption, throughput, and network longevity**.  

## ⚙️ Technologies Used  
- **Programming:** Python, MATLAB  
- **Machine Learning:** Reinforcement Learning, Q-Learning  
- **Network Algorithms:** Modified Dijkstra’s Algorithm  
- **Simulation:** Energy-aware simulations with **randomly distributed sensor nodes**  

## 📊 Performance Results  

| Model | Network Lifetime (Rounds) | Energy Consumption (J) | Packet Delivery Rate (%) |
|--------|------------------|--------------------|--------------------|
| **Our Approach** | **2000+** | **Optimized** | **Higher Stability** |
| LEACH | ~1000 | High | Unstable |
| HEED | ~1400 | Medium | Moderate |
| ML-Based Routing | ~1800 | Low | High |

🏆 **Key Takeaway**: **Adaptive clustering & multi-hop communication significantly improve WSN performance**!  

## 🏗 System Implementation  
### 1️⃣ **Network Setup & Initialization**  
- **Sensor Nodes:** 100 nodes randomly placed in a **100m x 100m** area  
- **Base Station:** Located centrally at **(50,50)**  
- **Initial Energy:** **2.5 Joules** per node  

### 2️⃣ **Multi-hop Routing & Energy Optimization**  
- **Modified Dijkstra’s Algorithm** selects the lowest-energy route  
- **Nodes communicate via 3-hop maximum to save energy**  

### 3️⃣ **Adaptive Clustering with Reinforcement Learning**  
- **State Space**: Energy ratio, node density, distance to base station  
- **Actions**: Become cluster head OR remain regular node  
- **Reward Function**: Encourages energy-efficient decisions  
- **Q-Learning Updates**: Adapts dynamically to network conditions  

### 4️⃣ **Data Transmission & Performance Monitoring**  
- Energy consumption calculated using:  
  - **Transmission Energy**: `E_tx = (E_elec + E_amp * d^n) * packet_size`  
  - **Reception Energy**: `E_rx = E_elec * packet_size`  
  - **Processing Energy**: `E_proc = P_proc * processing_time`  
- **Network metrics tracked in real-time**  

## 👨‍💻 Contributors  
| Name | Role |
|------|------|
| **Yasaswi Polasi** | Reinforcement Learning & Routing Optimization |
| **Sri Nikitha Veerla** | Clustering Algorithm & Performance Evaluation |
| **Abhishek Medikonda** | Multi-hop Communication & Energy Modeling |
| **Meghana Reddy Samreddy** | Data Processing & Visualization |
| **Anjali Reddy Kapila** | Simulation & Testing |

## 🚀 Future Enhancements  
🔹 **Deep Learning-Based Cluster Selection** for improved **adaptive routing**  
🔹 **Energy Harvesting Integration** (solar/vibration-based power sources)  
🔹 **Fault-Tolerant Clustering** for self-healing WSNs  
🔹 **Security Enhancements** to prevent **data tampering & unauthorized access**  

## 📖 References  
1. Heinzelman et al. *LEACH: Low-Energy Adaptive Clustering Hierarchy Protocol* (2000)  
2. Zhang & Wu. *Energy-Balanced Routing for WSNs* (2020)  
3. Kumar et al. *Machine Learning for Energy-Efficient WSNs* (2018)  
