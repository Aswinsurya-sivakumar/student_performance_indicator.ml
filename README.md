# 🎓 Student Performance Indicator

An end-to-end Machine Learning project that predicts a student's **math score** based on demographic, academic, and socio-economic factors — covering everything from data ingestion to a deployed, web-based prediction app.

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-Web%20App-black?logo=flask)
![scikit--learn](https://img.shields.io/badge/scikit--learn-ML-orange?logo=scikitlearn)
![AWS](https://img.shields.io/badge/AWS-Elastic%20Beanstalk-orange?logo=amazonaws)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Overview

**Student Performance Indicator** is an end-to-end Machine Learning project that predicts students' math performance based on demographic, academic, and other relevant factors. The project covers the complete ML lifecycle — data preprocessing, exploratory data analysis, feature engineering, model training and evaluation, Flask application development, and cloud deployment.

---

## 🚀 Key Features

- 🧹 Data preprocessing and exploratory data analysis (EDA)
- 🛠️ Feature engineering and data transformation pipelines
- 🤖 Training and evaluation of multiple Machine Learning models
- 🏆 Automated selection of the best-performing model
- 🌐 Web-based prediction interface built with Flask
- ☁️ Cloud deployment on AWS Elastic Beanstalk
- 📂 Version control and collaboration via Git and GitHub

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| **Language** | Python |
| **Data Handling** | Pandas, NumPy |
| **Machine Learning** | Scikit-learn |
| **Web Framework** | Flask |
| **Deployment** | AWS Elastic Beanstalk |
| **Version Control** | Git & GitHub |

---

## 🔄 Project Workflow

```
Data Collection
      │
      ▼
Data Preprocessing
      │
      ▼
Exploratory Data Analysis (EDA)
      │
      ▼
Feature Engineering
      │
      ▼
Model Training
      │
      ▼
Model Evaluation
      │
      ▼
Model Selection
      │
      ▼
Flask Application
      │
      ▼
AWS Elastic Beanstalk Deployment
```

---

## 📂 Project Structure

```
Student-Performance-Indicator/
├── artifacts/              # Saved model, preprocessor, and datasets
├── src/
│   ├── components/         # Data ingestion, transformation, model training
│   ├── pipeline/           # Prediction and training pipelines
│   ├── exception.py        # Custom exception handling
│   ├── logger.py           # Logging configuration
│   └── utils.py            # Utility functions
├── templates/               # HTML templates for the Flask app
├── application.py           # Flask app entry point
├── requirements.txt         # Project dependencies
└── README.md
```

> Update this section to match your actual repository structure.

---

## ⚙️ Getting Started

### Prerequisites
- Python 3.9+
- pip

### Installation

```bash
# Clone the repository
git clone https://github.com/Aswinsurya-sivakumar/Student-Performance-Indicator.git
cd Student-Performance-Indicator

# Create and activate a virtual environment
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

### Run the App

```bash
python application.py
```

The app will start locally — open your browser at `http://127.0.0.1:5000`.

---

## ☁️ Deployment

The Machine Learning application is deployed on **AWS Elastic Beanstalk**, providing a scalable, cloud-based environment for running the Flask prediction application in production.

---

## 🎯 Objective

The main objective of this project is to demonstrate an end-to-end Machine Learning workflow — from preparing data and developing a predictive model, to building and deploying a fully functional, web-based Machine Learning application.

---

## 👨‍💻 Author

**Aswin Surya Sivakumar**

[![GitHub](https://img.shields.io/badge/GitHub-Aswinsurya--sivakumar-181717?logo=github)](https://github.com/Aswinsurya-sivakumar)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

⭐ If you found this project helpful, consider giving it a star on GitHub!
