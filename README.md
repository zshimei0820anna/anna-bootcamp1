# anna-bootcamp1

This repository contains my 4-month preparation work for JHU MS Health Sciences Informatics, with a focus on precision medicine informatics, biomedical informatics, cancer genomics, and health data analytics.

## Final Goal

By the end of this 4-month bootcamp, I aim to become comfortable using Python, R, SQL, and basic statistical modeling to analyze health-related and precision medicine datasets.

I should be able to:

- Use Python and Jupyter Notebook for data cleaning, analysis, and visualization
- Use Pandas and NumPy to work with tabular health and biomedical datasets
- Use SQL to query relational health data
- Use R for statistical analysis, visualization, and survival analysis
- Understand basic biomedical informatics and clinical informatics concepts
- Understand basic precision medicine data types, including clinical variables, genomics, gene expression, biomarkers, and outcomes
- Run and interpret basic regression models, including linear regression, logistic regression, and Cox proportional hazards models
- Build a small cancer or precision medicine data analysis project using public datasets
- Partially reproduce a simplified regression-based or survival-analysis-based precision medicine study
- Organize my code, figures, tables, and project documentation using GitHub

## Program and Research Context

This learning plan is designed around JHU MS Health Sciences Informatics core coursework and my research interests in precision medicine, biomedical informatics, molecular pathology, computational pathology, and cancer data analytics.

Relevant course themes include:

- Introduction to Precision Medicine Data Analytics
- Introduction to Biomedical Informatics
- Applied Clinical Informatics
- Knowledge Engineering and Decision Support
- Database Querying in Health
- Health Sciences Informatics Research Methods
- Capstone or thesis project preparation

My research preparation will emphasize:

- Precision medicine informatics
- Cancer genomics and molecular diagnostics
- Biomedical data analysis
- Computational pathology concepts
- Clinical and molecular data integration
- Regression and survival modeling for health outcomes

## Monthly Goals

### Month 1: Programming Foundations and Python Data Analysis

Goal: Build basic programming confidence and learn how to use Python for tabular health data analysis.

By the end of Month 1, I should be able to read a CSV file, inspect the dataset, clean simple missing values, create new variables, summarize data, and make basic plots in Python.

Weekly plan:

- Week 1: Python basics, Jupyter Notebook, variables, loops, functions, lists, dictionaries, and basic debugging
- Week 2: NumPy and Pandas basics, DataFrame operations, reading CSV files, filtering rows, selecting columns, and creating new variables
- Week 3: Data cleaning with Pandas, missing values, duplicates, data types, dates, string operations, and simple exploratory data analysis
- Week 4: Data visualization with Matplotlib and Seaborn, summary tables, groupby analysis, and a small Python health data project

Month 1 deliverable:

- A Jupyter Notebook analyzing a simple public or simulated health dataset using Python and Pandas

### Month 2: SQL, Biomedical Informatics, and R Basics

Goal: Learn how health and biomedical data are structured, queried, and analyzed across multiple tables.

By the end of Month 2, I should be able to use SQL to query patient, encounter, diagnosis, lab, medication, and molecular-style tables.

Weekly plan:

- Week 5: SQL basics, SELECT, WHERE, ORDER BY, LIMIT, DISTINCT, and filtering health data
- Week 6: SQL aggregation, COUNT, AVG, SUM, GROUP BY, HAVING, and summary tables
- Week 7: SQL joins, patient_id, encounter_id, specimen_id, diagnosis_id, INNER JOIN, LEFT JOIN, and multi-table health data queries
- Week 8: R basics, RStudio, data frames, dplyr, ggplot2, and comparison between R and Python workflows

Biomedical informatics concepts to learn:

- Patient table
- Encounter table
- Diagnosis table
- Lab result table
- Medication table
- Specimen table
- Tumor sample table
- Gene mutation table
- Biomarker table
- Clinical outcome table

Month 2 deliverable:

- A SQL notebook or SQL script answering 8-10 questions using simulated relational health or cancer data
- A short R script or R Markdown file that performs basic data cleaning and visualization

### Month 3: Statistics, Regression, Survival Analysis, and Precision Medicine Data

Goal: Learn the statistical and regression methods commonly used in health informatics and precision medicine studies.

By the end of Month 3, I should be able to run and interpret basic regression and survival models in Python or R.

Weekly plan:

- Week 9: Descriptive statistics, distributions, sampling, confidence intervals, p-values, hypothesis testing, and group comparisons
- Week 10: Linear regression and logistic regression, coefficients, odds ratios, p-values, confidence intervals, and model interpretation
- Week 11: Model evaluation, train-test split, confusion matrix, ROC curve, AUC, sensitivity, specificity, and calibration basics
- Week 12: Survival analysis basics, Kaplan-Meier curves, log-rank test, Cox proportional hazards model, hazard ratios, and survival outcome interpretation

Precision medicine concepts to learn:

- Mutation
- Gene expression
- Biomarker
- Tumor type
- Treatment response
- Overall survival
- Progression-free survival
- Immune checkpoint blockade
- Molecular subtype
- Clinical covariates

Month 3 deliverable:

- A regression or survival analysis project using Python or R
- The project should include data cleaning, exploratory analysis, model fitting, model evaluation, and written interpretation

### Month 4: Cancer Informatics Project and Paper Reproduction

Goal: Apply programming, SQL, statistics, and biomedical informatics skills to a precision medicine or cancer informatics project.

By the end of Month 4, I should be able to reproduce a simplified regression-based or survival-analysis-based study using public cancer or precision medicine data.

Weekly plan:

- Week 13: Learn public precision medicine and cancer data resources, including TCGA, cBioPortal, AACR Project GENIE, GEO, and relevant clinical annotation files
- Week 14: Select one recent precision medicine, oncology informatics, or computational pathology-related study with public data and a reproducible regression or survival analysis component
- Week 15: Reproduce a simplified analysis pipeline, including cohort definition, variable selection, outcome definition, model fitting, and evaluation
- Week 16: Finalize the project, clean the GitHub repository, write the README, summarize results, limitations, and next steps

Month 4 deliverable:

- A final mini-project that partially reproduces a regression-based or survival-analysis-based precision medicine study using Python or R
- The project should include code, figures, tables, and a written summary

Possible final project topics:

- Association between cancer gene mutations and survival outcomes
- Logistic regression model predicting treatment response using clinical and molecular features
- Cox regression analysis using TCGA clinical and molecular data
- Exploratory analysis of cancer mutation frequencies using cBioPortal or GENIE-style data
- Gene expression signature analysis with regression or survival outcomes
- Simplified reproduction of a published precision medicine analytics study

## Final Project Standard

At the end of this bootcamp, my final project should demonstrate that I can:

- Define a clear precision medicine or health informatics research question
- Load and inspect a public biomedical or health dataset
- Clean and transform clinical and molecular variables
- Use SQL or Pandas to create analysis-ready tables
- Perform exploratory data analysis
- Run a basic regression or survival model
- Evaluate model performance or interpret survival results
- Interpret results in a biomedical informatics or precision medicine context
- Organize code, figures, tables, and outputs clearly in GitHub
- Explain limitations and possible next steps

## Folder Structure

- `data/`: public or simulated datasets only
- `notebooks/`: Jupyter notebooks
- `scripts/`: Python and R scripts
- `sql/`: SQL queries
- `outputs/`: figures, result tables, and model outputs
- `papers/`: notes on relevant papers and reproduction targets