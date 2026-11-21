# credit-card-default-prediction
A Machine Learning project that predicts credit card payment defaults using customer demographic and financial data. Includes data preprocessing, exploratory data analysis, feature selection, and classification models using Python and Scikit-learn.
#  Credit Card Default Prediction Using Machine Learning

##  Project Overview

This project focuses on predicting whether a credit card customer is likely to default on their next month's payment using Machine Learning techniques.

The project analyzes customer demographic and financial information to identify patterns associated with credit card payment defaults.

##  Objectives

- Understand and explore credit card customer data.
- Perform data cleaning and preprocessing.
- Conduct Exploratory Data Analysis (EDA).
- Visualize customer payment and financial patterns.
- Identify and handle outliers using the IQR method.
- Select relevant features for prediction.
- Build and evaluate Machine Learning classification models.

##  Dataset Description

The project uses a Credit Card Default dataset containing customer demographic, repayment, bill, and payment information.

**Important Features:**

- ID – Customer identification number.
- LIMIT_BAL – Amount of given credit.
- SEX – Gender.
- EDUCATION – Education level.
- MARRIAGE – Marital status.
- AGE – Customer age.
- PAY_0 to PAY_6 – Previous payment status.
- BILL_AMT1 to BILL_AMT6 – Monthly bill amounts.
- PAY_AMT1 to PAY_AMT6 – Previous payment amounts.

**Target Variable:** `default payment next month`

Target classes:

- `0` – No default.
- `1` – Default.

##  Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

##  Project Workflow

1. **Data Loading:** Import the dataset using Pandas.
2. **Data Understanding:** Examine the dataset structure, columns, data types, and statistical summaries.
3. **Data Cleaning:** Handle missing values, duplicates, and inconsistent data.
4. **Exploratory Data Analysis:** Explore customer demographics, repayment patterns, and default distribution.
5. **Data Visualization:** Create box plots, histograms, count plots, and correlation heatmaps.
6. **Outlier Handling:** Identify and cap outliers using the Interquartile Range (IQR) method.
7. **Feature Selection:** Identify important features using SelectKBest and statistical techniques.
8. **Data Splitting:** Divide the dataset into training and testing sets.
9. **Model Building:** Train classification algorithms.
10. **Model Evaluation:** Compare model performance using evaluation metrics.

##  Machine Learning Algorithms

The following classification algorithms are explored:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

##  Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score

These metrics help compare the performance of the classification algorithms.

##  Installation

Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn xlrd
```

##  How to Run the Project

1. Clone this repository:

```bash
git clone https://github.com/your-username/credit-card-default-prediction.git
```

2. Navigate to the project folder.

3. Install the required libraries.

4. Place the dataset file in the project directory.

5. Launch Jupyter Notebook:

```bash
jupyter notebook
```

6. Open the project notebook and run all cells.

##  Project Structure

```text
credit-card-default-prediction/
│
├── credit card project.ipynb
├── credit card.xls
└── README.md
```

*Update the filenames if your actual files have different names.*

##  Future Improvements

- Experiment with additional classification algorithms.
- Apply hyperparameter tuning.
- Improve model performance through feature engineering.
- Evaluate models using confusion matrices and ROC-AUC.
- Develop a web application for credit card default prediction.

##  Author

**Vishwani G**

B.Sc. Computer Science with Artificial Intelligence Student

Interested in Artificial Intelligence, Machine Learning, and Data Science.

---

⭐ Thank you for visiting this project!
