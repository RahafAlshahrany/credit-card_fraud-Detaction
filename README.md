# credit-card_fraud-Detaction 💻
the project is teamwork 👨🏻‍🤝‍👨🏾👭
## 🚧About Project
This is a machine learning project made on Credit Card Fraud Detection. The data is taken from Kaggle. Different classification machine learning algorithms have been applied to get the maximum accuracy.
This fraud detection application is designed to help businesses identify and prevent fraudulent activities. Our system utilizes advanced machine learning algorithms to analyze data in real-time and provide instant insights.
# About Dataset
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
# Dataset Link
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
# Installation Guide for app  ⬇️
## you must save the csv file of dataset with creditcard_fraud.py the app depends on it
# for run the app 
first thing must change Streamlit Theming:
1) open gitbash
2) cd ~/.streamlit
to open the streamlit confg
3) nano config.toml
to change the file theming press cntrol+o and then enter to allowe you wreating
4) copy code below and Paste it on gitbash
   [theme]
primaryColor = "#90CAEB"
backgroundColor = "#00172B"
secondaryBackgroundColor = "#738893"
textColor = "#FFFFFF"
font = "serif"
5) save the changes control +S
6) cntrol +X to exite
7) you will see the Theming
  


   ![image](https://github.com/RahafAlshahrany/credit-card_fraud-Detaction/assets/143160674/189f41db-13d7-418d-b7c7-0e5d5f5e8bdb)
   ![image](https://github.com/RahafAlshahrany/credit-card_fraud-Detaction/assets/143160674/30ff7b5d-bf8d-4e15-bc7c-59fa977cfaae)
![image](https://github.com/RahafAlshahrany/credit-card_fraud-Detaction/assets/143160674/bb5ceaf9-32f1-455b-988b-0ee3cee6455a)
# predacting page 
![image](https://github.com/RahafAlshahrany/credit-card_fraud-Detaction/assets/143160674/4446ec66-7dcd-49b0-83e1-e2d69f9691fe)

 # References 🌟✨
   1) https://docs.streamlit.io/library/advanced-features/theming
   2)    https://docs.kanaries.net/topics/Streamlit/streamlit-theming

   
