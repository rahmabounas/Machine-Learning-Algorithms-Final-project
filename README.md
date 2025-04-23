# 🛡️ Microsoft Malware Prediction – ML Project

## 📌 Description

This project is based on the **Microsoft Malware Prediction** dataset, originally released as part of a Kaggle competition. The checkpoint is designed to practice and apply both **supervised** and **unsupervised machine learning** methods using a simplified version of the dataset.

You'll explore Windows OS-based machine data to predict the probability of malware infection and cluster machines based on system features. The aim is to build robust models that could help in identifying vulnerable systems and suggesting preventive actions.

---

## 📂 Dataset Overview

📍 Each row corresponds to a unique machine's purchase history and system state.

🧪 Dataset Fields (partial list):

| Feature/Variable                | Explanation                                                                                              |
|-------------------------------|----------------------------------------------------------------------------------------------------------|
| `Wdft_IsGamer`                | Indicates whether the device is a gamer device or not based on its hardware configuration.               |
| `Census_IsVirtualDevice`      | Identifies a Virtual Machine (machine learning model).                                                    |
| `Census_OSEdition`            | Edition of the current OS.                                                                                |
| `Census_HasOpticalDiskDrive` | True indicates that the machine has an optical disk drive (CD/DVD).                                       |
| `Firewall`                    | This attribute is true (1) for Windows 8.1 and above if Windows firewall is enabled.                      |
| `SMode`                       | Set to true when the device is known to be in 'S Mode', e.g. Windows 10 S mode.                           |
| `IsProtected`                 | Calculated field from SpyNet: TRUE = at least one active and up-to-date antivirus product; FALSE = none. |
| `OsPlatformSubRelease`        | Returns the OS platform sub-release (Vista, Win7, Win8, etc.).                                           |
| `CountryIdentifier`           | ID for the country the machine is located in.                                                             |

🖼️ [Dataset Preview](https://drive.google.com/file/d/13hQ-46e6Q7zvLgx8jmQ2R_HwcvKjhpCA/view)

---

## 🎯 Objectives

### Part 1: Supervised Learning

- Import the dataset and perform initial data exploration
- Display general information and generate a **Pandas Profiling Report**
- Handle missing or corrupted values
- Remove duplicate rows
- Detect and treat outliers
- Encode categorical features
- Prepare data for modeling
- Train a **Decision Tree Classifier**
  - Plot its ROC Curve
- Tune hyperparameters to improve performance

---

### Part 2: Unsupervised Learning

- Drop the target variable
- Apply **K-Means Clustering**
  - Plot the clusters
  - Determine optimal **K** value
- Interpret clustering results

---

## 📌 How to Use

1. Clone the repository
2. Install the required libraries (`pandas`, `numpy`, `matplotlib`, `scikit-learn`)
3. Run each step in a Jupyter notebook or Python script
4. Analyze the outputs and tune models accordingly

---

## 📊 Final Goal

Use both supervised and unsupervised methods to:
- Predict malware infection
- Understand machine clustering
- Help security analysts identify vulnerable machine profiles

---

📎 **Note**: This dataset has been modified for educational use. The results are not meant for production deployment but for practice and skill development.



