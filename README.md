** Fraud Detection System using Machine Learning(Logistic Regression) **
This project focuses on detecting fraudulent financial transactions using machine learning techniques. It involves large-scale data analysis, feature engineering, and building a classification model using Scikit-learn. The dataset contains over 6 million transaction records, and the model is trained to identify fraud patterns with high recall.

**What I Did**
- Loaded and analyzed a dataset with 6 million+ transactions
- Checked data (no missing values, very few fraud cases)
- Created graphs to understand data (bar chart, histogram, heatmap)
- Created new features like balance difference
- Found that fraud mostly happens in TRANSFER and CASH_OUT
- Built a machine learning model using Logistic Regression
- Handled imbalanced data using class_weight='balanced'
- Evaluated model using accuracy, precision, recall
- Got around 94% accuracy and high fraud detection rate
- Saved the model using joblib
- Deployes on Streamlit
