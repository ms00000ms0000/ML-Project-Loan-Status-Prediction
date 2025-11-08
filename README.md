# 🏦 Loan Status Prediction System — Machine Learning Model  

## 📘 Project Description  
The **Loan Status Prediction System** is a **Machine Learning project** designed to predict whether a **loan application** will be **approved or rejected** based on applicant information.  

The model utilizes **Support Vector Machine (SVM) with a Linear Kernel** to classify applications efficiently and achieved an **accuracy of 79%** on test data.  

A detailed **Exploratory Data Analysis (EDA)** was performed to explore trends and relationships among applicant attributes such as **Gender, Marital Status, Dependents, Education, Employment Type, Income, Loan Amount, Credit History, and Property Area**.  

This project demonstrates how **ML-based automation** can make **loan approval systems faster, fairer, and more data-driven**, reducing manual bias in financial institutions.  

---

## 🔍 About the Project  
This project automates the **loan eligibility assessment process** by analyzing applicant details through predictive modeling.  
By applying **SVM with a linear kernel**, it provides accurate binary classification results (Approved / Not Approved), empowering banks and fintech systems to make **data-backed lending decisions**.  

---

## 🧠 Model Architecture  
The project uses a **Support Vector Machine (SVM)** model — ideal for handling classification problems with both numerical and categorical data efficiently.  

* **Algorithm:** Support Vector Machine (Linear Kernel)  
* **Problem Type:** Binary Classification  
* **Evaluation Metric:** Accuracy Score  

---

## 🧾 Dataset Description  
The dataset includes demographic, financial, and credit-related information about loan applicants.  

| Feature Name          | Description |
| :--------------------- | :------------------------------------------------------------- |
| `Gender`               | Applicant’s gender (Male/Female) |
| `Married`              | Marital status of the applicant |
| `Dependents`           | Number of dependents |
| `Education`            | Education level (Graduate/Not Graduate) |
| `Self_Employed`        | Employment type |
| `ApplicantIncome`      | Applicant’s income |
| `CoapplicantIncome`    | Co-applicant’s income |
| `LoanAmount`           | Requested loan amount |
| `Loan_Amount_Term`     | Duration of the loan (in months) |
| `Credit_History`       | Credit record (1 = good, 0 = bad) |
| `Property_Area`        | Urban/Rural/Semiurban |
| `Loan_Status`          | Target variable — Approved (Y) or Not Approved (N) |

---

## ⚙️ Tech Stack & Libraries  

**Language:**  
* Python 🐍  

**Libraries:**  
* **NumPy** – Numerical computation  
* **Pandas** – Data handling and manipulation  
* **Scikit-learn** – Model building and performance evaluation  
* **Matplotlib / Seaborn** – Data visualization and EDA  

---

## 🚀 Features  
* ✅ **Loan Approval Prediction** — Classifies applications as approved or not approved  
* 📊 **Comprehensive EDA** — Identifies key trends and correlations  
* ⚙️ **Algorithm Used** — SVM (Linear Kernel) for high interpretability  
* 📈 **Model Performance** — Achieved **79% accuracy** on the test dataset  
* 💡 **Real-World Value** — Accelerates loan processing and minimizes human bias  

---

## 📊 Results  
The **Support Vector Machine (Linear Kernel)** achieved a **79% accuracy**, making it a reliable model for automating loan application assessments in banking environments.  

---

## 📁 Repository Structure  

```
📦 ML_Project_Loan_Status_Prediction
│
├── loan_status_prediction.ipynb # Complete Jupyter Notebook
├── loan_data.csv # Dataset used for model training
└── README.md # Project documentation

```
---

## 🧪 How to Run  

1. **Clone the repository:**  
   ```bash
   git clone https://github.com/ms00000ms0000/ML-Project-Loan-Status-Prediction.git
   cd ML-Project-Loan-Status-Prediction
   ```

2. **Install dependencies:**
  ```bash
  pip install -r requirements.txt
  ```

3. **Run the Jupyter Notebook:**

  ```bash
  jupyter notebook loan_status_prediction.ipynb
  ```

4. **Execute all cells to train, test, and evaluate the model.**

---

## 📈 Future Improvements

* Integrate deep learning models (ANN) for enhanced prediction accuracy

* Add a web-based dashboard for loan officers to test applications interactively

* Implement automated credit score analysis for richer data insights

---

## 👨‍💻 Developer

Developed by: Mayank Srivastava
