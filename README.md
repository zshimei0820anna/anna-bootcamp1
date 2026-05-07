# anna-bootcamp1

This repository contains my summer preparation work for JHU MS Health Sciences Informatics, with a focus on Python, R, SQL, health data analytics, biomedical informatics, precision medicine, and reproducible research.

## Background

I have prior experience with MATLAB for chemistry-related experimental data processing and plotting. I have also been exposed to PCA/PLS during my undergraduate thesis project. This preparation plan builds on that scientific data background while focusing on Python, R, SQL, statistics, and health informatics skills needed for JHU MS HSI.

## Final Goal

By the end of this summer preparation plan, I aim to be ready for JHU MS Health Sciences Informatics coursework and research-oriented projects.

I should be able to:

- Use Python, R, and SQL for health and biomedical data analysis
- Use Jupyter Notebook and RStudio to produce reproducible analysis reports
- Use Pandas, NumPy, Matplotlib, Seaborn, dplyr, ggplot2, and basic statistical modeling tools
- Query relational health data using SQL
- Understand common health data structures, including patient, encounter, diagnosis, lab, medication, specimen, molecular, and outcome tables
- Understand core concepts in biomedical informatics, clinical informatics, precision medicine, decision support, and research methods
- Clean, transform, summarize, visualize, and interpret health-related datasets
- Run and interpret linear regression, logistic regression, and Cox proportional hazards models
- Understand basic model evaluation, including train-test split, ROC curve, AUC, sensitivity, specificity, and calibration
- Understand basic dimensionality reduction and feature selection concepts, including PCA and regularized regression
- Analyze public health, clinical, cancer genomics, or precision medicine datasets
- Partially reproduce a simplified regression-based or survival-analysis-based health or precision medicine study
- Organize code, figures, tables, notes, and project documentation using GitHub

## JHU MS HSI Alignment

This plan is designed to support preparation for core JHU MS Health Sciences Informatics coursework and project work, including:

- Introduction to Precision Medicine Data Analytics
- Introduction to Biomedical Informatics
- Applied Clinical Informatics
- Health Science Informatics: Knowledge Engineering and Decision Support
- Design Discovery for Health Care
- Database Querying in Health
- Health Sciences Informatics Research Methods
- Capstone or thesis project preparation

## Month 1: Python, Jupyter, and Health Data Analysis Foundations

Goal: Build practical Python fluency for health data analysis and reproducible notebook-based reporting.

By the end of Month 1, I should be able to use Python and Jupyter Notebook to load, inspect, clean, summarize, visualize, and interpret tabular health-related datasets.

Weekly plan:

- Week 1: Python and Jupyter foundations for health data
  - Jupyter Notebook workflow
  - Markdown documentation
  - Variables, strings, numbers, booleans
  - Lists, dictionaries, loops, conditionals, and functions
  - Writing simple rule-based clinical classification functions
  - Creating small patient-level datasets
  - Basic debugging and reading error messages
  - Mini-task: Create a simulated patient dataset and classify patients using clinical threshold logic

## Week 2: Pandas and NumPy for Biomedical Tabular Data

- Focus: structured biomedical data analysis using Pandas and NumPy
- Dataset: Breast Cancer Wisconsin Diagnostic Dataset
- Core skills: `DataFrame`, `Series`, `read_csv`, `head`, `shape`, `info`, `describe`, `value_counts`
- Data cleaning: select columns, filter rows, check missing values, check duplicates, recode diagnosis labels
- Analysis task: compare selected numeric tumor features between benign and malignant samples
- Output: dataset inspection, diagnosis summary, feature summaries, grouped summaries, and short interpretation
- Deliverable: `month1_week2_breast_cancer_pandas_basics.ipynb`

- Week 3: Exploratory data analysis and visualization
  - Grouped summaries using groupby
  - Cross-tabulation and frequency tables
  - Histograms, boxplots, scatterplots, line plots, bar charts, and heatmaps
  - Correlation analysis
  - Writing interpretation sections for figures and tables
  - Mini-task: Create an exploratory analysis notebook with summary tables and plots

- Week 4: Month 1 mini-project
  - Full Python notebook workflow
  - Data import, cleaning, feature creation, exploratory analysis, visualization, and interpretation
  - Clear Markdown explanations
  - Short limitations section
  - Mini-project: Exploratory analysis of a public or simulated health dataset

Month 1 deliverable:

- A polished Jupyter Notebook analyzing a public or simulated health dataset using Python
- The notebook should include data cleaning, summary tables, figures, interpretation, and limitations

Month 1 high-performance standard:

