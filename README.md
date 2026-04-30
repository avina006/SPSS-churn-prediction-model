📌 Project Overview

This project focuses on building a Customer Churn Prediction model using IBM SPSS Modeler. The goal is to identify customers who are likely to leave (churn) based on their attributes such as credit limit, gender, and other demographic information.

🎯 Objective
Predict customer churn (Yes/No)
Understand factors influencing churn
Support data-driven decision-making
🛠️ Tools & Technologies
IBM SPSS Modeler
Microsoft Excel
📂 Dataset
Source: ACME Customer Data (Excel file)
Contains:
Customer ID
Gender
Credit Limit
Zodiac
Other attributes
⚙️ Project Workflow
1️⃣ Data Import
Imported dataset using Excel Source Node
2️⃣ Data Understanding
Assigned data types using Type Node
3️⃣ Feature Engineering
Created Churn variable using condition:
(CREDITLIMIT < 5000)
4️⃣ Data Cleaning
Handled missing values using Filler Node
5️⃣ Data Partitioning
Split data into:
70% Training
30% Testing
6️⃣ Model Building
Applied Logistic Regression for churn prediction
7️⃣ Model Output
Generated model nugget for predictions
Evaluated results using test data
📊 Key Insights
Customers with lower credit limits are more likely to churn
Predictive modeling helps identify high-risk customers
Data preprocessing plays a crucial role in model accuracy
🧠 Learning Outcomes
Hands-on experience with data preprocessing and modeling
Understanding of logistic regression for classification
Practical exposure to business analytics using SPSS Modeler
📌 Conclusion

The project demonstrates how predictive analytics can transform raw customer data into actionable insights. Businesses can use such models to improve customer retention and make better strategic decisions.

📎 How to Run
Open project in IBM SPSS Modeler
Load the Excel dataset
Execute the stream step-by-step
Run the Logistic Regression model
