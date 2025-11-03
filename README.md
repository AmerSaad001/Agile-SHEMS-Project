# 🏠 Smart Home Energy Management System (SHEMS)

This project was developed for the **Agile Software Development** course at Lakehead University.  
It combines **Multi-Agent Systems (MAS)**, **Blockchain**, and **LSTM-based prediction** to optimize smart home energy consumption and enable peer-to-peer trading.

---

## ⚙️ Overview
SHEMS is a decentralized platform where intelligent agents coordinate to manage household energy.  
It predicts energy demand, balances loads, and allows households to trade excess energy securely using blockchain.

**Main Features:**
- 🔋 Prediction Agent – forecasts hourly power demand using LSTM  
- ⚖️ Demand Response Agent – shifts or reschedules loads dynamically  
- 💰 Negotiation Agent – performs P2P energy trading via smart contracts  
- 👥 Behavioral Agent – clusters users and appliances based on usage patterns  
- 🧩 Facilitating Agent – coordinates communication between all other agents  

---

## 🧠 Machine Learning
- Built and trained **LSTM (Long Short-Term Memory)** models using real and simulated datasets  
- Achieved **92% accuracy** on consumption prediction  
- Compared performance with Linear Regression, Random Forest, and XGBoost models  

---

## 📊 Dataset
The system uses both real-world and simulated data:
- **REDD Dataset:** Appliance-level energy usage  
- **NREL Dataset:** Solar generation data  
- **OPSD Dataset:** Grid data for load balancing  
- **smart_home_energy.csv:** Custom dataset for testing and model evaluation  

---

## 🚀 Results
| Metric | Traditional System | MAS System |
|:-------|:------------------:|:-----------:|
| Energy Efficiency | 8% | **22%** |
| Prediction Accuracy | 75% | **92.3%** |
| Grid Dependency | 10% | **30%** |
| Energy Cost Reduction | 5% | **18%** |

---

## 🧩 Technologies Used
- **JADE (Java Agent DEvelopment Framework)** – for multi-agent coordination  
- **Python (TensorFlow, pandas, NumPy)** – for prediction and analysis  
- **MySQL** – for storing trading and consumption data  
- **Blockchain (conceptual)** – for secure energy transactions  

---

## 🧾 Development Approach
Followed the **Agile (Scrum)** methodology with iterative sprints:
1. System design and agent modeling  
2. LSTM model development  
3. Integration and testing in JADE  
4. Data visualization and analysis  

---

## 👥 Authors
Developed by **Amer Saad & Team**  
Lakehead University — 2024  

---

## ⚠️ Disclaimer
This repository contains only simulation and academic research code.  
No real-world user data or private credentials are included.
