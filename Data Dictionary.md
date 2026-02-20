# Week 18 - Datasets Dictionary

Information on all the datasets required for completing the Week 18 assignments on Classification Algorithms (Decision Trees and Random Forests).

## Folder Structure

```
Week-18 (Classification-2)/
│
├── Task-Datasets/
│   ├── task1_decision_tree_customer_data.csv
│   └── task2_random_forest_customer_data.csv
│
├── Assignment-Dataset/
│   ├── assignment1_decision_tree_optimization.csv
│   ├── assignment2_random_forest_optimization.csv
│   └── assignment3_classifier_comparison.csv
│
└── Assessment-Dataset/
    └── employee_attrition_prediction.csv
```


## Task Datasets

### 1. task1_decision_tree_customer_data.csv
**Purpose**: Practice implementing Decision Tree classification for customer purchase prediction

**Columns**:
- `Customer_ID` (numeric): Unique customer identifier
- `Age` (numeric): Customer age (18-65)
- `Salary` (numeric): Annual salary in dollars ($15,000-$150,000)
- `Purchased` (binary): Whether customer purchased the product (0=No, 1=Yes)

**Records**: 100 rows  

---

### 2. task2_random_forest_customer_data.csv
**Purpose**: Practice implementing Random Forest classification

**Columns**:
- `Customer_ID` (numeric): Unique customer identifier
- `Age` (numeric): Customer age (18-65)
- `Salary` (numeric): Annual salary in dollars ($15,000-$150,000)
- `Purchased` (binary): Whether customer purchased the product (0=No, 1=Yes)

**Records**: 120 rows  

---

## Assignment Datasets

### 1. assignment1_decision_tree_optimization.csv
**Purpose**: Practice hyperparameter tuning for Decision Trees (max_depth, min_samples_split, criterion)

**Columns**:
- `Customer_ID` (numeric): Unique identifier
- `Age` (numeric): Customer age (20-70)
- `Annual_Income` (numeric): Annual income in thousands ($20K-$200K)
- `Spending_Score` (numeric): Customer spending behavior score (1-100)
- `Years_as_Customer` (numeric): Years since first purchase (0-20)
- `Online_Purchase_Frequency` (numeric): Monthly online purchases (0-30)
- `Will_Churn` (binary): Customer churn prediction (0=Stay, 1=Churn)

**Records**: 250 rows  

---

### 2. assignment2_random_forest_optimization.csv
**Purpose**: Optimize Random Forest hyperparameters (n_estimators, max_depth, criterion)

**Columns**:
- `Transaction_ID` (numeric): Unique transaction identifier
- `Amount` (numeric): Transaction amount ($10-$5000)
- `Time_of_Day` (numeric): Hour of transaction (0-23)
- `Day_of_Week` (numeric): Day of week (0=Monday to 6=Sunday)
- `Customer_Age` (numeric): Customer age (18-80)
- `Account_Age_Days` (numeric): Days since account creation (1-3650)
- `Previous_Transactions` (numeric): Number of previous transactions (0-500)
- `Is_Fraud` (binary): Fraudulent transaction indicator (0=Legitimate, 1=Fraud)

**Records**: 300 rows  

---

### 3. assignment3_classifier_comparison.csv
**Purpose**: Compare Decision Tree vs Random Forest on the same dataset

**Columns**:
- `Patient_ID` (numeric): Unique patient identifier
- `Age` (numeric): Patient age (25-85)
- `BMI` (numeric): Body Mass Index (18-45)
- `Blood_Pressure` (numeric): Systolic blood pressure (90-180)
- `Glucose_Level` (numeric): Fasting glucose (70-200)
- `Insulin_Level` (numeric): Insulin level (10-300)
- `Family_History` (binary): Family history of diabetes (0=No, 1=Yes)
- `Physical_Activity` (categorical): Low, Medium, High
- `Diabetes_Risk` (binary): Risk of diabetes (0=Low Risk, 1=High Risk)

**Records**: 350 rows  

---

## Assessment Dataset

### employee_attrition_prediction.csv
**Purpose**: End-to-end classification project using Decision Trees and Random Forests

**Columns**:
- `Employee_ID` (numeric): Unique employee identifier
- `Age` (numeric): Employee age (22-60)
- `Gender` (categorical): Male, Female
- `Education_Level` (categorical): High School, Bachelor, Master, PhD
- `Department` (categorical): Sales, IT, HR, Finance, Marketing, Operations
- `Job_Role` (categorical): Entry, Mid, Senior, Manager
- `Years_at_Company` (numeric): Years employed (0-30)
- `Monthly_Income` (numeric): Monthly salary ($2000-$20000)
- `Distance_from_Home` (numeric): Distance in km (1-50)
- `Work_Life_Balance` (numeric): Rating 1-4 (1=Poor, 4=Excellent)
- `Job_Satisfaction` (numeric): Rating 1-4 (1=Low, 4=High)
- `Performance_Rating` (numeric): Rating 1-4 (1=Low, 4=Outstanding)
- `Overtime` (binary): Works overtime regularly (0=No, 1=Yes)
- `Stock_Option_Level` (numeric): Stock option level (0-3)
- `Training_Hours_Last_Year` (numeric): Training hours (0-100)
- `Left_Company` (binary): Employee left (0=Stayed, 1=Left)

**Records**: 500 rows  
