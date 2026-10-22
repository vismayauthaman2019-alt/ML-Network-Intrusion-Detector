# 🛡️ ML Network Intrusion Detector

## 📌 Project Overview
This repository contains a robust Machine Learning Network Intrusion Detection System (NIDS) developed as part of the BharatCares IBM SkillsBuild Cyber Security Bootcamp. The system applies predictive modeling to network traffic logs, classifying connections as either benign or anomalous to detect potential cyber threats before they compromise internal infrastructure.

## 🛠️ Technology Stack & Dependencies

| Category | Technology / Library | Purpose |
| :--- | :--- | :--- |
| **Language** | Python 3.10+ | Core programming and logic execution. |
| **ML Framework** | Scikit-learn (1.3.0) | Model training, classification, and dataset retrieval. |
| **Data Processing** | Pandas (2.0.3), Numpy (1.24.3) | DataFrame manipulation and numerical array operations. |

## 📊 Dataset Specifications
This project utilizes the **KDDCup99 Dataset**, widely recognized as a standard for NIDS evaluation.
* **Source:** Fetched dynamically via `sklearn.datasets.fetch_kddcup99`.
* **Features:** 41 attributes per connection (e.g., duration, protocol_type, flag, src_bytes, dst_bytes).
* **Target:** Binary classification mapped from 22 distinct attack types.

## 🚀 Setup and Execution Instructions

### Option 1: Cloud Execution (Google Colab)
1. Upload the `Vismaya_MLIntrusionDetector.ipynb` file to Google Colab.
2. Navigate to **Runtime > Run all** to execute the pipeline.
3. Review the generated classification metrics at the bottom of the notebook.

### Option 2: Local Environment Execution
1. Clone the repository to your local machine:
   ```bash
   git clone [https://github.com/YourUsername/ML-Network-Intrusion-Detector.git](https://github.com/YourUsername/ML-Network-Intrusion-Detector.git)
