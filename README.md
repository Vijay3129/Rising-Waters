# 🌊 Rising Waters

### AI-Powered Flood Prediction & Early Warning System

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black?logo=flask)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![XGBoost](https://img.shields.io/badge/Model-XGBoost-success)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)

---
## My Github - https://github.com/Vijay3129


# 🌍 Project Overview

**Rising Waters** is an AI-powered flood prediction system designed to provide **early flood risk assessments** using Machine Learning and environmental data analysis. The system analyzes critical weather and geographical parameters to determine the likelihood of flood occurrences and assists communities, governments, and disaster management agencies in making proactive decisions.

Floods are among the most destructive natural disasters, causing:

* Loss of human lives
* Destruction of infrastructure
* Agricultural damage
* Economic losses
* Displacement of communities
* Long-term environmental impacts

With increasing climate change and unpredictable weather patterns, traditional monitoring methods are often insufficient. **Rising Waters** bridges this gap by utilizing data-driven intelligence to predict flood risks before they become catastrophic.

---

# 🎯 Problem Statement

Natural disasters such as floods occur with little warning and often result in devastating consequences. Existing systems rely heavily on manual observations and delayed reporting.

The objective of this project is to build an intelligent system capable of:

* Predicting flood occurrence.
* Providing early warnings.
* Assisting in disaster preparedness.
* Supporting data-driven decision-making.

---

# 🚀 Key Features

✅ Real-Time Flood Prediction

✅ End-to-End Machine Learning Pipeline

✅ Automated Data Preprocessing

✅ Multiple Model Comparison

✅ High Accuracy Prediction Engine

✅ Interactive Web Application

✅ Early Warning System

✅ Scalable and Deployable Architecture

---

# 🏗 System Architecture

```text
                    Environmental Data
                              │
                              ▼
                  Data Collection & Cleaning
                              │
                              ▼
                     Data Preprocessing
                              │
      ┌────────────────────────────────────────┐
      │                                        │
      │  • Missing Value Handling              │
      │  • Categorical Encoding                │
      │  • Outlier Treatment                   │
      │  • Feature Scaling                     │
      └────────────────────────────────────────┘
                              │
                              ▼
                    Feature Engineering
                              │
                              ▼
                  Train-Test Dataset Split
                              │
                              ▼
                 Machine Learning Models
                              │
      ┌────────────────────────────────────────┐
      │                                        │
      │  • K-Nearest Neighbors (KNN)           │
      │  • Decision Tree                       │
      │  • Random Forest                       │
      │  • XGBoost                             │
      └────────────────────────────────────────┘
                              │
                              ▼
                    Model Evaluation
                              │
                              ▼
                    Best Model Selection
                              │
                              ▼
                    Flask Web Application
                              │
                              ▼
                    Real-Time Prediction
```

---

# 🧠 Machine Learning Workflow

```text
Dataset
   │
   ▼
Preprocessing
   │
   ▼
Feature Engineering
   │
   ▼
Train-Test Split
   │
   ▼
Model Training
   │
   ▼
Model Evaluation
   │
   ▼
Best Model Selection
   │
   ▼
Deployment
```

---

# 📊 Data Preprocessing Pipeline

The project follows a complete data preparation workflow:

### 1️⃣ Handling Missing Values

* Detect missing entries
* Verify dataset completeness
* Ensure clean input data

### 2️⃣ Handling Categorical Variables

* Feature Mapping
* Label Encoding

### 3️⃣ Outlier Detection

* Interquartile Range (IQR) Method
* Outlier Capping

### 4️⃣ Feature Scaling

* StandardScaler
* Data Standardization

### 5️⃣ Dataset Preparation

* Independent Variables (X)
* Target Variable (y)
* Training and Testing Sets

---

# 🤖 Machine Learning Models Used

| Model         | Purpose                 |
| ------------- | ----------------------- |
| KNN           | Baseline Classification |
| Decision Tree | Rule-Based Prediction   |
| Random Forest | Ensemble Learning       |
| XGBoost       | Boosting Algorithm      |

---

# 🏆 Final Model Selection

After evaluating multiple machine learning models, **XGBoost** was selected as the final deployment model because of:

* High prediction accuracy
* Strong generalization ability
* Better handling of complex relationships
* Lower overfitting risk
* Robust performance on structured data

### Final Accuracy

```text
Decision Tree : 96.55%
Random Forest : 96.55%
XGBoost       : 96.55%
```

⭐ **Selected Model: XGBoost**

---

# 🌐 Web Application

The system is deployed using **Flask**.

### Pages

| Page           | Description          |
| -------------- | -------------------- |
| home.html      | Project Landing Page |
| index.html     | User Input Form      |
| chance.html    | Flood Warning Page   |
| no_chance.html | Safe Condition Page  |

---

# 🔄 Prediction Workflow

```text
User Inputs Weather Parameters
                │
                ▼
     Apply StandardScaler
                │
                ▼
      Load Trained Model
                │
                ▼
       Generate Prediction
                │
                ▼
      Display Final Result
```

---

# 📂 Project Structure

```text
Rising-Waters/
│
├── dataset/
│   └── flood_dataset.csv
│
├── preprocessing/
│   ├── missing_values.py
│   ├── categorical_values.py
│   ├── outlier_handling.py
│   └── feature_scaling.py
│
├── models/
│   ├── knn_model.py
│   ├── decision_tree.py
│   ├── random_forest.py
│   ├── xgboost_model.py
│   └── compare_models.py
│
├── saved_models/
│   ├── floods.save
│   └── transform.save
│
├── templates/
│   ├── home.html
│   ├── index.html
│   ├── chance.html
│   └── no_chance.html
│
├── static/
│   ├── main.css
│   └── main.js
│
├── app.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

# 💻 Technologies Used

### Programming Language

* Python

### Libraries

* NumPy
* Pandas
* Scikit-Learn
* Matplotlib
* Seaborn
* Joblib

### Framework

* Flask

### Frontend

* HTML
* CSS
* JavaScript

---

# ⚙ Installation

## Clone Repository

```bash
git clone https://github.com/your-username/Rising-Waters.git
cd Rising-Waters
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run Application

```bash
python app.py
```

Open:

```text
http://127.0.0.1:5000
```

---

# 📸 Application Screenshots

```text
📌 Home Page Screenshot Here
📌 Prediction Form Screenshot Here
📌 Flood Alert Screenshot Here
📌 Safe Prediction Screenshot Here
```

---

# 🌍 Real-World Applications

* Disaster Management Authorities
* Government Agencies
* Smart Cities
* Weather Monitoring Centers
* Agricultural Planning
* Emergency Response Systems
* Community Safety Programs

---

# 🔮 Future Enhancements

* Real-time Weather API Integration
* IoT Sensor Data Collection
* Interactive Flood Maps
* SMS and Email Alerts
* Mobile Application
* Deep Learning Models
* Satellite Data Integration
* Cloud Deployment

---

# 🤝 Contribution

Contributions, suggestions, and improvements are always welcome.

```bash
Fork → Improve → Commit → Pull Request
```

---

# 📜 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Authors
**D. Hemanth Kumar (Team lead)**

**P. Karthik Sai (member)**

**L. Shivani (Member)**

**V. Vijay (Member)**

Artificial Intelligence & Machine Learning Enthusiast

*"Predicting disasters today to protect lives tomorrow."*

---

# **Thank you for consulting this project**

**I hope this can be helpful for your Research**
