###### **📌 Customer Churn Prediction – Telco Dataset**



This project uses the Telco Customer Churn dataset from Kaggle to build machine learning models that predict whether a customer will churn (leave the company) or stay.

By analyzing customer demographics, contract details, and service usage patterns, telecom companies can take proactive steps to reduce churn, improve customer satisfaction, and increase revenue.



**🚀 Project Workflow**

###### 

1. **Data Loading \& Exploration**



* &nbsp;		Loaded the dataset (Telco-Customer-Churn.csv)



* &nbsp;		Checked for missing values, data types, and overall dataset shape



**2. Data Preprocessing**



* &nbsp;	Dropped customerID (not useful for prediction)



* &nbsp;	Converted TotalCharges to numeric and handled missing values



* &nbsp;	Encoded categorical variables using Label Encoding



* &nbsp;	Scaled numerical features using StandardScaler



* &nbsp;	Final dataset prepared with features (X) and target (y)



**3. Train-Test Split**



* &nbsp;	Split data into 80% training and 20% testing sets



* &nbsp;	Used stratify=y to maintain class balance



**4. Model Training**



* &nbsp;	Random Forest Classifier



* &nbsp;	XGBoost Classifier



**5. Model Evaluation**



* &nbsp;	Accuracy, ROC-AUC score, and classification report



* &nbsp;	Confusion matrix visualization



**6. Feature Importance**



* &nbsp;	Identified top factors driving churn using Random Forest \& XGBoost



* &nbsp;	Visualized most important features







**📂 Project Structure** 



**📁 Customer-Churn-Prediction**

**│── 📄 Telco-Customer-Churn.csv # Dataset**

**│── 📓 Churn\_Prediction.ipynb # Main Jupyter Notebook (project code)**

**│── 📄 README.md # Project documentation**

**│── 📄 requirements.txt # Dependencies**









**📊 Results**



* Both Random Forest and XGBoost performed well in predicting churn.



* Key drivers of churn included:



* &nbsp;	Contract type (month-to-month contracts had higher churn)



* &nbsp;	Monthly charges



* &nbsp;	Tenure (shorter-tenure customers were more likely to churn)



* &nbsp;	Internet service type







**🛠️ Tech Stack**



* **Python** (Pandas, NumPy, Matplotlib, Seaborn)



* **Scikit-learn** (preprocessing, train-test split, Random Forest, evaluation metrics)



* **XGBoost** (boosted tree classifier)







📂 Dataset



Dataset: https://www.kaggle.com/datasets/blastchar/telco-customer-churn







**📌 How to Run**



&nbsp;	1. Clone this repository:

&nbsp;		git clone https://github.com/MaanasiS/customer-churn-prediction.git

&nbsp;		cd customer-churn-prediction



&nbsp;	2. Install dependencies:

&nbsp;		pip install -r requirements.txt

&nbsp;	

&nbsp;	3. Run the Jupyter Notebook to train and evaluate models.





**📈 Future Improvements**



&nbsp;	1. Test more advanced models (Logistic Regression, Neural Networks)



&nbsp;	2. Perform hyperparameter tuning for Random Forest \& XGBoost



&nbsp;	3. Deploy as a web app (Flask/Streamlit) for real-time predictions





**✅ Requirements**



&nbsp;	The project requires the following Python libraries (included in requirements.txt):



* &nbsp;		pandas



* &nbsp;		numpy



* &nbsp;		matplotlib



* &nbsp;		seaborn



* &nbsp;		scikit-learn



* &nbsp;		xgboost



* &nbsp;		jupyter notebook / jupyterlab





**🏆 Conclusion**



&nbsp;	1. This project demonstrates how machine learning can predict customer churn and provide actionable insights for businesses.

&nbsp;	2. With proactive retention strategies, telecom companies can reduce churn, cut costs, and improve customer loyalty.





**💼 Business Impact**



&nbsp;	1. Churn prediction helps businesses identify customers at risk of leaving.



&nbsp;	2. Companies can offer discounts, personalized services, or loyalty programs to these customers.



&nbsp;	3. This leads to higher retention rates, better revenue, and stronger customer relationships.



