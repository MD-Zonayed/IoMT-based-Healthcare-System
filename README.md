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

# 🤖 Machine Learning Models

Six supervised Machine Learning algorithms were evaluated and compared.

| Model | Description or Purpose | Advantages |
|-------|-------------|------------|
| Gradient Boosting Classifier | Ensemble boosting algorithm & viral infection prediction | Highest prediction accuracy |
| Random Forest | Bagging ensemble model or ensemble learning baseline | Robust against overfitting |
| Decision Tree | Tree-based classifier or rule-based classification | Easy interpretation |
| Logistic Regression | Linear probabilistic classifier or linear classification baseline | Fast training |
| Support Vector Machine | Margin maximization classifier or margin-based classification | Effective in high-dimensional data |
| K-Nearest Neighbors | Distance-based classifier | Simple and non-parametric |

The **Gradient Boosting Classifier (GBC)** achieved the best overall performance after hyperparameter tuning or optimization, demonstrating superior predictive capability for viral infection detection. Among all evaluated models, the **GBC** achieved the highest predictive performance, reaching **97.5% accuracy**. :contentReference[oaicite:4]{index=4}

---

# 🧠 Machine Learning Workflow

The proposed healthcare framework employs a complete machine learning pipeline for intelligent viral infection prediction. Physiological data collected from wearable sensors undergo preprocessing, feature engineering, model training, hyperparameter optimization, and performance evaluation before deployment.

## Machine Learning Pipeline

```text
Wearable Sensors
        │
        ▼
Data Collection
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Train-Test Split
        │
        ▼
Machine Learning Models
        │
        ▼
Hyperparameter Optimization
        │
        ▼
Performance Evaluation
        │
        ▼
Prediction
```

---

# 📊 Dataset Description

The machine learning dataset consists of physiological measurements collected from wearable healthcare sensors.

## Physiological Parameters

| Parameter | Sensor | Purpose |
|-----------|--------|---------|
| Body Temperature | DS18B20 | Fever detection |
| Heart Rate | MAX30102 | Cardiovascular monitoring |
| Blood Oxygen (SpO₂) | MAX30102 | Respiratory assessment |
| Body Movement | MPU6050 | Activity monitoring |

These physiological indicators are commonly associated with viral infections and provide valuable information for intelligent healthcare prediction.

---

# 🌐 Internet of Medical Things (IoMT)

## IoMT Architecture

<p align="center">

<img src="images/iomt_architecture.png" width="900"/>

</p>

The proposed Internet of Medical Things (IoMT) framework enables secure acquisition, transmission, storage, and intelligent analysis of healthcare data to enable continuous patient monitoring and intelligent healthcare management.

The layered architecture consists of:

- Sensor Layer
- Gateway Layer
- Cloud Layer
- Machine Learning Layer
- User Interface Layer

This architecture supports efficient data collection, preprocessing, cloud communication, predictive analytics, and real-time healthcare visualization. :contentReference[oaicite:3]{index=3}

## IoMT Workflow

```text
Wearable Sensors
        │
        ▼
Raspberry Pi Gateway
        │
        ▼
Data Preprocessing
        │
        ▼
Cloud Storage
        │
        ▼
Machine Learning Analysis
        │
        ▼
Prediction Results
        │
        ▼
Healthcare Dashboard
```

---

# 📡 IoMT Components

| Component | Function |
|-----------|----------|
| Wearable Sensors | Collect physiological signals |
| Raspberry Pi | Edge computing and data aggregation |
| Wireless Communication | Transfer healthcare data |
| Cloud Platform | Store and manage patient records |
| Machine Learning Engine | Predict viral infections |
| Healthcare Dashboard | Display monitoring results |

---

# ⚕️ Wearable Healthcare Design

<p align="center">
<img src="images/wearable_design.png" width="750"/>
</p>

The wearable device integrates multiple biomedical sensors into a compact healthcare monitoring platform capable of continuously collecting physiological signals.

The modular architecture allows future integration of additional biomedical sensors and intelligent diagnostic algorithms.

---

# 🔧 Signal Processing

Before training machine learning models, the collected physiological signals undergo several preprocessing steps:

- Missing value handling
- Noise removal
- Data normalization
- Feature extraction
- Feature selection
- Dataset balancing

These preprocessing techniques improve data quality and increase model robustness.

---

# 📈 Performance Evaluation

Model performance was evaluated using multiple statistical metrics.

| Metric | Purpose |
|---------|----------|
| Accuracy | Overall prediction performance |
| Precision | Positive prediction quality |
| Recall | Sensitivity |
| F1-Score | Balance between precision and recall |
| Confusion Matrix | Classification analysis |
| ROC Curve | Threshold evaluation |
| AUC Score | Overall classifier discrimination |

---

# 🏆 Experimental Results

The experimental evaluation demonstrated that the proposed IoMT-based healthcare framework can accurately predict viral infections using wearable physiological data.

Key findings include:

- Successful real-time physiological monitoring
- Reliable wearable sensor integration
- Efficient IoMT communication
- Accurate machine learning prediction
- Effective hyperparameter optimization
- High system reliability
- Real-time healthcare monitoring capability

The optimized **Gradient Boosting Classifier** achieved the highest prediction performance with an overall accuracy of **97.5%**, outperforming the remaining evaluated machine learning algorithms.

---

# 📊 Performance Comparison

| Model | Accuracy |
|--------|---------:|
| Gradient Boosting Classifier | **97.50%** |
| Random Forest | **97.1%** |
| Decision Tree | **96.3%** |
| Logistic Regression | **94%** |
| Support Vector Machine | **91.4** |
| K-Nearest Neighbors | **95** |

---