- I can receive a tabular health dataset and produce a clean exploratory analysis notebook
- I can explain each data-cleaning decision
- I can transform raw measurements into interpretable variables
- I can write a concise scientific interpretation of tables and figures
## Month 2: SQL, Relational Health Data, R, and Biomedical Informatics Foundations

Goal: Build the database and informatics foundation needed for Database Querying in Health, Applied Clinical Informatics, and biomedical informatics coursework.

By the end of Month 2, I should be able to query relational health data, understand common clinical data structures, and analyze extracted data using Python or R.

Weekly plan:

- Week 5: SQL fundamentals for health data
  - SELECT, WHERE, ORDER BY, LIMIT, DISTINCT
  - Filtering patients by demographics, diagnoses, lab values, medications, and dates
  - Basic database concepts: tables, rows, columns, primary keys, foreign keys
  - Patient-level versus encounter-level data
  - Mini-task: Query a patient table and create demographic summaries

- Week 6: SQL aggregation and clinical summary tables
  - COUNT, AVG, SUM, MIN, MAX
  - GROUP BY and HAVING
  - CASE WHEN statements
  - Derived categories and cohort flags
  - Cohort counts and stratified summaries
  - Mini-task: Generate clinical summary tables from relational data

- Week 7: Multi-table relational health data
  - INNER JOIN and LEFT JOIN
  - One-to-one and one-to-many relationships
  - patient_id, encounter_id, diagnosis_id, lab_id, medication_id, specimen_id
  - Joining patient, encounter, diagnosis, lab, medication, and outcome-style tables
  - Common join problems: duplicated rows, repeated encounters, and incorrect denominators
  - Mini-task: Build an analysis-ready table from multiple simulated clinical tables

- Week 8: R basics for health data analysis
  - RStudio workflow
  - data.frame and tibble
  - dplyr: select, filter, mutate, group_by, summarise, arrange, left_join
  - ggplot2: histogram, boxplot, scatterplot, line plot, grouped bar chart
  - Comparison between Pandas and dplyr workflows
  - Mini-task: Repeat one Python analysis in R

Biomedical informatics concepts to learn:

- EHR structure
- Patient and encounter data
- Diagnosis, procedure, medication, and lab data
- ICD, CPT, LOINC, and RxNorm at a conceptual level
- FHIR and OMOP at a conceptual level
- Cohort definition
- Phenotyping
- Clinical outcome definition
- Data provenance
- Reproducibility

Month 2 deliverables:

- A SQL script or notebook with 10-15 well-commented clinical data queries
- A small relational health data project that joins multiple tables and produces an analysis-ready table
- A short R script or R Markdown file that performs cleaning, summary, and visualization

Month 2 high-performance standard:

- I can translate a clinical question into SQL queries
- I can distinguish patient-level, encounter-level, and observation-level analyses
- I can avoid common join mistakes
- I can move data from SQL into Python or R for further analysis
## Month 3: Biostatistics, Regression, Survival Analysis, and Model Evaluation

Goal: Build the statistical modeling foundation needed for Research Methods, Precision Medicine Data Analytics, and future capstone or thesis work.

By the end of Month 3, I should be able to choose, run, evaluate, and interpret basic statistical models used in health and biomedical studies.

Weekly plan:

- Week 9: Biostatistics and research methods foundations
  - Descriptive statistics
  - Distributions, sampling, standard error, confidence intervals
  - p-values and hypothesis testing
  - t-test, chi-square test, and nonparametric alternatives at a practical level
  - Study design basics: cohort, case-control, cross-sectional analysis
  - Bias, confounding, missing data, and reproducibility
  - Mini-task: Write a short statistical analysis plan for a small health dataset

- Week 10: Regression modeling for health outcomes
  - Linear regression for continuous outcomes
  - Logistic regression for binary outcomes
  - Coefficients, odds ratios, confidence intervals, and p-values
  - Covariate adjustment and confounding
  - Model assumptions and interpretation
  - Mini-task: Fit and interpret a logistic regression model for a binary health outcome

- Week 11: Model evaluation and machine learning foundations
  - Train-test split
  - Cross-validation
  - Confusion matrix
  - Sensitivity, specificity, precision, recall
  - ROC curve and AUC
  - Calibration basics
  - Regularized regression: LASSO, ridge, elastic net
  - PCA and feature reduction concepts
  - Mini-task: Compare logistic regression and regularized regression on a health dataset

