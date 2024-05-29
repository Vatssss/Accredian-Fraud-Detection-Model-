# Accredian-Fraud-Detection-Model-
# INSAID- ACCREDIAN Internship Task Data Science &amp; Machine Learning
This project implements a fraud detection model using data from a transaction dataset.

**Project Steps:**

1. **Data Loading and Cleaning:**
   - Load Data:
     Load transaction data from "Fraud.csv".

   - Handling Missing Values:
     Identify missing values in the dataset.

   - Outlier Detection:
      Detect outliers in the 'amount' column using the Interquartile Range (IQR) method.

2. **Feature Engineering:**
   - Select Relevant Features:
      Choose numeric features relevant to fraud detection: step, amount, oldbalanceOrg, newbalanceOrig, oldbalanceDest, newbalanceDest, isFlaggedFraud.

3. **Model Training:**
   - Split Data:
      Split the data into training and testing sets (65% training, 35% testing).

   - Train Model:
      Train a logistic regression model on the training data.

**Code Structure:**
- `Fraud.csv`: Contains transaction data (features and target variable isFraud).
- `fraudDetection.ipynb`: Jupyter notebook containing the main code.
- Data Source: The dataset can be found [here](https://drive.google.com/uc?export=download&confirm=6gh6&id=1VNpyNkGxHdskfdTNRSjjyNa5qC9u0JyV).

**Libraries Used:**
1. pandas
2. scikit-learn
3. NumPy