# 💡 Technical Contributions

The major technical contributions of this research include:

- Development of an IoMT-enabled wearable healthcare monitoring system.
- Integration of Raspberry Pi with biomedical sensors.
- Comparative evaluation of six supervised machine learning algorithms.
- Hyperparameter optimization for improved prediction accuracy.
- Intelligent viral infection prediction using physiological data.
- Scalable architecture for remote healthcare monitoring.
- Modular framework suitable for future healthcare applications.

---

# 🎯 Applications

The proposed framework can be applied in:

- Smart Hospitals
- Remote Patient Monitoring
- Home Healthcare
- Elderly Care
- Rural Healthcare
- Pandemic Monitoring
- Preventive Healthcare
- Telemedicine
- Medical Research
- AI-assisted Clinical Decision Support

---

# 🔬 Research Impact

This work demonstrates how Artificial Intelligence, Machine Learning, and the Internet of Medical Things can work together to create intelligent healthcare systems capable of improving disease prediction, enabling remote patient monitoring, and supporting data-driven healthcare decisions.

The proposed framework provides a scalable foundation for future AI-assisted healthcare applications and contributes toward the advancement of next-generation digital health technologies.

---

# 📂 Source Code Organization

| Folder | Description |
|---------|-------------|
| `src/sensors/` | Sensor interfacing and data acquisition |
| `src/preprocessing/` | Data cleaning, normalization, and feature engineering |
| `src/machine_learning/` | Model training and prediction |
| `src/evaluation/` | Model evaluation and comparison |
| `src/visualization/` | Data visualization and plots |
| `app/` | User interface and healthcare dashboard |
| `datasets/` | Raw and processed datasets |
| `models/` | Saved trained machine learning models |
| `results/` | Experimental results, graphs, and figures |
| `docs/` | Manuscript, presentation, and supplementary materials |

---

# 🧪 Reproducibility

To reproduce the experimental results:

1. Install all required Python packages.
2. Prepare the dataset in the `datasets/raw/` directory.
3. Execute the preprocessing pipeline.
4. Train each machine learning model.
5. Perform hyperparameter optimization.
6. Evaluate model performance using the provided scripts.
7. Compare results with those reported in the manuscript.

---

# 📦 Python Dependencies

The project primarily uses the following libraries:

- Python 3.10+
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook
- Raspberry Pi GPIO (for hardware integration)
- Flask or Streamlit (if dashboard is included)

These should be listed in the `requirements.txt` file.

---

# 🔒 Security & Privacy

This repository is intended for research and educational purposes.

Before publishing:

- Remove Wi-Fi credentials.
- Remove API keys or authentication tokens.
- Anonymize any patient-related information.
- Do not upload personally identifiable healthcare data.
- Share only de-identified or publicly available datasets.

---

# 📈 Future Improvements

Potential future enhancements include:

- Deep Learning-based disease prediction
- Transformer-based healthcare models
- Federated Learning for privacy-preserving healthcare
- Explainable AI (XAI) for clinical decision support
- Real-time cloud deployment
- Integration with wearable smartwatches
- Multi-disease prediction framework
- Edge AI optimization for Raspberry Pi
- Mobile healthcare application
- Large Language Model (LLM)-assisted clinical support

---

# 🌍 Potential Applications

This framework can support:

- Remote Patient Monitoring
- Smart Hospitals
- Home Healthcare
- Elderly Care
- Telemedicine
- Rural Healthcare
- Pandemic Surveillance
- Preventive Healthcare
- AI-Assisted Diagnosis
- Medical Research

---

# 📚 Related Publications

This repository complements the following research works:

- Machine Learning and IoT in Healthcare: Recent Advancements, Challenges & Future Directions
- An Ensemble Machine Learning Approach for Viral Infection Prediction using IoMT

---

# 📖 Citation

If you use this repository in your research, please cite:

```bibtex
@article{zonayed2026iomt,
  author  = {MD Zonayed and Co-authors},
  title   = {IoMT-Based Wearable Healthcare Monitoring and Viral Infection Prediction Using Machine Learning},
  journal = {Under Review},
  year    = {2026}
}
```

> **Note:** Update the citation with the final journal name, volume, pages, DOI, and publication year after acceptance.

---

# 🤝 Acknowledgements

The authors would like to thank:

- World University of Bangladesh
- Department of Mechatronics Engineering
- Dreamers Lab
- Supervisors and collaborators
- Researchers who contributed to data collection and manuscript preparation

---

# 👨‍💻 About the Author

## MD Zonayed

**Research Assistant | Mechatronics Engineer | AI & Robotics Researcher**

### Research Interests

- Artificial Intelligence
- Machine Learning
- Deep Learning
- Internet of Medical Things (IoMT)
- Healthcare AI
- Computer Vision
- Robotics & Automation
- Internet of Things (IoT)
- Precision Agriculture
- Human-Robot Collaboration

### 📬 Contact

📧 **Email:** iamzunayed@gmail.com

🌐 **LinkedIn**  
https://www.linkedin.com/in/md-zonayed-8966a8276

📚 **Google Scholar**  
https://scholar.google.com/citations?user=oDymy0IAAAAJ&hl=en

🔬 **ResearchGate**  
https://www.researchgate.net/profile/Md-Zonayed

---

# ⭐ Support the Project

If you find this repository useful:

- ⭐ Star the repository
- 🍴 Fork the repository
- 📖 Cite this work in your research
- 🤝 Contribute improvements
- 📬 Contact the author for collaborations

---

<p align="center">

<b>🏥 Advancing Intelligent Healthcare through Artificial Intelligence, Machine Learning, and the Internet of Medical Things (IoMT) 🏥</b>

</p>
