# Bank Customer Churn Prediction

Welcome to the **Bank Customer Churn Prediction** project! 🎉 We’re the **Sevens** team, diving into our first experience with the **CRISP-DM** approach to solve a real-world problem: predicting customer churn for a bank.

## Project Overview 🏦

Bank customer churn occurs when customers close their accounts and leave the bank. The goal of this project is to analyze which factors contribute to customer churn and build a predictive model to identify which customers are at risk of leaving.

Using **CRISP-DM** (Cross Industry Standard Process for Data Mining), we’ll go through a structured approach to data analysis and model building, focusing on the six main steps:
1. **Business Understanding** – Why is customer churn important? What does it mean for the bank?
2. **Data Understanding** – What information do we have about our customers? Are there any patterns or interesting trends?
3. **Data Preparation** – Cleaning, transforming, and organizing the data to make it ready for analysis.
4. **Modeling** – Building a predictive model to determine which customers are likely to churn.
5. **Evaluation** – Checking how well our model works and if it accurately predicts churn.
6. **Deployment** – Using the model to make predictions (not covered in this phase).

This is a collaborative learning experience, so we’re learning by doing! 😄

## Dataset 📊

The dataset contains the following columns, representing various customer attributes and churn status:

| Column         | Description                                   |
|----------------|-----------------------------------------------|
| `id`           | Unique record identifier                     |
| `CustomerId`   | Customer's unique identifier                 |
| `Surname`      | Customer’s surname                           |
| `CreditScore`  | Customer's credit score                      |
| `Geography`    | Country where the customer lives             |
| `Gender`       | Customer’s gender                            |
| `Age`          | Customer's age                               |
| `Tenure`       | Number of years the customer has been with the bank |
| `Balance`      | Account balance                              |
| `NumOfProducts`| Number of products held by the customer      |
| `HasCrCard`    | Whether the customer has a credit card (1 = Yes, 0 = No) |
| `IsActiveMember` | Whether the customer is an active member (1 = Yes, 0 = No) |
| `EstimatedSalary` | Estimated annual salary of the customer  |
| `Exited`       | Whether the customer has exited (1 = Yes, 0 = No) |

### Example Records

Here are some sample rows to give you an idea of the data format:

| id | CustomerId | Surname         | CreditScore | Geography | Gender | Age | Tenure | Balance | NumOfProducts | HasCrCard | IsActiveMember | EstimatedSalary | Exited |
|----|------------|-----------------|-------------|-----------|--------|-----|--------|---------|---------------|-----------|----------------|-----------------|--------|
| 0  | 15674932   | Okwudilichukwu  | 668         | France    | Male   | 33  | 3      | 0.0     | 2             | 1.0       | 0.0            | 181449.97       | 0      |
| 1  | 15749177   | Okwudiliolisa   | 627         | France    | Male   | 33  | 1      | 0.0     | 2             | 1.0       | 1.0            | 49503.50        | 0      |
| 2  | 15694510   | Hsueh           | 678         | France    | Male   | 40  | 10     | 0.0     | 2             | 1.0       | 0.0            | 184866.69       | 0      |

## Required Packages 📦

To run this project smoothly, you’ll need to install the following packages:

```python
# Install packages if not already installed
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Packages Overview:
- **pandas**: For data manipulation and analysis.
- **numpy**: Essential for numerical operations.
- **matplotlib & seaborn**: For data visualization to help us better understand our data.
- **scikit-learn**: To build and evaluate our predictive model.

## Project Structure 📂

Here’s how we’re organizing our files:

```plaintext
.
├── data                # Folder containing the dataset files
├── notebooks           # Jupyter Notebooks for data exploration and modeling
├── README.md           # Project overview and documentation (this file!)
└── src                 # Source code for model building and evaluation
```

## CRISP-DM Workflow 🛠️

We’re following CRISP-DM for this project:

1. **Business Understanding**: Understanding why churn is important for customer retention and profitability.
2. **Data Understanding**: Exploring the dataset for trends and patterns.
3. **Data Preparation**: Cleaning and preparing data for analysis.
4. **Modeling**: Trying out different models to predict churn (Logistic Regression, Decision Trees, etc.).
5. **Evaluation**: Testing model accuracy to select the best one.
6. **Deployment**: Not covered in this project but can be an extension in the future.

## Contributing ✨

As a beginner group, we’re learning together! Please feel free to share questions, ideas, or solutions to any issues you run into. Collaboration is key!

Let’s make this project awesome, one line of code at a time! 😄