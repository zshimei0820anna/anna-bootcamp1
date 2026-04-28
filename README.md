# anna-bootcamp1

This repository contains my 4-month preparation work for JHU MS Health Sciences Informatics, with a focus on precision medicine informatics, biomedical informatics, clinical data analytics, cancer genomics, and reproducible research.

## Background

Prior experience with MATLAB for chemistry-related experimental data processing, plotting, EPR data handling, and exposure to PCA/PLS during my undergraduate thesis project. This bootcamp is designed to help me transfer my MATLAB-based scientific computing background into Python, R, SQL, biomedical informatics, and health data science workflows.

## Final Goal

Aim to be prepared for JHU MS Health Sciences Informatics coursework and research-oriented projects.

I should be able to:

- Use Python, R, and SQL for health and biomedical data analysis
- Translate MATLAB-style scientific computing workflows into Python and R
- Use Jupyter Notebook and RStudio to produce reproducible analysis reports
- Use Pandas, NumPy, matplotlib, seaborn, dplyr, ggplot2, and basic statistical modeling tools
- Query relational health data using SQL
- Understand patient, encounter, diagnosis, lab, medication, specimen, molecular, and outcome tables
- Understand core biomedical informatics concepts relevant to clinical data, precision medicine, decision support, and research methods
- Run and interpret regression models, including linear regression, logistic regression, and Cox proportional hazards models
- Perform basic dimensionality reduction and multivariable modeling, including PCA and regularized regression
- Analyze public health, clinical, cancer genomics, or precision medicine datasets
- Partially reproduce a simplified regression-based or survival-analysis-based precision medicine study
- Organize code, figures, tables, notes, and project documentation using GitHub

## JHU MS HSI Alignment

This plan is designed to support preparation for core JHU MS Health Sciences Informatics themes, including:

- Introduction to Precision Medicine Data Analytics
- Introduction to Biomedical Informatics
- Applied Clinical Informatics
- Health Science Informatics: Knowledge Engineering and Decision Support
- Design Discovery for Health Care
- Database Querying in Health
- Health Sciences Informatics Research Methods
- Capstone or thesis project preparation

## Month 1: MATLAB-to-Python Scientific Data Analysis and Health Data Foundations

Goal: Move from MATLAB-based scientific data handling to Python-based reproducible biomedical data analysis.

By the end of Month 1, I should be able to use Python and Jupyter Notebook to clean, transform, summarize, visualize, and document tabular biomedical or health-related datasets.

Weekly plan:

- Week 1: Python for MATLAB users
  - Python syntax only as needed for scientific computing
  - Differences between MATLAB and Python indexing, arrays, functions, scripts, and notebooks
  - NumPy arrays, vectorized operations, indexing, slicing, broadcasting, and matrix-style thinking
  - Jupyter Notebook workflow, Markdown documentation, reproducible analysis structure
  - Mini-task: Recreate a simple MATLAB-style data processing workflow in Python

- Week 2: Pandas for experimental and health data
  - DataFrame structure compared with MATLAB tables
  - Reading CSV/Excel files
  - Inspecting data using shape, head, info, describe, value_counts
  - Filtering, selecting, sorting, creating variables, and recoding categories
  - Handling missing values, duplicate rows, data types, and date/time variables
  - Mini-task: Clean and summarize a simulated patient or biomedical dataset

- Week 3: Visualization and exploratory biomedical data analysis
  - matplotlib and seaborn for publication-style exploratory figures
  - Histograms, boxplots, scatterplots, line plots, grouped bar charts, heatmaps
  - Grouped summaries using groupby
  - Correlation analysis and visual inspection of variables
  - Comparison with MATLAB plotting workflow
  - Mini-task: Create a figure panel for a health or biomedical dataset

- Week 4: First structured health data analysis project
  - Full Python notebook project
  - Data import, cleaning, feature creation, exploratory analysis, visualization, and interpretation
  - Write results in Markdown using a clear scientific reporting style
  - Mini-project: Exploratory analysis of a public or simulated health dataset

Month 1 deliverable:

