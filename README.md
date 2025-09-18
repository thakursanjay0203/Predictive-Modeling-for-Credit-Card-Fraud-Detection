# Predictive-Modeling-for-Credit-Card-Fraud-Detection
This project focuses on detecting fraudulent credit card transactions using data analytics and machine learning. It leverages real-world transaction data, addresses extreme class imbalance, and builds a predictive model to improve fraud detection accuracy and recall.

---

## Project Overview
- **Dataset Size:** 284,807 transactions  
- **Fraud Cases:** ~0.17% of total transactions (highly imbalanced)  
- **Techniques Used:** Data Cleaning, EDA, Resampling, Feature Engineering  
- **Model:** Logistic Regression  
- **Performance:** ~94% accuracy with improved fraud detection recall compared to baseline  

---

##  Key Steps
1. **Data Exploration & Cleaning**
   - Loaded and inspected dataset  
   - Checked for missing values and anomalies  
   - Performed statistical analysis on transaction amounts  

2. **Exploratory Data Analysis (EDA)**
   - Compared fraudulent vs legitimate transaction patterns  
   - Identified skewness in class distribution  

3. **Data Preprocessing**
   - Handled class imbalance using undersampling/oversampling  
   - Normalized/standardized relevant features  

4. **Model Development**
   - Trained Logistic Regression classifier  
   - Tuned model thresholds to optimize recall  
   - Evaluated using accuracy, precision, recall, and F1-score  

5. **Results**
   - Achieved ~94% accuracy  
   - Significantly improved recall for fraud detection  
   - Generated insights into transaction behavior for fraud patterns  
