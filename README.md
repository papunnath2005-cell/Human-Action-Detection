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

## ⚙️ Installation

### 1. Clone Repository
```bash
git clone https://github.com/your-username/human-action-detection.git
cd human-action-detection
