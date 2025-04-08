# 🚀 Loan Approval Prediction using Machine Learning

## 📌 Overview
This project develops a predictive model to determine the likelihood of loan approval for applicants based on various financial and demographic factors. Using machine learning techniques, the model aids financial institutions in making informed loan approval decisions, enhancing both the speed and accuracy of their evaluation processes.

## 🎯 Objective
The primary goal of this project is to automate the loan approval process, reduce human error, and provide a systematic approach to handle loan applications more efficiently and effectively.

## 🗂 Dataset Description
The dataset used in this project includes details such as Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, and others. It consists of 614 total entries with several features that influence the loan approval decision.

## 💻 Technologies Used
- **Python**: For implementing machine learning algorithms.
- **Pandas & NumPy**: For data manipulation and numerical computation.
- **Matplotlib & Seaborn**: For data visualization.
- **Scikit-Learn**: For model building and validation.

## 🛠 Features
The dataset includes the following features to train the model:
- `Gender`: Male or Female 🚹🚺
- `Married`: Applicant married (Yes/No) 💍
- `Dependents`: Number of dependents 👨‍👩‍👧‍👦
- `Education`: Applicant Education (Graduate/Under Graduate) 🎓
- `Self_Employed`: Self employed (Yes/No) 💼
- `ApplicantIncome`: Income of the applicant 💵
- `CoapplicantIncome`: Income of the co-applicant 💵
- `LoanAmount`: Loan amount in thousands 💰
- `Loan_Amount_Term`: Term of loan in months ⏳
- `Credit_History`: credit history meets guidelines ✅
- `Property_Area`: Urban/ Semi Urban/ Rural 🏙️🌄

## 🧠 Model Training
Multiple machine learning models were trained to predict the loan approval status, including:
- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machine (SVM)**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **Naive Bayes** which provided an accuracy of **84%**, demonstrating its effectiveness in handling this dataset.

The Random Forest Classifier, however, provided the best results, standing out as the most reliable model with an accuracy of approximately 77.27% and a cross-validation score of around 80.95%.

## 📊 Results
The Naive Bayes model achieved an accuracy of **84%**, highlighting its suitability for datasets with clear distributions of features. The Random Forest Classifier, with its ensemble approach, provided the highest overall reliability.

## 🚀 Usage
To run this project, you will need to install the required libraries mentioned above. Clone this repository, navigate to the project directory, and run the Python notebooks.

## 🤝 Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request with your updates.

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.
