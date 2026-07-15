 🏦 Loan Prediction Using Random Forest

 📌 Project Overview

This project uses Machine Learning to predict whether a loan application will be approved or rejected based on applicant information. The model is built using the Random Forest Classifier and trained on historical loan application data.

The objective of this project is to automate the loan approval prediction process by analyzing applicant details such as income, education, employment status, credit history, loan amount, and property area.

---

 📊 Dataset

The dataset contains loan applicant information including:

- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area
- Loan_Status (Target Variable)

📂 Dataset File:

-> `loan.csv`

---

🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Google Colab


 🤖 Machine Learning Workflow

 📥 Data Collection
- Loaded the loan dataset.

 🧹 Data Preprocessing
- Removed unnecessary columns.
- Handled missing values.
- Cleaned and prepared the dataset.
⚙️ Feature Engineering
- Converted categorical variables using Label Encoding.

 🚀 Model Training
- Split the dataset into training and testing sets.
- Trained a Random Forest Classifier.

 📈 Model Evaluation
The model was evaluated using:
- Accuracy Score
- Classification Report
- Confusion Matrix

💾 Model Saving
- Saved the trained model using Joblib.


 🎯 Model Performance

| Metric | Value |
|----------|----------|
| Algorithm | Random Forest Classifier |
| Accuracy | **75.61%** |



📂 Project Files

|       File Name           |                Description                |
|-------------------------- |-------------------------------------------|
| Loan_Prediction.ipynb     | Complete Machine Learning Notebook        |
| loan.csv                  | Dataset                                   |
| loan_prediction_model.pkl | Trained Random Forest Model               |
| README.md                 | Project Documentation                     |
| requirements.txt          | Required Python Libraries                 |


 🔍 Model Output

The model predicts:

 ✅ Loan Approved

 ❌ Loan Rejected



⚡ Installation
 Clone Repository

```bash
git clone https://github.com/komal-thummar/Loan-Prediction-Using-Random-Forest.git
```


# Run Notebook

bash
Loan_Prediction.ipynb


🔮 Future Enhancements

- Hyperparameter Tuning
- Feature Engineering
- Streamlit Web Application
- Flask Deployment
- Model Comparison with Other Machine Learning Algorithms



 👩‍💻 Author

**Komal Thummar**

Machine Learning Project using Random Forest Classifier.



 📜 License

This project is developed for educational and learning purposes.

⭐ If you found this project useful, consider giving it a star on GitHub.