- A polished Jupyter Notebook that analyzes a health or biomedical dataset using Python
- The notebook should include clean code, Markdown explanation, summary tables, figures, and a short interpretation section

Month 1 standard for high performance:

- I can independently receive a messy CSV file and produce an analysis-ready dataset
- I can explain each data-cleaning decision
- I can produce interpretable plots rather than just code output
- I can write a short scientific summary of the results
## Month 2: SQL, Relational Clinical Data, R, and Biomedical Informatics Foundations

Goal: Build the database and informatics foundation needed for Database Querying in Health, Applied Clinical Informatics, and biomedical informatics coursework.

By the end of Month 2, I should be able to understand and query relational health data, then analyze the extracted data using Python or R.

Weekly plan:

- Week 5: SQL fundamentals for clinical data
  - SELECT, WHERE, ORDER BY, LIMIT, DISTINCT
  - Filtering by demographics, diagnoses, lab values, medications, and dates
  - Basic database thinking: rows, columns, primary keys, foreign keys
  - Mini-task: Query a patient table and create demographic summaries

- Week 6: SQL aggregation and clinical summary tables
  - COUNT, AVG, SUM, MIN, MAX
  - GROUP BY and HAVING
  - Case statements for derived categories
  - Creating cohort counts and stratified summaries
  - Mini-task: Generate patient-level and encounter-level summary tables

- Week 7: Multi-table relational health data
  - INNER JOIN, LEFT JOIN, one-to-many relationships
  - patient_id, encounter_id, specimen_id, diagnosis_id
  - Joining patient, encounter, diagnosis, lab, medication, and outcome-style tables
  - Common clinical data problems: duplicated rows after joins, repeated encounters, longitudinal records
  - Mini-task: Build an analysis-ready table from multiple simulated clinical tables

- Week 8: R for statistical reporting and biomedical analysis
  - RStudio workflow
  - data.frame and tibble
  - dplyr: select, filter, mutate, group_by, summarise, arrange, left_join
  - ggplot2: scatterplot, boxplot, histogram, line plot, grouped bar chart
  - Comparison between Pandas and dplyr workflows
  - Mini-task: Repeat one Python analysis in R

Biomedical informatics concepts to learn:

- EHR structure
- Patient and encounter data
- Diagnosis, procedure, medication, and lab data
- ICD, CPT, LOINC, RxNorm at a conceptual level
- FHIR, OMOP, and clinical data models at a conceptual level
- Cohort definition
- Phenotyping
- Clinical outcome definition
- Data provenance and reproducibility

Month 2 deliverables:

- A SQL script or notebook with 10-15 well-commented clinical data queries
- A small relational health data project that joins multiple tables and produces an analysis-ready table
- A short R script or R Markdown file that performs cleaning, summary, and visualization

Month 2 standard for high performance:

- I can translate a clinical question into SQL queries
- I can recognize patient-level versus encounter-level analysis
- I can avoid common join mistakes
- I can move data from SQL into Python or R for analysis
## Month 3: Biostatistics, Regression, Survival Analysis, and Precision Medicine Modeling

Goal: Build the statistical modeling foundation needed for Research Methods, Precision Medicine Data Analytics, and future capstone or thesis work.

By the end of Month 3, I should be able to run, evaluate, and interpret basic models used in biomedical and precision medicine studies.

Weekly plan:

- Week 9: Biostatistics and research methods foundations
  - Descriptive statistics
  - Distributions, sampling, standard error, confidence intervals
  - p-values and hypothesis testing
  - t-test, chi-square test, nonparametric alternatives at a practical level
  - Study design basics: cohort, case-control, cross-sectional analysis
  - Bias, confounding, missing data, and reproducibility
  - Mini-task: Write a statistical analysis plan for a small health dataset

- Week 10: Regression modeling for health outcomes
  - Linear regression
  - Logistic regression
  - Coefficients, odds ratios, confidence intervals, p-values
  - Covariate adjustment and confounding
  - Model assumptions and interpretation
  - Mini-task: Fit and interpret a logistic regression model for a binary health outcome

