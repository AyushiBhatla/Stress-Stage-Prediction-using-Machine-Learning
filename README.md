# Mental Health Stress Level and Stage Prediction

## 📑 Project Description
This project aims to predict individuals' **stress levels** and **stress stages** (Low, Moderate, High) using Machine Learning techniques based on demographic, lifestyle, and mental health survey data.  
The workflow includes **data preprocessing**, **exploratory data analysis (EDA)**, **model training**, **multi-class classification**, and **single-sample prediction using a preprocessing pipeline**.

## 🏷️ Domain
- Mental Health Analysis
- Machine Learning
- Healthcare Informatics
- Data Science

## 🧩 Project Structure
| Notebook | Purpose |
|:---------|:--------|
| `1_Data_Preprocessing.ipynb` | Load, explore, clean, and encode the dataset |
| `2_EDA_and_Visualization.ipynb` | Perform visual and statistical analysis |
| `3_Stress_Level_Prediction.ipynb` | Train Random Forest, SVM, MLP on raw stress scores |
| `4_Stress_Stage_Classification.ipynb` | Categorize stress into stages and train models |
| `5_Single_Sample_Prediction.ipynb` | Deploy model for real-time individual prediction |

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Scikit-Learn
- Seaborn, Matplotlib
- Jupyter Notebook

## 📈 Machine Learning Models
- Random Forest Classifier
- Support Vector Machine (SVC)
- Multilayer Perceptron (MLP)

## 📊 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report

## 🚀 Highlights
- End-to-End ML pipeline for both regression (stress score) and classification (stress stage)
- Clear visualization of distributions, correlations, and feature relationships
- Preprocessing pipeline for real-time single-sample stress stage prediction

## 📥 Dataset
The dataset is sourced from internal research and stored at:
/content/drive/MyDrive/BDA /LAB 1/anxiety_depression_data.csv

Features include demographic information, lifestyle factors, and mental health assessment scores.

## 📂 Folder Structure (Recommended)
Stress-Stage-Prediction/
│
├── data/
│   └── anxiety_depression_data.csv
│
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_data_preprocessing.ipynb
│   ├── 03_model_training_evaluation.ipynb
│   ├── 04_final_model_prediction.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── model_training.py
│   ├── predict_single_sample.py
│
├── README.md
├── requirements.txt
└── .gitignore
