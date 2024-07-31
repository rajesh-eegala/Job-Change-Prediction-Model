# Job Change Prediction

This project aims to predict whether an individual is likely to seek a job change based on various factors such as demographics, education, experience, and job history. The dataset used for this project includes features like gender, relevant experience, education level, and more.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)

## Overview

The objective of this project is to develop a predictive model that can accurately determine whether an individual is likely to look for a new job. This can help companies and HR professionals in talent management and retention strategies.

## Dataset

The dataset includes the following columns:

- `gender`: Gender of the individual
- `relevent_experience`: Relevant experience in the field
- `enrolled_university`: Enrollment status in a university course
- `education_level`: Highest education level attained
- `major_discipline`: Major discipline of education
- `experience`: Years of experience
- `company_size`: Size of the current company
- `company_type`: Type of the current company
- `last_new_job`: Time since last job change
- `training_hours`: Training hours completed
- `target`: Target variable indicating if the individual is looking for a job change

## Data Cleaning

The dataset contains missing values, which are handled by filling with the mode or dropping rows with missing data. This ensures a clean dataset for modeling.

## Exploratory Data Analysis

Exploratory Data Analysis (EDA) includes visualizations to understand the distribution of variables and their relationship with the target variable. Key visualizations include:

- Count plots for categorical variables
- Distribution plots for continuous variables

## Modeling

Various machine learning models are tested to predict the target variable, including:

- Logistic Regression
- Decision Trees
- Random Forest
- Gradient Boosting

## Evaluation

The models are evaluated using metrics like accuracy, precision, recall, and F1 score to ensure the best model performance.

## Results

The final model provides insights into the key factors influencing job change decisions. These insights can be used for strategic HR planning and employee retention.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.
