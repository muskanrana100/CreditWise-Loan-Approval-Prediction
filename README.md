# 💳 CreditWise – Loan Approval Prediction

### Machine Learning | Python | Scikit-learn | Data Analysis

A Machine Learning project that analyzes applicant information and predicts loan approval using classification algorithms. This project explores the complete machine learning workflow, from data understanding and preprocessing to model training, comparison, and performance evaluation.

---

## 📌 Project Overview

Loan approval decisions depend on several factors, including an applicant's income, credit score, employment status, savings, and financial background.

**CreditWise** explores how machine learning can identify patterns in applicant data and predict loan approval outcomes.

The project focuses on understanding the dataset, preparing meaningful features, training multiple classification models, and evaluating their performance using appropriate metrics.

## 🎯 Project Objectives

- Understand and analyze loan applicant data.
- Perform Exploratory Data Analysis (EDA).
- Handle missing values and prepare data for machine learning.
- Apply feature encoding and feature scaling.
- Train and compare multiple classification algorithms.
- Evaluate model performance using different metrics.
- Understand how machine learning supports data-driven predictions.

## 🛠️ Technologies & Libraries

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Jupyter Notebook | Development environment |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine learning and evaluation |

## 🧠 Machine Learning Concepts Implemented

### 1. Data Understanding & Exploration

- Dataset inspection using `head()`, `info()` and `describe()`.
- Data types and statistical summaries.
- Missing-value analysis.
- Target variable distribution and class balance.
- Categorical and numerical feature analysis.

### 2. Exploratory Data Analysis (EDA)

- Distribution plots and histograms.
- Count plots and bar charts.
- Box plots for numerical feature analysis.
- Correlation heatmap.
- Analysis of relationships between applicant features and loan approval.

### 3. Data Preprocessing

- Separation of independent and dependent variables.
- Removal of unnecessary identifier columns.
- Handling missing numerical values using median imputation.
- Handling missing categorical values using most-frequent imputation.
- Label Encoding for the target variable.
- One-Hot Encoding for categorical features.
- Feature scaling using StandardScaler.
- Train-test splitting with stratification.

### 4. Machine Learning Algorithms

Three classification algorithms were implemented and compared:

- **Logistic Regression:** A classification algorithm used to estimate the probability of loan approval.
- **K-Nearest Neighbors (KNN):** Classifies an applicant based on the labels of nearby data points.
- **Gaussian Naive Bayes:** Uses Bayes' theorem with a Gaussian distribution assumption for numerical features.

### 5. Feature Engineering

Additional features were created to explore whether transformations could improve model performance:

- Squared DTI Ratio (`DTI_Ratio_sq`).
- Squared Credit Score (`Credit_Score_sq`).
- Log-transformed Applicant Income (`Applicant_Income_log`).

The engineered features were evaluated against the baseline feature set.

### 6. Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

### 7. Machine Learning Pipeline

Scikit-learn tools were used to organize preprocessing and model training:

- `Pipeline`
- `ColumnTransformer`
- `SimpleImputer`
- `StandardScaler`
- `OneHotEncoder`
- `train_test_split`

This approach helps keep preprocessing consistent between training and testing data and reduces data leakage.

---

## 🔄 Project Workflow

1. Dataset collection and loading
2. Data inspection and understanding
3. Exploratory Data Analysis
4. Missing-value analysis
5. Feature and target separation
6. Train-test splitting
7. Data preprocessing and encoding
8. Model training
9. Model performance evaluation
10. Feature engineering
11. Final model comparison and observations

---

## 📊 Models Compared

| Model | Type |
|---|---|
| Logistic Regression | Linear Classification |
| K-Nearest Neighbors | Distance-Based Classification |
| Gaussian Naive Bayes | Probabilistic Classification |

The models were compared using multiple evaluation metrics rather than relying on accuracy alone.

## 📁 Repository Structure

```text
CreditWise-Loan-Approval-Prediction/
│
├── CreditWiseLoan_Improved.ipynb
│
└── README.md
```

**Note:** The dataset is not included in this repository.

## ▶️ How to Run the Project

1. Clone this repository:

```bash
git clone https://github.com/muskanrana100/CreditWise-Loan-Approval-Prediction.git
```

2. Navigate to the project directory:

```bash
cd CreditWise-Loan-Approval-Prediction
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

4. Place the required dataset file (`loan_approval_data.csv`) in the location expected by the notebook.

5. Launch Jupyter Notebook:

```bash
jupyter notebook
```

6. Open `CreditWiseLoan_Improved.ipynb` and run the cells sequentially.

## 📚 Key Learnings

Through this project, I gained practical experience in:

- Understanding and exploring real-world structured datasets.
- Preparing raw data for machine learning.
- Applying different encoding and scaling techniques.
- Building machine learning pipelines.
- Training and comparing classification algorithms.
- Understanding evaluation metrics beyond accuracy.
- Applying feature engineering to improve model representation.
- Understanding the importance of avoiding data leakage.

Most importantly, this project helped me understand that building a machine learning model is not just about fitting an algorithm. It involves understanding the data, selecting appropriate preprocessing techniques, validating results, and interpreting model performance.

## 🚀 Future Improvements

- Experiment with additional classification algorithms.
- Perform hyperparameter tuning.
- Apply explainable AI techniques such as SHAP.
- Investigate feature importance and model interpretability.
- Evaluate fairness and potential bias in loan approval predictions.
- Develop an interactive application for predictions.

## ⚠️ Disclaimer

This project is developed for educational and learning purposes. Its predictions should not be used as the basis for actual financial or loan approval decisions.

## 👩‍💻 Author

**Muskan Rana**

B.Tech Computer Science & Engineering (Artificial Intelligence)

Aspiring AI Engineer | Machine Learning | Generative AI

- GitHub: [@muskanrana100](https://github.com/muskanrana100)

---

⭐ If you find this project interesting, feel free to explore the notebook and share your feedback!

**Always Learning. Always Building. Always Improving.**
