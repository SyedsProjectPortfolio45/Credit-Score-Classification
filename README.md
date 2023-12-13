# Credit-Score-Classification📈📊

#### Tools used🛠: Python, NumPy, Pandas, Machine Learning, Plotly
🔗dataset link --> https://statso.io/credit-score-classification-case-study/

## 🚧You see the detailed code with visualizations by clicking on the Google Colab logo when you open the ipynb file

# Description
Banks and credit card companies calculate your credit score to determine your creditworthiness. It helps banks and credit card companies immediately to issue loans to customers with good creditworthiness. Today banks and credit card companies use Machine Learning algorithms to classify all the customers in their database based on their credit history.

There are three credit scores that banks and credit card companies use to label their customers:
- Good
- Standard
- Poor

A person with a good credit score will get loans from any bank and financial institution.

## Step-by-step approach
- Imported necessary Python libraries and Dataset
- Checked for null values
- Performed **EDA**
- Conducted Data Exploration by visualizing **box-plots** of credit scores based on occupation, annual salary, monthly inhand salary, number of bank accounts, number of credit cards, average interest rates, number of loans taken, days delayed for credit card payments, number of delayed payments, number of outstanding debt, credit utilization ratio, credit history age, total number of EMI's per month, amount invested monthly, monthly balance left.
- Created a Credit Mix column categorically by transforming it into numerical feature so that we can use it to train a Machine Learning model for the task of credit score classification
- Split the data into training and test sets and proceed further by training a credit score classification model using **RandomForestClassifier**
- Now, let’s make predictions from our model by giving inputs to our model according to the features we used to train the model