- Week 12: Survival analysis and precision medicine outcomes
  - Time-to-event data
  - Censoring
  - Kaplan-Meier curves
  - Log-rank test
  - Cox proportional hazards model
  - Hazard ratios and survival interpretation
  - Overall survival and progression-free survival
  - Mini-task: Fit a Kaplan-Meier curve and Cox model using a public or simulated cancer dataset

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

- A regression analysis notebook using Python or R
- A survival analysis notebook using R or Python
- A short written report interpreting model results in biomedical or clinical terms

Month 3 high-performance standard:

- I can choose an appropriate model for continuous, binary, and time-to-event outcomes
- I can interpret coefficients, odds ratios, hazard ratios, p-values, and confidence intervals
- I can evaluate model performance and explain limitations
- I can connect statistical models to clinical or precision medicine questions
## Month 4: Precision Medicine, Clinical Decision Support, and Paper Reproduction

Goal: Apply programming, SQL, statistics, and biomedical informatics skills to a final project aligned with JHU HSI coursework and potential research interests.

By the end of Month 4, I should be able to complete a small but rigorous project that resembles the structure of a JHU HSI course project, capstone idea, or early research preparation project.

Weekly plan:

- Week 13: Public health, clinical, and precision medicine data resources
  - TCGA
  - cBioPortal
  - AACR Project GENIE
  - GEO
  - MIMIC demo or other accessible clinical datasets
  - Clinical annotation files
  - Mutation tables
  - Gene expression matrices
  - Survival and outcome variables
  - Mini-task: Select one public dataset and create a data dictionary

- Week 14: Knowledge engineering and decision support concepts
  - Clinical decision support basics
  - Rule-based decision logic
  - Risk scores
  - Basic FHIR and CDS concepts
  - Translating model results into clinical interpretation
  - Ethical issues: bias, privacy, data leakage, clinical validity, and model generalizability
  - Mini-task: Design a simple decision-support logic based on a clinical rule or risk model

- Week 15: Paper reproduction pipeline
  - Select one health informatics, precision medicine, oncology informatics, or biomedical informatics paper
  - Identify the research question, cohort, predictors, outcome, model, and evaluation method
  - Reproduce a simplified version of the analysis using public data
  - Focus on regression, regularized regression, or survival analysis rather than deep learning
  - Mini-task: Produce a reproducible notebook that mirrors the paper's core analysis logic

- Week 16: Final project polishing and presentation
  - Clean code and folder structure
  - Finalize figures and tables
  - Write README and methods summary
  - Document limitations and next steps
  - Prepare a 1-page project summary
  - Prepare a 5-minute oral explanation
  - Mini-task: Final GitHub repository cleanup and project write-up

Possible final project topics:

- Association between selected cancer gene mutations and survival outcomes
- Cox regression analysis using TCGA clinical and molecular data
- Logistic regression model predicting treatment response using clinical and molecular features
- Exploratory mutation frequency analysis using cBioPortal or GENIE-style data
- Gene expression signature analysis with regression or survival outcomes
- Simplified reproduction of a published precision medicine analytics study
- Simple clinical decision-support prototype based on a clinical rule or risk model

Month 4 deliverables:

- A final health informatics or precision medicine mini-project
- A reproducible GitHub repository with code, figures, tables, README, and written interpretation
- A short scientific report
- A brief presentation-style summary for future course, capstone, or research discussion

Month 4 high-performance standard:

- I can define a precise biomedical or health informatics question
- I can justify the dataset, variables, outcome, and model
- I can reproduce a simplified analysis pipeline from a paper
- I can explain limitations clearly
- I can present the project in a way that is understandable to a course instructor or potential research mentor
## Final Project Standard

At the end of this bootcamp, my final project should demonstrate that I can:

- Define a clear health informatics or precision medicine research question
- Load, inspect, and document a public biomedical or health dataset
- Clean and transform clinical and/or molecular variables
- Use SQL or Pandas to create analysis-ready tables
- Perform exploratory data analysis
- Apply regression, regularized regression, or survival analysis
- Evaluate model performance or interpret survival results
- Interpret findings in a biomedical informatics or clinical context
- Relate computational results to clinical relevance and limitations
- Organize code, figures, tables, and outputs clearly in GitHub
- Write a concise scientific report and README
- Explain the project verbally as preparation for JHU coursework, capstone, or research mentorship

## Folder Structure

- `data/`: public or simulated datasets only
- `notebooks/`: Jupyter notebooks
- `scripts/`: Python and R scripts
- `sql/`: SQL queries
- `outputs/`: figures, result tables, and model outputs
- `papers/`: notes on relevant papers and reproduction targets
- `reports/`: short written summaries and final project reports