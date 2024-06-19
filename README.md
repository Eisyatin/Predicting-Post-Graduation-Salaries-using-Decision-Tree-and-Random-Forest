# Prediction of Post Graduation Salary (Group Project for Subject: Business Intelligence)

This project predicts post-graduation salaries using two machine learning algorithms: Decision Tree and Random Forest. The project is developed using RapidMiner for data understanding, data preparation, and model deployment.

## Project Overview

This repository contains the following:
- **[Raw Data](https://github.com/Eisyatin/Predicting-Post-Graduation-Salaries-using-Decision-Tree-and-Random-Forest/blob/main/Graduate_Tracer_Study_ORIGINAL.xlsx)**: The original dataset used for analysis.
- **[Processed Data](https://github.com/Eisyatin/Predicting-Post-Graduation-Salaries-using-Decision-Tree-and-Random-Forest/blob/main/Graduate_Tracer_Study_PROCESSED.csv)**: The dataset after cleaning and preprocessing.
- **Models**: Implementations of Decision Tree and Random Forest algorithms.
- **PDF Documentation**: Detailed documentation of the project workflow and findings.
  - [Data Understanding and Preparation](https://github.com/Eisyatin/Predicting-Post-Graduation-Salaries-using-Decision-Tree-and-Random-Forest/blob/main/DataUnderstanding_DataPreparation_GraduateTracerStudy.pdf)
  - [Modelling and Predicting Salaries](https://github.com/Eisyatin/Predicting-Post-Graduation-Salaries-using-Decision-Tree-and-Random-Forest/blob/main/Modelling_PredictingPostGraduationSalariesusingDTandRF.pdf)

## Team Members

- Aina Farzana Zulkifli | 2021817142
- Nur Eisyatin Radhiah Annuar | 2021610238
- Siti Mukhlisah Muskamal | 2022815898
- Yasmin Nabila Othman | 2021619506

## Data Source

The data used in this project is sourced from the Graduate Tracer Study. The dataset comprises 902 records with 12 attributes. Key attributes include:
- Gender
- Age
- Graduation Year
- Program Code
- Current Occupation
- Job Category
- Department
- Company Name
- Type of Company
- Company's Nature of Business
- Years of Work Experience (after graduation)
- Current Salary Midpoint

## Data Understanding and Preparation

The data understanding and preparation process involved the following steps:
1. **Data Exploration**: Examining the dataset to understand its structure and content.
2. **Data Quality Assessment**: Checking for missing values, outliers, and inconsistencies.
3. **Data Cleaning**: Replacing missing values and correcting errors.
4. **Data Transformation**: Converting nominal data to numerical where necessary, e.g., transforming salary range to salary midpoint.
5. **Feature Selection**: Selecting relevant attributes for modeling based on their significance to the target outcome.

For detailed steps and methodologies, refer to the PDF documentation provided in the repository.

## Models

### Decision Tree

A Decision Tree model was built using RapidMiner to classify and predict the salary range of graduates. The key metrics for the model's performance are:
- Precision: 52.46%
- Recall: 53.27%
- F1-Score: 0.4672

### Random Forest

A Random Forest model was also developed to enhance prediction accuracy. The performance metrics for this model are:
- Precision: 71.53%
- Recall: 56.67%
- F1-Score: 0.6782

### Salary Categories

The salary predictions are categorized into three ranges:
- **Low**: < RM3000
- **Medium**: RM3000 - RM5000
- **High**: > RM5000

## Recommendations

Based on the findings, we provide the following recommendations:
1. Enhance curriculum to include skills that are most valued in the workforce.
2. Provide more opportunities for students to gain work experience before graduation.
3. Encourage students to pursue programs with higher employability rates.
