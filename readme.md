# ⚙️ Industrial Anomaly Detection System with MLOps

![Streamlit Demo](images/streamlit.png)

A production-ready **AI/ML anomaly detection system** using an **LSTM Autoencoder** on NASA turbofan engine sensor data.  
The project includes model training, real-time inference, Streamlit UI, FastAPI backend, prediction logging, monitoring, automated retraining, Docker, and GitHub Actions CI.

---

## 🚀 Project Highlights

- Built an LSTM Autoencoder for time-series anomaly detection
- Used NASA turbofan engine sensor data
- Added FastAPI backend for real-time prediction
- Built Streamlit UI for interactive testing
- Added prediction logging
- Generated monitoring reports from inference logs
- Added automated retraining trigger based on anomaly rate
- Dockerized FastAPI and Streamlit services
- Added unit tests and GitHub Actions CI pipeline

---

## 📌 Use Case

This project simulates an **industrial predictive maintenance system**.

It detects abnormal sensor behavior in machines such as:

- aircraft engines
- manufacturing systems
- industrial IoT devices
- automotive components
- production equipment

---

## 🏗️ Architecture

```text
NASA Sensor Data
      ↓
Preprocessing + Sliding Windows
      ↓
LSTM Autoencoder
      ↓
Reconstruction Error
      ↓
Anomaly Threshold
      ↓
NORMAL / ANOMALY Prediction
      ↓
FastAPI + Streamlit
      ↓
Prediction Logs
      ↓
Monitoring Report
      ↓
Automatic Retraining Trigger
