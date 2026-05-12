# Health Informatics & Precision Medicine Project Portfolio

This repository contains selected reproducible projects in health informatics, biomedical data analytics, clinical data analysis, and precision medicine.

The repository is organized as a project portfolio rather than a private learning plan. Each project focuses on a concrete analytical task and includes code, notebooks, outputs, and concise interpretation notes when available.

## Focus Areas

- Health data cleaning and exploratory data analysis
- Biomedical tabular data analysis
- SQL-based clinical cohort construction
- Regression modeling and model evaluation
- Survival analysis and cancer outcome modeling
- Precision medicine and oncology informatics
- Public biomedical dataset analysis
- Simplified reproduction and extension of published analysis workflows
- Reproducible research using Python, R, SQL, and Jupyter Notebook

## Project Index

| Project | Topic | Key Methods | Folder |
|---|---|---|---|
| Breast Cancer EDA | Diagnostic tumor feature analysis using tabular biomedical data | Python, Pandas, summary statistics, visualization | `projects/01_breast_cancer_eda/` |
| Clinical SQL Cohort Project | Simulated relational health data and cohort construction | SQL, joins, aggregation, cohort summaries | `projects/02_clinical_sql_project/` |
| R Health Data Analysis Mini Project | Re-analysis of a health dataset using R | R, dplyr, ggplot2, reproducible reporting | `projects/03_r_health_data_analysis/` |
| Regression Modeling Project | Binary health outcome modeling and model interpretation | Logistic regression, train-test split, ROC/AUC, calibration basics | `projects/04_regression_modeling/` |
| Survival Analysis Project | Cancer outcome and time-to-event analysis | Kaplan-Meier, log-rank test, Cox regression | `projects/05_survival_analysis/` |
| Precision Medicine Data Resource Review | Exploration of public biomedical and oncology data resources | TCGA, cBioPortal, GEO, GENIE-style data review, data dictionary | `projects/06_precision_medicine_data_resources/` |
| Oncology Biomarker Analysis | Association between molecular features and clinical outcomes | Mutation or expression data, clinical covariates, regression or survival analysis | `projects/07_oncology_biomarker_analysis/` |
| Clinical Decision Support Mini Project | Rule-based or risk-score-based health decision logic | Clinical rules, risk stratification, decision logic, ethical limitations | `projects/08_clinical_decision_support/` |
| Paper Reproduction Series | Simplified reproduction of selected published health or precision medicine analyses | Public data, statistical modeling, reproducible notebooks, comparison with published workflow | `projects/09_paper_reproduction_series/` |
| Final Integrative Project | End-to-end health informatics or precision medicine analysis | Data cleaning, modeling, interpretation, README, report, presentation summary | `projects/10_final_integrative_project/` |

## Suggested Paper Reproduction Series

The paper reproduction component may include one major reproducible analysis and several shorter paper dissection exercises.

| Component | Scope | Output |
|---|---|---|
| Paper Dissection 1 | Identify research question, cohort, predictors, outcome, model, and limitations | Structured paper note |
| Paper Dissection 2 | Compare methods across a related health informatics or precision medicine paper | Structured paper note |
| Paper Dissection 3 | Review a second modeling or survival-analysis workflow | Structured paper note |
| Main Reproduction Project | Reproduce a simplified version of one published analysis using public data | Notebook, figures, tables, README, short report |
| Optional Extension | Modify the original workflow by adding a covariate, subgroup, visualization, or evaluation metric | Extended notebook or appendix |

## Repository Structure

```text
projects/
  01_breast_cancer_eda/
  02_clinical_sql_project/
  03_r_health_data_analysis/
  04_regression_modeling/
  05_survival_analysis/
  06_precision_medicine_data_resources/
  07_oncology_biomarker_analysis/
  08_clinical_decision_support/
  09_paper_reproduction_series/
  10_final_integrative_project/

shared/
  scripts/
  sql/
  references/
  data_dictionaries/

docs/
  project_summaries/
  paper_notes/
  final_reports/