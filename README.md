# 🤰 AI-Powered Fetal Monitoring Belt

This project is part of a year-long Engineering Design Project (EDP) at IIIT Jabalpur. The AI-Powered Fetal Monitoring Belt is an intelligent, wearable medical device that non-invasively tracks fetal and maternal parameters using ECG and EMG sensors. It applies advanced signal separation (CAA-CycleGAN) and AI classification (LightGBM) to provide real-time fetal health insights via a cloud-based dashboard. Designed for affordability and accessibility, the system bridges the gap between hospital-grade prenatal care and home-based monitoring.

---

## 🚀 Project Summary

The **AI-Powered Fetal Monitoring Belt** is a non-invasive, smart wearable that monitors critical fetal and maternal parameters using embedded sensors and intelligent AI models. Unlike traditional Cardiotocography (CTG) systems, this belt offers a low-cost, real-time alternative with cloud connectivity, making fetal healthcare accessible even in remote or resource-limited settings.

---

## 🎯 Objectives

- Enable real-time monitoring of fetal health during second and third trimesters.
- Use multimodal physiological data (ECG, EMG, accelerometer, temperature).
- Apply AI techniques for fetal health classification.
- Deliver real-time alerts and historical trends to doctors and expecting mothers via Web UI.
- Offer a cost-effective and scalable solution for maternal healthcare.

---

## 🧠 Novel Contributions

- **Dual-Sensor Integration**: Combines ECG (fetal heart rate) and EMG (uterine contractions) in one belt.
- **CAA-CycleGAN for Signal Separation**: A deep learning model that isolates fetal ECG from noisy abdominal recordings.
- **AI-Powered Health Prediction**: Uses a LightGBM classifier trained on medical data to detect fetal health conditions with **98.38% accuracy** and **0.9985 ROC AUC**.
- **MERN Stack Web UI**: Real-time dashboard for clinicians and mothers.
- **Edge + Cloud Integration**: Supports both local processing and cloud-based visualization.

---

## 🛠️ System Architecture

### 1. Data Collection
- **AD8232 ECG Sensor**: Monitors fetal heart rate.
- **EMG Sensor**: Detects uterine contractions.
- **Temperature & Accelerometer Sensors**: Monitor maternal vitals and fetal movement.

### 2. Signal Processing
- **CAA-CycleGAN**: Deep learning model for separating fetal ECG (FECG) from maternal ECG.
- **Attention Mechanism**: Enhances relevant signal components for cleaner extraction.

### 3. AI Prediction
- **LightGBM Classifier**: Predicts fetal health status – `Normal`, `Suspect`, or `Pathological`.

### 4. Web UI (MERN Stack)
- Real-time visualizations and alerts for patients and clinicians.
- Historical data trends, downloadable reports, and anomaly notifications.

---
