
# University Graduates & AI Enrollment Analysis

## Overview

This project explores higher education data to analyze university graduate trends and enrollment in postgraduate programs related to Artificial Intelligence and Data Analytics.

Developed as part of my Master's degree in Artificial Intelligence at Universidad Internacional de La Rioja (UNIR), the project combines exploratory data analysis, statistical techniques, visualization, and classical Machine Learning methods.

The analysis focuses on understanding patterns in university graduation records and examining relationships between graduates and postgraduate enrollment.

## Objectives

- Explore university graduation trends across multiple years.
- Clean and preprocess educational datasets.
- Analyze distributions by institution, city, and academic program.
- Examine relationships between university graduates and postgraduate enrollment.
- Apply correlation analysis and feature scaling.
- Explore simple and multiple linear regression models.
- Evaluate regression results using statistical metrics.

## Technologies

**Programming and Data Analysis**
- Python
- pandas
- NumPy

**Data Visualization**
- Matplotlib
- Seaborn
- Plotly

**Machine Learning**
- scikit-learn
- Linear Regression
- MinMaxScaler

**Development Environment**
- Jupyter Notebook
- Google Colab (original academic environment)

## Datasets

The project uses educational datasets covering university graduates and postgraduate enrollment.

### University Graduates

CSV files containing graduation records for:

- 2019
- 2020
- 2021
- 2022
- 2023

### Academic Program Analysis

- `Egresados_Licenciaturas_2022.xlsx`
- `Ingresos_Posgrados_IA_Datos_2023.xlsx`

These datasets support the analysis of graduation patterns and postgraduate enrollment in AI-related fields.

The original datasets are stored separately until their sources and redistribution permissions are verified.

## Project Structure

```text
university-graduates-ai-enrollment-analysis/
├── README.md
├── requirements.txt
├── .gitignore
│
├── notebooks/
│   ├── 01_graduates_exploration.ipynb
│   └── 02_enrollment_analysis_regression.ipynb
│
├── data/
│   └── README.md
│
└── results/
```

## Methodology

### 1. Data Collection and Loading

Educational datasets are imported from CSV and Excel files using pandas.

The project combines data from multiple academic years to support exploratory and comparative analysis.

### 2. Data Cleaning and Preprocessing

Preprocessing includes:

- Reviewing dataset structure and column names.
- Handling missing values.
- Normalizing text and categorical information.
- Filtering and grouping records.
- Preparing numerical variables for statistical analysis.

### 3. Exploratory Data Analysis

Exploratory analysis examines:

- Distribution of university graduates.
- Differences between academic institutions.
- Geographic patterns.
- Academic program categories.
- Year-to-year graduation trends.

### 4. Data Visualization

The project uses Matplotlib, Seaborn, and Plotly to visualize distributions, relationships, and trends in educational data.

Visualizations support the interpretation of patterns and comparisons across datasets.

### 5. Correlation Analysis

Correlation techniques are used to explore relationships between numerical variables.

These results are interpreted as statistical associations, not causal relationships.

### 6. Feature Scaling

MinMaxScaler from scikit-learn is used to transform numerical features into normalized ranges for selected analyses.

### 7. Linear Regression

The project explores simple and multiple linear regression using scikit-learn.

Models are fitted to examine relationships between educational variables, including graduates and postgraduate enrollment.

### 8. Model Evaluation

The notebooks use regression metrics such as:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)

The original regression experiments calculate predictions on the same observations used for fitting.

Therefore, these metrics describe in-sample fit and should not be interpreted as validated predictive performance on unseen data.

## Notebooks

### 01 — University Graduates Exploration

`notebooks/01_graduates_exploration.ipynb`

Analyzes university graduation records from 2019 to 2023.

Includes data loading, normalization, grouping, and exploratory visualization.

### 02 — AI & Data Analytics Enrollment Analysis

`notebooks/02_enrollment_analysis_regression.ipynb`

Analyzes educational data related to graduates and postgraduate enrollment.

Includes:

- Exploratory analysis.
- Data visualization.
- Correlation analysis.
- Feature scaling.
- Linear regression.
- Regression evaluation metrics.

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/ngualteros/University-Graduates-AI-Enrollment-Analysis.git
```

### 2. Create a Virtual Environment

```bash
python -m venv .venv
```

Activate it on Windows:

```powershell
.\.venv\Scripts\Activate.ps1
```

### 3. Install Dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Prepare the Datasets

Place the authorized CSV and Excel files in the `data/` directory.

The original academic notebooks reference files by their original names and contain Google Colab-specific upload instructions.

Before running locally, these references must be updated to use the repository's `data/` directory.

### 5. Run the Notebooks

```bash
jupyter notebook
```

Open the notebooks inside the `notebooks/` directory and execute the cells sequentially after adjusting the data paths.

## Results and Limitations

The original academic work includes exploratory visualizations, statistical comparisons, and regression experiments.

Important limitations:

- Regression results are evaluated in-sample.
- The analysis does not establish causal relationships.
- Graduate and postgraduate enrollment datasets do not necessarily represent the same individuals.
- Data compatibility and source availability must be verified.
- Execution in a clean local environment requires path adjustments.

## Future Improvements

- Standardize data-loading paths.
- Improve reproducibility across environments.
- Separate training and testing data for predictive experiments.
- Add cross-validation where appropriate.
- Compare regression models with baseline approaches.
- Add automated data validation.
- Document verified results and visualizations.

## Academic Context

Developed as part of the Master's in Artificial Intelligence at Universidad Internacional de La Rioja (UNIR).

Course: Data Analysis and Interpretation.

The repository documents academic exercises and analysis. Group contributions should be acknowledged where applicable.

## Author

**Nicolás Gualteros Pérez**

Systems Engineer | Master's in Artificial Intelligence

Machine Learning | Data Analysis | AI Engineering | Automation

LinkedIn: https://www.linkedin.com/in/nicogualteros
