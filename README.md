# sonar-anomaly-detection_ML
Anomaly detection system using Random Forest and Isolation Forest to identify known patterns and unknown outliers in real-world datasets.

# Overview
This project focuses on building a robust anomaly detection system by combining:

- Random Forest (Supervised Learning)
- Isolation Forest (Unsupervised Anomaly Detection)

The goal is to detect both **known patterns** and **unknown anomalies** in real-world datasets.
-----------------------------------------------------------------------------------------------------------
# Motivation
In real-world systems, labelled data is often limited or unavailable.

Especially in domains like:
- Sonar signal analysis
- Industrial monitoring
- Sensor-based systems

Anomalies are rare and unpredictable.

This project explores how combining supervised and unsupervised models improves detection capability.
-------------------------------------------------------------------------------------------------------------
# Approach

# 1. Data Preprocessing
- Loaded dataset using Pandas
- Cleaned and normalized features

# 2. Random Forest
- Trained on labelled data
- Used for the classification of known patterns

# 3. Isolation Forest
- Applied on feature space
- Detects anomalies based on isolation (outliers)

# 4. Evaluation
- Compared supervised vs unsupervised performance
- Tested model behaviour on edge cases and unseen data

----------------------------------------------------------------------------------------------------------------

# Results

- Isolation Forest successfully detected anomalies without labelled data
- Random Forest performed well on known patterns
- The combination provides a more robust detection system

📌 Visualization:
<img width="1153" height="687" alt="image" src="https://github.com/user-attachments/assets/870bb24b-60f3-44a5-89ca-ac87c288f9da" />

## 💡 Key Insight
Isolation Forest isolates anomalies based on how different they are from normal data, making it highly effective in real-world scenarios where labels are unavailable.

-------------------------------------------------------------------------------------------

# Applications
- Autonomous Underwater Vehicles (AUVs)
- Sonar anomaly detection
- Fraud detection
- Predictive maintenance
- Early warning systems
---------------------------------------------------------------------------------------------
# Tech Stack
- Python
- Pandas
- Scikit-learn
- Matplotlib

------------------------------------------------------------------------------------------------

# Future Work
- Real-time anomaly detection pipeline
- Integration with streaming data
- Deployment as an API

--------------------------------------------------------------------------------------------------

## 🤝 Connect
If you're working on anomaly detection or applied ML, feel free to connect!
