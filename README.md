# 🚀 SpaceX Falcon 9 Landing Prediction

### Applied Data Science Capstone Project

An end-to-end data science project that analyzes SpaceX Falcon 9 launch data and builds machine learning models to predict whether the rocket's first stage will successfully land.

The project covers the complete data science workflow — from data collection and web scraping to data wrangling, SQL analysis, exploratory data analysis, interactive visualization, feature engineering, and machine learning.

---

## 📌 Project Overview

SpaceX significantly reduces launch costs by reusing the first stage of its Falcon 9 rockets.

The objective of this project is to investigate the factors associated with successful first-stage landings and develop a classification model capable of predicting landing success.

### Key Questions

* Which launch sites have the highest success rates?
* How does payload mass affect landing success?
* How has Falcon 9 landing success changed over time?
* Which launch and payload characteristics are associated with successful landings?
* Which machine learning algorithm provides the best predictive performance?

---

## 🎯 Project Objectives

The project follows an end-to-end data science workflow:

1. Collect launch data from the SpaceX API
2. Extract additional launch information through web scraping
3. Clean and transform the collected datasets
4. Perform exploratory data analysis
5. Analyze the data using SQL
6. Engineer features for machine learning
7. Build interactive geographic visualizations
8. Develop an interactive Plotly Dash dashboard
9. Train and compare multiple classification models
10. Tune model hyperparameters using GridSearchCV
11. Evaluate model performance on unseen test data

---

## 🛠️ Technologies & Tools

| Category            | Technologies                |
| ------------------- | --------------------------- |
| Programming         | Python                      |
| Data Analysis       | Pandas, NumPy               |
| Visualization       | Matplotlib, Seaborn, Plotly |
| Database            | SQLite / SQL                |
| Web Scraping        | BeautifulSoup               |
| API                 | SpaceX REST API             |
| Machine Learning    | Scikit-learn                |
| Model Tuning        | GridSearchCV                |
| Geospatial Analysis | Folium                      |
| Dashboard           | Plotly Dash                 |
| Development         | Jupyter Notebook            |
| Version Control     | Git & GitHub                |

---

## 📂 Project Structure

```text
Data_Science_Capstone/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── notebooks/
│   ├── 01_data_collection_api.ipynb
│   ├── 02_web_scraping.ipynb
│   ├── 03_data_wrangling.ipynb
│   ├── 04_eda_sql.ipynb
│   ├── 05_eda_visualization.ipynb
│   ├── 06_launch_site_analysis.ipynb
│   └── 07_machine_learning_prediction.ipynb
│
├── data/
│   └── spacex_launch_geo.csv
│
├── database/
│   └── spacex.db
│
├── app/
│   └── spacex_dash_app.py
│
├── reports/
│   └── Data_Science_Capstone_Report.pdf
│
└── assets/
    └── spacex_dash_app_screenshot.png
```

---

## 🔬 Methodology

### 1. Data Collection

Historical Falcon 9 launch information was collected using the SpaceX REST API.

Additional launch records were extracted through web scraping using BeautifulSoup.

The collected data included information such as:

* Launch sites
* Payload information
* Booster versions
* Orbit types
* Flight numbers
* Landing outcomes
* Launch dates

---

### 2. Data Wrangling

The raw datasets were cleaned and transformed before analysis.

Key preprocessing steps included:

* Handling missing values
* Removing unnecessary fields
* Converting data types
* Creating training labels
* Transforming categorical variables
* Preparing features for machine learning

---

### 3. Exploratory Data Analysis

Exploratory analysis was performed using Python visualization libraries to identify patterns and relationships within the launch data.

The analysis investigated relationships between:

* Payload mass and landing success
* Launch site and landing success
* Number of flights and success rate
* Orbit type and landing outcome
* Launch year and success rate

---

### 4. SQL Analysis

The dataset was loaded into a relational database and analyzed using SQL.

SQL queries were used to answer business and analytical questions involving:

* Launch site performance
* Payload characteristics
* Launch outcomes
* Success rates
* Historical trends

---

### 5. Geospatial Analysis

Folium was used to create interactive maps showing Falcon 9 launch locations.

The geographic analysis helped investigate the relationship between launch locations and landing outcomes.

---

### 6. Interactive Dashboard

A Plotly Dash application was developed to provide an interactive interface for exploring the launch dataset.

The dashboard allows users to interact with launch information through filters and visualizations.

### Dashboard Preview

![SpaceX Dashboard](assets/spacex_dash_app_screenshot.png)

---

## 🤖 Machine Learning

The final stage of the project focused on predicting first-stage landing success.

Several classification algorithms were evaluated, including:

* Logistic Regression
* Support Vector Machine
* K-Nearest Neighbors
* Decision Tree Classifier

Hyperparameter optimization was performed using `GridSearchCV`.

The dataset was split into training and testing sets before model evaluation.

---

## 📊 Model Results

| Model                  | Test Accuracy |
| ---------------------- | ------------: |
| Decision Tree          |    **94.44%** |
| Support Vector Machine |        83.33% |
| K-Nearest Neighbors    |        83.33% |

### Best Performing Model

The **Decision Tree Classifier** achieved the highest test accuracy of **94.44%** on the evaluated test set.

This model provided the strongest predictive performance among the evaluated algorithms.

---

## 💡 Key Findings

The analysis demonstrated that Falcon 9 landing success can be investigated using a combination of:

* Historical launch data
* Payload characteristics
* Launch site information
* Orbit information
* Flight history
* Machine learning classification

The project also demonstrates how multiple data science techniques can be combined into a single end-to-end analytical workflow.

---

## 📈 Skills Demonstrated

This project demonstrates practical experience with:

* Data collection through APIs
* Web scraping
* Data cleaning and preprocessing
* Exploratory data analysis
* SQL data analysis
* Feature engineering
* Statistical and visual analysis
* Geospatial visualization
* Interactive dashboards
* Classification algorithms
* Model evaluation
* Hyperparameter tuning
* Python data science workflows

---

## 📄 Project Report

A detailed project report is available in:

```text
reports/Data_Science_Capstone_Report.pdf
```

---

## 🎓 Certification

This project was completed as the final capstone project for the:

**IBM Data Science Professional Certificate**

Completed through Coursera.

---

## 👨‍💻 Author

**Muhammad Shaaf**

Data Science | Machine Learning | SQL | Python | Power BI

GitHub: [MuhammadShaaf](https://github.com/MuhammadShaaf)

---

## ⭐ Project Purpose

This project was developed as a portfolio demonstration of an end-to-end data science workflow, combining data collection, data analysis, visualization, SQL, interactive dashboards, and predictive machine learning.
