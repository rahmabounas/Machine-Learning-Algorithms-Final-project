# 🛡️ Microsoft Malware Prediction – ML Project

## 🧾 Description

This project uses the **Microsoft Malware Prediction** dataset to explore both **supervised** and **unsupervised** machine learning techniques. The dataset contains system-level information about Windows machines, with the objective of predicting whether a system will be infected by malware.

The checkpoint walks through the entire ML pipeline, including data cleaning, modeling, and evaluation, and serves as a practical application of major machine learning concepts.

---

## 🗂️ Dataset Overview

- 📌 Source: Simplified version of the original **Kaggle Microsoft Malware Prediction** dataset.
- 🧠 Each row = one Windows machine.
- 🎯 Target variable = Whether or not the machine is infected with malware.

![Dataset Sample](https://i.imgur.com/hv2Ynyn.jpg)

---

## 🎯 Objectives

- Build a classification model to predict malware infections.
- Cluster systems based on feature similarity to discover hidden patterns.
- Apply essential data preprocessing techniques like handling missing values, encoding, and outlier removal.

---

## 🛠️ Tools & Libraries

- Python
- pandas, numpy
- sklearn
- seaborn, matplotlib
- pandas-profiling
- plotly (optional for advanced visualizations)

---

## 🧪 Project Structure

### 🔹 Part 1: Supervised Learning (Classification)

1. Import & explore the data  
2. Create a pandas profiling report  
3. Handle missing values, outliers, duplicates  
4. Encode categorical variables  
5. Prepare data for modeling  
6. Apply **Decision Tree Classifier**  
7. Evaluate using **ROC curve**  
8. Tune model hyperparameters  

### 🔹 Part 2: Unsupervised Learning (Clustering)

1. Drop the target variable  
2. Apply **K-Means Clustering**  
3. Find the optimal **K** using Elbow Method / Silhouette Score  
4. Visualize and interpret the clusters  

---

## 📈 Example Outputs

- 📊 ROC Curve for Decision Tree performance
- 🔍 Cluster visualization for unsupervised insights
- 📋 Data summary reports showing system characteristics

---

