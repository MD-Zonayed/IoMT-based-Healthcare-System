# 🏥 IoMT-Based Wearable Healthcare Monitoring and Viral Infection Prediction Using Ensemble Machine Learning

<p align="center">
  <img src="images/banner.png" alt="Healthcare IoMT Banner" width="900"/>
</p>

<p align="center">

<img src="https://img.shields.io/badge/Status-Research%20Completed-success?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Healthcare-IoMT-red?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Machine%20Learning-Healthcare-blue?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Python-3.10-yellow?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Raspberry%20Pi-IoMT-green?style=for-the-badge"/>

<img src="https://img.shields.io/badge/Research-Medical%20AI-orange?style=for-the-badge"/>

</p>

---

# 📖 Project Overview

This repository contains our research on an **Internet of Medical Things (IoMT)-based wearable healthcare monitoring system** integrated with **Machine Learning** for early prediction of viral infections.

The proposed framework combines wearable physiological sensors, Raspberry Pi edge computing, cloud-enabled IoMT infrastructure, and intelligent machine learning algorithms to continuously monitor patient health and predict potential viral infections before severe symptoms appear.

The system collects multiple physiological parameters including body temperature, heart rate, blood oxygen saturation (SpO₂), and body movement. These measurements are processed using machine learning algorithms to assist healthcare professionals in early diagnosis and remote patient monitoring.

The research demonstrates how Artificial Intelligence and IoMT can support modern healthcare by enabling intelligent monitoring, early warning systems, and data-driven clinical decision-making.

---

# 🎯 Research Objectives

The primary objectives of this research are:

- Develop a wearable IoMT healthcare monitoring platform.
- Monitor multiple physiological parameters in real time.
- Predict viral infections using Machine Learning.
- Compare multiple supervised learning algorithms.
- Improve prediction accuracy through hyperparameter optimization.
- Enable remote healthcare monitoring.
- Support intelligent healthcare decision making.
- Reduce diagnostic delay through early prediction.

---

# ✨ Key Features

✅ Wearable Healthcare Monitoring

✅ Internet of Medical Things (IoMT)

✅ Real-Time Physiological Monitoring

✅ Raspberry Pi Edge Computing

✅ Cloud-Based Healthcare Architecture

✅ Viral Infection Prediction

✅ Machine Learning-Based Diagnosis

✅ Hyperparameter Optimization

✅ Remote Patient Monitoring

✅ Intelligent Healthcare Dashboard

✅ Multi-Sensor Data Acquisition

✅ High Prediction Accuracy

---

# 🏗 System Architecture

<p align="center">

<img src="images/system_block_diagram.png" width="900"/>

</p>

The proposed healthcare system consists of five interconnected layers:

- Wearable Sensor Layer
- Gateway / Edge Layer
- Cloud Layer
- Machine Learning Layer
- User Interface Layer

Physiological data collected by wearable sensors are transmitted to the Raspberry Pi gateway, processed through IoMT infrastructure, analyzed using machine learning models, and presented to healthcare professionals through a graphical user interface. :contentReference[oaicite:2]{index=2}

---

# 🌐 IoMT Architecture

<p align="center">

<img src="images/iomt_architecture.png" width="900"/>

</p>

The proposed Internet of Medical Things (IoMT) framework enables secure acquisition, transmission, storage, and intelligent analysis of healthcare data.

The layered architecture consists of:

- Sensor Layer
- Gateway Layer
- Cloud Layer
- Machine Learning Layer
- User Interface Layer

This architecture supports efficient data collection, preprocessing, cloud communication, predictive analytics, and real-time healthcare visualization. :contentReference[oaicite:3]{index=3}

---

# ⚙️ Hardware Components

| Hardware | Purpose |
|-----------|---------|
| Raspberry Pi 4B | Edge computing, sensor integration, data acquisition, machine learning interface |
| DS18B20 Temperature Sensor | Continuous body temperature monitoring |
| MAX30102 Sensor | Heart rate and blood oxygen (SpO₂) monitoring |
| MPU6050 Accelerometer | Body movement and activity detection |
| Wi-Fi Module (Built into Raspberry Pi) | Wireless communication with cloud services |
| Wearable Sensor Module | Continuous physiological data acquisition |
| Power Supply | Portable system operation |

---

# 💻 Software & Development Tools

| Software | Purpose |
|-----------|---------|
| Python | Core programming language |
| Scikit-learn | Machine learning model development |
| Pandas | Data preprocessing |
| NumPy | Numerical computation |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Model development and experimentation |
| VS Code | Software development |
| Raspberry Pi OS | Embedded operating system |
| Git & GitHub | Version control and collaboration |

---

# 🔬 Machine Learning Models

Six supervised Machine Learning algorithms were evaluated and compared.

| Algorithm | Purpose |
|------------|---------|
| Gradient Boosting Classifier | Viral infection prediction |
| Random Forest Classifier | Ensemble learning baseline |
| Decision Tree | Rule-based classification |
| Logistic Regression | Linear classification baseline |
| Support Vector Machine | Margin-based classification |
| K-Nearest Neighbors | Distance-based classification |

Among all evaluated models, the **Gradient Boosting Classifier (GBC)** achieved the highest predictive performance after hyperparameter optimization, reaching **97.5% accuracy**. :contentReference[oaicite:4]{index=4}

---

# 📂 Repository Structure

```text
Healthcare-IoMT-ML/
│
├── README.md
├── LICENSE
├── requirements.txt
├── CITATION.cff
│
├── docs/
│
├── datasets/
│
├── models/
│
├── notebooks/
│
├── src/
│
├── images/
│
├── results/
│
└── app/
```

---