- Week 11: Model evaluation and machine learning foundations
  - Train-test split and cross-validation
  - Confusion matrix, sensitivity, specificity, precision, recall
  - ROC curve and AUC
  - Calibration basics
  - Regularized regression: LASSO, ridge, elastic net
  - Connection to PCA/PLS and high-dimensional biomedical predictors
  - Mini-task: Compare logistic regression and regularized regression on a health dataset

- Week 12: Survival analysis and precision medicine outcomes
  - Time-to-event data
  - Kaplan-Meier curves
  - Log-rank test
  - Cox proportional hazards model
  - Hazard ratios and survival interpretation
  - Overall survival and progression-free survival
  - Mini-task: Fit a Cox model using a public or simulated cancer dataset

Precision medicine concepts to learn:

- Mutation
- Gene expression
- Biomarker
- Tumor type
- Molecular subtype
- Treatment response
- Overall survival
- Progression-free survival
- Clinical covariates
- Feature selection
- Internal validation
- External validation at a conceptual level

Month 3 deliverables:

- A regression analysis project using Python or R
- A survival analysis notebook using R or Python
- A short written report interpreting model results in biomedical terms

Month 3 standard for high performance:

- I can choose an appropriate model for continuous, binary, and time-to-event outcomes
- I can interpret coefficients, odds ratios, hazard ratios, p-values, and confidence intervals
- I can evaluate model performance and explain limitations
- I can connect statistical models to clinical or precision medicine questions
## Month 4: Precision Medicine, Cancer Informatics, Decision Support, and Paper Reproduction

Goal: Apply programming, SQL, statistics, and biomedical informatics skills to a final project aligned with precision medicine informatics, cancer genomics, and health sciences informatics research.

By the end of Month 4, I should be able to complete a small but rigorous project that resembles the structure of a JHU HSI course project or early capstone idea.

Weekly plan:

- Week 13: Public precision medicine and cancer data resources
  - TCGA
  - cBioPortal
  - AACR Project GENIE
  - GEO
  - Clinical annotation files
  - Mutation tables
  - Gene expression matrices
  - Survival and outcome variables
  - Mini-task: Download or access one public cancer dataset and create a data dictionary

- Week 14: Knowledge engineering and decision support concepts
  - Clinical decision support basics
  - Rule-based decision logic
  - Risk scores
  - Basic FHIR and CDS concepts
  - Translating model results into clinical interpretation
  - Ethical issues: bias, privacy, data leakage, clinical validity, model generalizability
  - Mini-task: Design a simple decision-support logic based on a regression or risk model

- Week 15: Paper reproduction pipeline
  - Select one recent precision medicine, cancer genomics, computational pathology, or biomedical informatics paper
  - Identify the research question, cohort, predictors, outcome, model, and evaluation method
  - Reproduce a simplified version of the analysis using public data
  - Focus on regression, regularized regression, or survival analysis rather than deep learning
  - Mini-task: Produce a reproducible notebook that mirrors the paper's core analysis logic

- Week 16: Final project polishing and GitHub presentation
  - Clean code and folder structure
  - Finalize figures and tables
  - Write README and methods summary
  - Document limitations and next steps
  - Prepare a 1-page project summary and a 5-minute oral explanation
  - Mini-task: Final GitHub repository cleanup and final project write-up

Possible final project topics:

- Association between selected cancer gene mutations and survival outcomes
- Cox regression analysis using TCGA clinical and molecular data
- Logistic regression model predicting treatment response using clinical and molecular features
- Exploratory mutation frequency analysis using cBioPortal or GENIE-style data
- Gene expression signature analysis with regression or survival outcomes
- Simplified reproduction of a published precision medicine analytics study
- Simple clinical decision-support prototype based on a risk model

Month 4 deliverables:

- A final precision medicine or cancer informatics mini-project
- A reproducible GitHub repository with code, figures, tables, README, and written interpretation
- A short project report written in a scientific format
- A brief presentation-style summary for future advisor or course discussion

Month 4 standard for high performance:

- I can define a precise biomedical informatics question
- I can justify the dataset, variables, outcome, and model
- I can reproduce a simplified analysis pipeline from a paper
- I can explain limitations clearly
- I can present the project in a way that is understandable to a course instructor or potential research mentor