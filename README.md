# Predicting Academic Risk in College Students Using Enrollment and Performance Data

An end-to-end data science project using **Python, College Scorecard, and IPEDS data** to analyze institutional characteristics associated with student outcomes and build predictive models for graduation performance.

## Project Documentation

- [Full Project Report](Kedeesh_Nolan_Academic_Risk_Prediction_Report.pdf)
- [Final Presentation](Kedeesh_Nolan_Academic_Risk_Prediction_Presentation.pdf)


## Project Overview

Student success and degree completion are important measures of institutional performance in higher education. This project explores how enrollment characteristics, institutional attributes, financial indicators, and student outcome measures can be used to analyze patterns associated with graduation performance.

Using data from the **U.S. Department of Education College Scorecard and Integrated Postsecondary Education Data System (IPEDS)**, I developed a structured data science workflow that moved from large-scale raw data preparation and integration to exploratory analysis, feature engineering, predictive modeling, model evaluation, and interpretation.

The analysis focused on institutions in **New York State** and used `UNITID` to integrate information across the two federal higher-education datasets.

## Business & Research Objective

The primary objectives were to:

- Integrate College Scorecard and IPEDS data into a unified analytical dataset.
- Identify institutional and enrollment characteristics associated with graduation outcomes.
- Prepare and transform large higher-education datasets for predictive analysis.
- Engineer a classification target representing higher graduation performance.
- Develop and compare supervised machine-learning models.
- Evaluate model performance and interpret factors associated with student success.
- Demonstrate how educational data can support earlier, more informed institutional decision-making.

## Data Sources

The project uses two public higher-education datasets from the **U.S. Department of Education**:

### College Scorecard

The original College Scorecard dataset contained approximately:

- **6,429 institutions**
- **3,306 variables**
- Institutional characteristics
- Enrollment information
- Cost and financial measures
- Student outcomes and completion indicators

### IPEDS

The Integrated Postsecondary Education Data System dataset contained approximately:

- **307,707 records**
- **64 variables**
- Enrollment characteristics
- Institutional information
- Student demographic measures
- Academic and performance-related data

The datasets were filtered and prepared for analysis, with the project focusing on institutions located in **New York**.

## Data Preparation & Integration

The raw datasets required substantial preparation before modeling.

Key preprocessing steps included:

- Loading and inspecting large College Scorecard and IPEDS datasets
- Filtering records to the relevant institutional population
- Selecting variables appropriate for the research objective
- Handling missing and incomplete values
- Standardizing fields across data sources
- Merging College Scorecard and IPEDS data using `UNITID`
- Removing unnecessary or redundant variables
- Preparing numerical and categorical features for machine learning
- Validating the final analytical dataset before modeling

A binary target variable, `High_Grad_Rate`, was engineered to support classification modeling of graduation performance.

## Exploratory Data Analysis

Exploratory analysis was used to better understand the structure of the data and identify patterns related to institutional performance.

The analysis examined:

- Graduation and completion outcomes
- Enrollment characteristics
- Institutional attributes
- Financial and cost-related measures
- Relationships among predictive features
- Distribution and quality of the modeling variables

Visualizations and summary statistics were used throughout the analysis to support feature selection and interpretation.

## Modeling Approach

Two supervised-learning classification models were developed using **scikit-learn**:

### Decision Tree Classifier

A Decision Tree model was used to capture nonlinear relationships and provide an interpretable view of how institutional characteristics contribute to graduation-performance classification.

### Logistic Regression

A Logistic Regression model was developed as a statistical classification approach for estimating the relationship between institutional characteristics and the probability of higher graduation performance.

Preprocessing and modeling were organized using Python and scikit-learn pipelines to create a structured and reproducible analytical workflow.

## Model Evaluation

The models were evaluated using classification performance measures to assess their ability to distinguish between institutions with different graduation-performance outcomes.

Evaluation included:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- Classification Report

Model results were compared to understand the strengths and limitations of each approach rather than relying on a single performance measure.

## Key Analytical Focus

The project demonstrates how institutional data can be transformed into a predictive framework for understanding student outcomes.

The analysis considered factors related to:

- Enrollment patterns
- Institutional characteristics
- Student demographics
- Financial and cost measures
- Academic outcomes
- Graduation performance

Rather than treating graduation outcomes as an isolated metric, the project examined how multiple institutional characteristics interact within a broader higher-education environment.

## Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Logistic Regression
- Decision Tree Classification
- Data Cleaning & Integration
- Feature Engineering
- Exploratory Data Analysis
- Predictive Modeling
- Model Evaluation

## Project Workflow

`College Scorecard + IPEDS Data`
→ `Data Cleaning & Filtering`
→ `Dataset Integration`
→ `Exploratory Data Analysis`
→ `Feature Engineering`
→ `Decision Tree + Logistic Regression`
→ `Model Evaluation`
→ `Interpretation & Recommendations`

## Key Takeaways

This project strengthened my ability to manage a complete data science workflow involving large, real-world public datasets. It required integrating multiple federal higher-education data sources, preparing and transforming data in Python, conducting exploratory analysis, engineering features, developing classification models, and interpreting results within an educational context.

The project also demonstrated how predictive analytics can be used to move beyond simply reporting historical student outcomes toward identifying patterns that may support earlier intervention, institutional planning, and data-informed student-success strategies.

---

**Author:** Kedeesh Nolan  
**Master's in Data Science Project | Applied Data Science**
