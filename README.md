#  Customer Churn Prediction Using Machine Learning

**Goal:** Predict whether a customer will leave a company using demographic and service-related data — and help businesses reduce churn through proactive retention strategies.


##  Overview

Customer churn refers to when customers stop doing business with a company. For subscription-based services like telecom, churn directly impacts revenue. This project uses machine learning to predict customer churn based on features such as demographics, account history, and service usage.



## Problem Statement

We aim to build a classification model that:

* Identifies customers who are likely to churn.
* Helps the business retain customers by taking early actions.

By analyzing features like **tenure, internet service type, monthly charges**, and more, we can generate actionable insights for reducing churn.



## Dataset Information

* **Dataset name:** `customer_data.csv`
* **Records:** 7,043 rows, 21 columns
* **Target Variable:** `Churn` (Yes/No)



##  Project Workflow

### 1. **Data Exploration**

* Checked for null values, data types, and distributions.
* Found 11 missing values in `TotalCharges`.

### 2. **Data Preprocessing**

* Handled missing values and converted `TotalCharges` to numeric.
* Applied **Label Encoding** to binary categorical features.
* Used **One-Hot Encoding** for multi-class categorical features.
* Scaled numerical features using **StandardScaler**.

### 3. **Modeling**

* Split data using an 80/20 **Train/Test** split.
* Trained and tested multiple models:

  * Logistic Regression
  * Random Forest Classifier
  * Support Vector Machine (SVM)
  * K-Nearest Neighbors (KNN)

### 4. **Evaluation**

* Evaluated using:

  * **Accuracy**
  * **Precision**
  * **Recall**
  * **F1 Score**
  * **ROC-AUC**
* Plotted confusion matrices and heatmaps for clarity.



## Tools Used

* **Python**
* **pandas**, **numpy**, **matplotlib**, **seaborn**
* **scikit-learn**
* **Jupyter Notebook**


## Final Deliverables

*  Jupyter Notebook with EDA, preprocessing, modeling, and evaluation.
*  < 5 min video presentation explaining the project end-to-end.
*  All files zipped and submitted as per project guidelines.


##  How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/yourusername/customer-churn-prediction.git
   cd customer-churn-prediction
   ```
2. Install requirements:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:

   ```bash
   jupyter notebook Customer_Churn_Analysis.ipynb
   ```


##  Key Takeaways

* Understanding customer churn is critical for long-term business success.
* Machine learning can identify high-risk customers with decent accuracy.
* Preprocessing and feature engineering significantly impact model performance.
* Random Forest and Logistic Regression performed best in our tests.



