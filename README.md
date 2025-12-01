# Optimizing Threat Detection using ML on Microsoft GUIDE

Machine learning model that accurately classifies cybersecurity alerts as either real threats or false positives. Using the Microsoft GUIDE dataset, the project optimizes for high threat detection rates (Recall) by addressing data imbalance and leveraging advanced feature engineering.

### **Objective**
The goal of this project is to build a machine learning model that accurately classifies cybersecurity alerts as either real threats or false positives. Using the Microsoft GUIDE dataset, the project optimizes for high threat detection rates (Recall) by addressing data imbalance and leveraging advanced feature engineering.

![Project Flow](./project-flow.png)


### **Project Step**s
* **Data Acquisition:** Downloaded the GUIDE dataset directly via the `kagglehub` API.
* **Data Cleaning:** Processed missing values and mapped anonymized IDs to Windows/Linux OS.
* **Visualization:** Plotted and compared the Top 10 incident types for Windows vs. Linux.
* **Baseline Modeling:** Trained Logistic Regression, Random Forest, and XGBoost to set benchmarks.
* **Feature Engineering:** Created new features based on event time and frequency rarity.
* **Optimization:** Applied Class Weights and Threshold Tuning to maximize incident detection.
* **Validation:** Verified performance gains using F1-Scores and Confusion Matrices.


