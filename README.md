# Project Management Success Analysis

This repository contains a **synthetic project management dataset** and a Jupyter notebook that performs exploratory data analysis (EDA) and predictive modeling. The goal is to understand which factors contribute to a project's success and build models to predict the likelihood of success.

## Dataset

The dataset (`project_management_data.csv`) includes 300 synthetic project records with the following columns:

| Column | Description |
| --- | --- |
| `project_id` | Unique identifier for each project |
| `team_size` | Number of team members assigned to the project |
| `project_budget` | Planned budget for the project (in USD) |
| `actual_budget` | Actual budget spent on the project |
| `planned_duration` | Planned project duration (in days) |
| `actual_duration` | Actual project duration (in days) |
| `issues_reported` | Number of issues reported during the project |
| `satisfaction_score` | Satisfaction score (0–100) from stakeholders |
| `manager_experience_years` | Years of experience of the project manager |
| `complexity` | Project complexity level (`Low`, `Medium`, `High`) |
| `industry` | Industry sector (`Technology`, `Finance`, `Healthcare`, `Retail`) |
| `on_time` | Indicator (1/0) whether the project finished on or before the planned duration |
| `under_budget` | Indicator (1/0) whether the project stayed under its planned budget |
| `success` | Target variable representing whether the project met time and budget goals and achieved high satisfaction (1) or not (0) |

## Notebook

The Jupyter notebook (`analysis_notebook.ipynb`) performs the following steps:

1. **Load the Dataset** – Reads the CSV file into a pandas DataFrame and displays the first few rows.
2. **Exploratory Data Analysis** – Summarizes the data, visualizes distributions of numeric features, and examines correlations and success rates across categorical variables.
3. **Preprocessing** – Encodes categorical variables and splits the data into training and testing sets.
4. *
5. *Modeling** – Trains a logistic regression and a random forest classifier to predict project success and evaluates their performance.
6. **Visualization** – Displays confusion matrices to compare model predictions and discusses which model performs better.

## How to Use

1. Clone this repository or download the files.
2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Open the Jupyter notebook:

```bash
jupyter notebook analysis_notebook.ipynb
```

4. Run the notebook cells to reproduce the analysis and explore the synthetic data.

## Purpose

This project is designed for **business analysts**, **program managers**, and **data analysts** who want to showcase their analytical skills using a complete data science workflow. It demonstrates data generation, exploratory analysis, feature engineering, model training, and interpretation of results.

Feel free to modify the dataset generation process or extend the analysis to include more advanced techniques such as hyperparameter tuning, feature importance investigation, or other machine learning algorithms.

## License

This project is released under the MIT License. You are free to use, modify, and distribute it for educational and professional purposes.
performance.
## Additional Experiments

You can further experiment with hyperparameter tuning, cross-validation, and feature importance to improve model performance.
