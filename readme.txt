# Scam Detection in the Banking Sector Using ML and DL

This project focuses on detecting financial scams in banking transactions using both Machine Learning (ML) and Deep Learning (DL) techniques. It includes a comparison of several ML algorithms and DL models based on performance metrics like accuracy, precision, recall, and F1 score.

---

## Dataset: `enhanced_scam_detection_dataset.csv`

### Columns Included:
- Customer_ID: Unique customer identifier
- Age, Gender, Account_Type, Credit_Score: Customer demographic and profile details
- Transaction_Amount, Transaction_Mode, Transaction_Type: Transaction-specific features
- Is_New_Device, Unusual_Pattern, Location, Transaction_Hour: Contextual features
- OTP_Failed_Attempts, Velocity_Transaction_Count, Past_Scam_Count: Behavioral indicators
- Scam_Type: Type of scam (e.g., Phishing, Identity Theft, etc.)
- Is_Scam: Target variable (1 = Scam, 0 = Legitimate)

---

## Models Implemented

### Machine Learning Models:
- Logistic Regression
- Decision Tree
- Random Forest

### Deep Learning Models:
- Feedforward Neural Network
- Recurrent Neural Network (RNN)

---

## Setup Instructions

Install required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn tensorflow keras
 