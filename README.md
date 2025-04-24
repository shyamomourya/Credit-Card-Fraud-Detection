# Credit-Card-Fraud-Detection
Credit card fraud happens when someone uses a card without the owner’s permission. This project was made to help banks and companies catch those fake transactions.

This project aims to detect fraudulent credit card transactions using machine learning. It uses a dataset with transaction records to build a model that can separate normal transactions from fraud. The main goal is to help banks and businesses reduce financial loss and protect customers from unauthorized payments.
📌 Dataset
The dataset contains records of credit card transactions, with each transaction labeled as fraud or not fraud. Most of the data represents normal transactions, while only a small part is fraud — which makes this a highly imbalanced dataset.
📊 Project Workflow
Data Cleaning:
Removed unnecessary data ("customer name", "customer address", "transaction detail" ) and prepared it for analysis.
Data Analysis:
Explored transaction patterns and relationships between features.
CONVERT OBJECT DATA:
Lavel encoding to convert categorical data into numerical data
Model Building:
Trained and tested multiple machine learning models like:
Logistic Regression
Decision Tree
Random Forest
Model Evaluation:
Compared models using  accuracy_score.
📈 Results
The Random Forest models gave the best results in detecting fraud while keeping false alarms low.
🛠️ Tools and Libraries
Python
Pandas
NumPy
Scikit-learn
Seaborn
Matplotlib
Imbalanced-learn
