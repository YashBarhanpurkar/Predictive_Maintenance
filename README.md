# Predictive Maintenance for Industrial Automation
*Applying Data Analytics to reduce downtime in smart manufacturing.*

## Project Overview
This project uses the **AI4I 2020 Predictive Maintenance Dataset** to identify mechanical failure patterns in production machines. As a GPE student at TU Berlin, my goal is to bridge the gap between traditional mechanical engineering and AI-driven automation.

## 📊 Phase 1 & 2: Root Cause Analysis (RCA)
I analyzed 10,000 rows of industrial sensor data to find the primary drivers of failure.

### Key Insights:
*   **Temperature:** Analysis showed only a **0.3K difference** in process temperature between healthy and failed machines, indicating thermal stress is not a primary failure mode here.
*   **Torque:** Failed machines showed a **26% higher average torque** (50.16 Nm) compared to healthy ones (39.63 Nm).
*   **Mechanical Fingerprint:** Failures are highly concentrated in the **High Torque / Low Speed** region and the **Extreme High Speed** tail.

![Failure Fingerprint](failure_fingerprint.png)

## 🛠️ Tech Stack
*   **Language:** Python 3.13.5
*   **Libraries:** Pandas (Data Wrangling), Matplotlib/Seaborn (Visualization), Scikit-Learn (Future Modeling)
*   **Environment:** Conda (venv)