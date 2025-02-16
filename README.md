# Network Intrusion Detection

This project focuses on detecting network intrusions using machine learning techniques. It employs both supervised and unsupervised learning approaches to identify malicious activities in network traffic.

## Dataset
The project utilizes the **CICIDS2017** dataset, which contains labeled network traffic data, including both normal and attack instances.

## Methodology
The following machine learning techniques are used for intrusion detection:

- **LSTM (Long Short-Term Memory)**: Used as a supervised learning model to classify network traffic.
- **Isolation Forest**: Applied as an unsupervised anomaly detection technique to identify potential intrusions.

## Key Results
- The **LSTM model** was trained with a time step of **10** for sequence-based network traffic classification.
- The **Isolation Forest** effectively detected anomalies without requiring labeled attack data.

## Installation & Dependencies
Ensure you have the required Python libraries installed before running the notebook.

```bash
pip install numpy pandas scikit-learn tensorflow keras matplotlib seaborn
