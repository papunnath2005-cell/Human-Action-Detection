# 🧍 Human Action Detection using Machine Learning

## 📌 Project Overview
This project focuses on **Human Action Detection** using machine learning techniques.  
The goal is to classify different human activities such as walking, sitting, standing, etc., based on sensor data.

The dataset used is the **mHealth (Mobile Health) dataset**, which contains body motion and vital signal recordings.

---

## 🚀 Features
- Data preprocessing and cleaning
- Handling imbalanced dataset using resampling
- Exploratory Data Analysis (EDA)
- Feature scaling (StandardScaler, RobustScaler)
- Multiple ML models implementation:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)
  - Decision Tree
  - Random Forest
  - Naive Bayes
- Model evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - Confusion Matrix

---

## 📊 Dataset Information
- Dataset: **mHealth Dataset**
- Format: CSV (zipped)
- Contains:
  - Sensor readings (accelerometer, gyroscope, etc.)
  - Activity labels

### 🏷️ Activity Labels
| Label | Activity |
|------|---------|
| 1 | Standing still |
| 2 | Sitting and relaxing |
| 3 | Lying down |
| 4 | Walking |
| 5 | Climbing stairs |
| 6 | Waist bends |
| 7 | Arm elevation |
| 8 | Knee bending |

---
### Output
<img width="727" height="789" alt="Screenshot 2026-04-02 102016" src="https://github.com/user-attachments/assets/c6fdc9b4-ab9b-4964-bbc1-3ed18d4a1626" />
<img width="727" height="777" alt="Screenshot 2026-04-02 102028" src="https://github.com/user-attachments/assets/d6829da3-3f01-4b1f-9474-7a8bf4fbabc7" />
<img width="747" height="381" alt="Screenshot 2026-04-02 102044" src="https://github.com/user-attachments/assets/a581e20c-76ea-489d-8f19-1625fed65a12" />
<img width="715" height="771" alt="Screenshot 2026-04-02 102006" src="https://github.com/user-attachments/assets/3ddbc6c9-82c8-40d2-87e8-3750d7e1f5a4" />

## ⚙️ Installation

### 1. Clone Repository
```bash
git clone https://github.com/your-username/human-action-detection.git
cd human-action-detection
