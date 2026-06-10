# Medical Insurance Cost Analysis

## Project Overview

This project focuses on analyzing a medical insurance dataset to identify the key factors affecting insurance charges.

The analysis includes data cleaning, preprocessing, exploratory data analysis (EDA), feature engineering, statistical testing, and visualization to uncover meaningful insights from the data.

The primary objective of this project is to understand how factors such as age, BMI, smoking habits, number of children, and region influence medical insurance costs.

---

## Dataset Information

The dataset contains the following features:

| Feature | Description |
|----------|------------|
| age | Age of the individual |
| sex | Gender of the individual |
| bmi | Body Mass Index |
| children | Number of children covered by insurance |
| smoker | Smoking status |
| region | Residential region |
| charges | Medical insurance charges |

---

## Project Workflow

### 1. Data Collection

- Imported dataset using Pandas
- Examined dataset structure
- Checked data types and dimensions

### 2. Data Cleaning

- Checked for missing values
- Removed inconsistencies
- Converted categorical variables into numerical format
- Verified data quality

### 3. Exploratory Data Analysis (EDA)

Performed analysis on:

- Age distribution
- BMI distribution
- Insurance charges distribution
- Gender comparison
- Smoking status impact
- Regional analysis
- Children vs insurance charges

### 4. Feature Engineering

Created additional features such as:

- BMI Categories
    - Underweight
    - Normal
    - Overweight
    - Obese

Performed categorical encoding for machine learning readiness.

### 5. Statistical Analysis

Conducted statistical tests to identify significant relationships between variables and insurance charges.

### 6. Correlation Analysis

Analyzed relationships among numerical features using correlation matrices and visualizations.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- SciPy
- Jupyter Notebook

---

## Key Insights

- Smoking status has the strongest impact on insurance charges.
- Smokers generally incur significantly higher medical expenses.
- Insurance charges tend to increase with age.
- Higher BMI is associated with increased insurance costs.
- Obese individuals generally have higher insurance charges.
- Regional differences have relatively less impact compared to smoking habits and BMI.

---

## Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Statistical Analysis
- Correlation Analysis
- Business Insight Generation

## Future Improvements

- Build predictive machine learning models
- Perform regression analysis
- Compare multiple ML algorithms
- Deploy the model using Streamlit
- Create an interactive dashboard

---

## Conclusion

This project demonstrates an end-to-end data analysis workflow using Python. Through data cleaning, visualization, feature engineering, and statistical analysis, valuable insights were extracted regarding the factors influencing medical insurance costs.

The findings indicate that smoking status, age, and BMI are among the most important factors affecting insurance charges.
