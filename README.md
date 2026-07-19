# IBM Data Science Professional Certificate – Capstone Project
# SpaceX Falcon 9 First Stage Landing Prediction

## Project Overview

This repository contains my final capstone project for the **IBM Data Science Professional Certificate**.

The objective of this project is to predict whether the first stage of the **SpaceX Falcon 9** rocket will successfully land after launch. Since reusable rockets significantly reduce launch costs, predicting landing success helps estimate launch expenses and provides valuable insights for companies competing in the commercial space industry.

---

## Business Problem

SpaceX advertises Falcon 9 launches at approximately **$62 million**, while many competitors charge over **$165 million** per launch. The lower cost is largely due to the successful recovery and reuse of the Falcon 9 first stage.

By predicting whether the first stage will land successfully, organizations can estimate launch costs and improve competitive bidding strategies.

---

# Project Workflow

## 1. Data Collection

Historical launch data was collected from:

- SpaceX REST API
- Wikipedia Web Scraping

---

## 2. Data Wrangling

The collected datasets were cleaned by:

- Handling missing values
- Removing unnecessary columns
- Formatting variables
- Creating features for analysis

---

## 3. Exploratory Data Analysis (EDA)

Exploratory analysis was performed using:

- SQL
- Pandas
- Matplotlib
- Seaborn

The analysis focused on relationships between:

- Launch Site
- Payload Mass
- Orbit Type
- Booster Version
- Landing Success

---

## 4. Interactive Dashboard

An interactive dashboard was developed using **Plotly Dash**.

The dashboard allows users to:

- Select launch sites
- Filter payload ranges
- Visualize landing success rates
- Explore launch trends interactively

---

## 5. Machine Learning

Several classification algorithms were trained and evaluated:

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- K-Nearest Neighbors (KNN)

Hyperparameter tuning was performed using **GridSearchCV** to identify the best-performing model.

---

# Repository Contents

| File | Description |
|------|-------------|
| `jupyter-labs-spacex-data-collection-api.ipynb` | Data collection using SpaceX API |
| `labs-jupyter-spacex-Data wrangling.ipynb` | Data cleaning and preprocessing |
| `jupyter-labs-eda-sql-coursera_sqllite.ipynb` | SQL analysis |
| `edadataviz.ipynb` | Data visualization and EDA |
| `lab_jupyter_launch_site_location.ipynb` | Interactive map visualization |
| `SpaceX_Machine Learning Prediction_Part_5.ipynb` | Machine learning models and evaluation |
| `spacex-dash-app.py` | Plotly Dash dashboard |
| `dataset_part_2.csv` | Processed dataset |
| `spacex_launch_dash.csv` | Dashboard dataset |

---

# Technologies Used

- Python
- Pandas
- NumPy
- SQL
- Matplotlib
- Seaborn
- Plotly Dash
- Folium
- Scikit-learn
- Jupyter Notebook

---

# Results

The project demonstrates that machine learning models can effectively predict Falcon 9 first-stage landing success using historical launch data.

Key findings include:

- Launch success varies by launch site.
- Payload mass influences landing success.
- Orbit type impacts landing probability.
- Machine learning models achieve strong predictive performance after feature engineering and hyperparameter tuning.

---

# How to Run the Project

## Clone the repository

```bash
git clone https://github.com/bakshidanish11-svg/IBM-DATA-SCIENCE-PROJECT-.git
```

## Install required packages

```bash
pip install pandas numpy matplotlib seaborn plotly dash scikit-learn folium
```

## Open the notebooks

Launch Jupyter Notebook or JupyterLab and open the notebook files.

## Run the dashboard

```bash
python spacex-dash-app.py
```

The dashboard will be available in your browser at:

```
http://127.0.0.1:8050/
```

---

# Future Improvements

Future enhancements may include:

- Collecting additional launch features
- Deploying the dashboard online
- Using ensemble models such as Random Forest and XGBoost
- Automating data updates using the SpaceX API

---

# Author

**Bakshi Danish**

GitHub Username: **bakshidanish11-svg**

GitHub Profile:
https://github.com/bakshidanish11-svg

IBM Data Science Professional Certificate – Capstone Project

July 2026

---

## Acknowledgements

This project was completed as part of the **IBM Data Science Professional Certificate** offered through Coursera.

Special thanks to IBM and SpaceX for providing the datasets, APIs, and learning resources used throughout this project.
