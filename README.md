**Bank Term Deposit Subscription Prediction using Logistic Regression**

A machine learning project that predicts whether a customer will subscribe to a bank term deposit using the Bank Marketing dataset.

---

**Project Overview**

This project develops a Logistic Regression model to classify customers into **Yes** or **No** based on demographic and banking information. The complete workflow includes data exploration, preprocessing, model training, and performance evaluation.

---

**Approach**

A supervised machine learning approach was used to solve this binary classification problem. The dataset was analyzed through Exploratory Data Analysis (EDA), categorical features were encoded using Label Encoding, numerical features were standardized, and a Logistic Regression model was trained to predict customer subscription behavior.

---

**Methodology**

- Loaded and inspected the Bank Marketing dataset.
- Performed Exploratory Data Analysis (EDA).
- Verified missing values and data types.
- Applied Label Encoding to categorical variables.
- Split the dataset into 80% training and 20% testing sets.
- Standardized the feature values using StandardScaler.
- Trained the Logistic Regression model.
- Evaluated performance using Accuracy, Classification Report, Confusion Matrix, and ROC Curve.

---

**Findings**

- The dataset contains **45,211** customer records with **17** features.
- No missing values were found during preprocessing.
- The Logistic Regression model achieved approximately **89% accuracy** on the testing dataset.
- The confusion matrix showed strong classification performance for customer subscription prediction.
- ROC analysis indicated good overall model performance.
