💰 AI-Powered Personal Finance Advisor
An end-to-end Machine Learning–based Personal Finance Advisor that analyzes user income and spending behavior, predicts savings, segments users into financial profiles, and provides personalized financial advice.
📌 Project Overview
Managing personal finances effectively is challenging due to varying income levels, expenses, and financial goals.
This project leverages Machine Learning to:
Analyze financial data
Predict future savings
Segment users based on spending behavior
Provide actionable financial advice
The system is designed as a modular, scalable ML pipeline following industry best practices.
🎯 Objectives
Understand user income and expense patterns
Predict monthly savings using regression models
Segment users using clustering techniques
Generate personalized financial recommendations
Provide visual insights for better decision-making
🧠 Machine Learning Techniques Used
Task
Technique
Data Cleaning
Pandas, NumPy
Feature Engineering
Financial Ratios
Savings Prediction
Random Forest Regressor
User Segmentation
K-Means Clustering
Evaluation
MAE, RMSE, R²
Visualization
Matplotlib, Seaborn
📂 Project Structure
Copy code

AI-Powered_Personal_Finance_Advisor/
│
├── data/
│   └── financial_data.csv
│
├── notebooks/
│   ├── 01_data_preprocessing.ipynb
│   ├── 02_feature_engineering.ipynb
│   ├── 03_train_regression.ipynb
│   ├── 04_train_clustering.ipynb
│   ├── 05_model_evaluation.ipynb
│   └── 06_advisor.ipynb
│
├── outputs/
│   ├── models/
│   ├── figures/
│   └── insights/
│
├── reports/
│   └── final_report.pdf
│
├── requirements.txt


🔧 Feature Engineering
Key financial indicators created:
Expense Ratio = Total Expenses / Income
Savings Ratio = Savings / Income
Dependency Burden = Dependents / Age
These features significantly improve model performance.
📊 Model Performance
🔹 Regression (Savings Prediction)
R² Score: High predictive accuracy
MAE & RMSE used for error measurement
🔹 Clustering (User Segmentation)
Groups users into:
Overspenders
Balanced spenders
High savers
💡 Personalized Financial Advice
Based on:
Savings ratio
Cluster assignment
Example:
Low savings → Budget optimization advice
High savings → Investment recommendations
🚀 How to Run the Project
1️⃣ Install dependencies
Bash
Copy code
pip install -r requirements.txt
2️⃣ Run notebooks (recommended order)
Copy code

01 → 02 → 03 → 04 → 05 → 06
3️⃣ Or run main script
Bash
Copy code
python main.py
🛠 Tools & Technologies
Python
Pandas, NumPy
Scikit-Learn
Matplotlib, Seaborn
Jupyter Notebook
Git & GitHub
🎓 Academic Use
This project was developed as a Final Year Machine Learning Project and demonstrates:
End-to-end ML workflow
Clean modular design
Practical real-world application
Industry-style project structuring
📌 Future Enhancements
Real-time expense tracking
Deep Learning–based prediction
Mobile/Web application integration
Personalized investment planning
👩‍💻 Author
Anusha Kattanguru
Final Year Student – Machine Learning & AI
⭐ Acknowledgements
Scikit-Learn Documentation
Kaggle Datasets
Faculty Mentors
