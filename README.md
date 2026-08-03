<div align="center">

# 🚢 Titanic Data Cleaning & Exploratory Data Analysis (EDA)

### 📊 Data Cleaning, Preprocessing & Visualization using Python

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-Data%20Visualization-blue?style=for-the-badge)

## 🎥 Demo Video

Click below to watch the project demonstration.

[Titanic Data Cleaning & EDA Demo](./Titanic_Project_Demo.mp4)

<img width="1896" height="1007" alt="image" src="https://github.com/user-attachments/assets/40f66cad-686d-4cb4-bf42-28889605da30" />
<img width="1890" height="1019" alt="Screenshot 2026-08-03 091604" src="https://github.com/user-attachments/assets/55600bc9-a1f7-4430-9361-ced4d4b70131" />


**An end-to-end Data Cleaning and Exploratory Data Analysis (EDA) project using the Titanic Dataset.**

</div>

---

# 📌 Problem Statement

Real-world datasets are rarely clean and often contain missing values, duplicate records, inconsistent data types, and poorly formatted feature names. These issues reduce the quality of analysis and negatively impact machine learning models.

The objective of this project is to clean and preprocess the Titanic dataset by handling missing values, removing duplicate records, converting data types, standardizing column names, and preparing the dataset for exploratory data analysis (EDA). The project also aims to visualize passenger characteristics and identify factors influencing survival.

---

# 📂 Dataset Details

**Dataset Name:** Titanic Dataset

**Source:** Kaggle

**Dataset Link**

(https://www.kaggle.com/code/rolandmueller/titanic-dataset-csv)

### Dataset Information

| Attribute | Description |
|-----------|-------------|
| Records | 891 |
| Features | 12 |
| File Format | CSV |
| Domain | Transportation / Survival Prediction |

### Features Used

| Column | Description |
|---------|-------------|
| PassengerId | Unique Passenger ID |
| Survived | Survival Status (0 = No, 1 = Yes) |
| Pclass | Passenger Class |
| Name | Passenger Name |
| Sex | Gender |
| Age | Passenger Age |
| SibSp | Number of Siblings/Spouses |
| Parch | Number of Parents/Children |
| Ticket | Ticket Number |
| Fare | Ticket Fare |
| Cabin | Cabin Number |
| Embarked | Boarding Port |

---

# 🎯 Objectives

- Load the Titanic dataset
- Inspect dataset quality
- Handle missing values
- Remove duplicate records
- Convert appropriate data types
- Rename columns for consistency
- Perform Exploratory Data Analysis (EDA)
- Generate statistical summaries
- Create professional visualizations
- Export a cleaned dataset

---

# ⚙️ Approach

The project follows a structured data preprocessing and analysis pipeline.

## Step 1 — Data Collection

- Imported the Titanic dataset using Pandas.
- Inspected dataset dimensions and missing values.

---

## Step 2 — Data Cleaning

The following preprocessing techniques were applied:

### ✔ Duplicate Removal

- Removed duplicate records.

### ✔ Missing Value Treatment

| Column | Method Used |
|---------|-------------|
| Age | Filled using Median |
| Embarked | Filled using Mode |
| Cabin | Replaced with "Unknown" |

---

### ✔ Data Type Conversion

Converted categorical columns:

- Survived
- Pclass
- Sex
- Embarked

Converted numerical column:

- Age → Integer

---

### ✔ Column Renaming

Renamed columns into readable naming conventions.

Example:

PassengerId → passenger_id

SibSp → siblings_spouses

Parch → parents_children

Embarked → embarked_port

---

## Step 3 — Feature Engineering

Created a new feature:

**Family Size**

```
Family Size = Siblings/Spouses + Parents/Children + 1
```

This feature was later used for survival analysis.

---

## Step 4 — Exploratory Data Analysis (EDA)

Performed multiple visual analyses using:

- Count Plot
- Histogram
- Box Plot
- Violin Plot
- Scatter Plot
- KDE Plot
- Heatmap
- Pie Chart
- Bar Plot

Generated statistical summary tables for:

- Missing Values
- Data Types
- Numerical Statistics
- Survival Matrix
- Port-wise Analysis

---

# 📊 Results

The data cleaning and exploratory analysis produced several meaningful insights.

### Key Findings

✅ Missing values were successfully handled.

✅ Duplicate records were removed.

✅ Dataset was standardized and cleaned.

✅ Female passengers had a significantly higher survival rate than male passengers.

✅ First-class passengers showed the highest survival probability.

✅ Higher ticket fares were generally associated with greater survival chances.

✅ Family size influenced passenger survival.

✅ The cleaned dataset is ready for Machine Learning and predictive modeling.

---

# 📈 Visualizations Included

- Overall Survival Count
- Survival by Passenger Class
- Survival by Gender
- Age Distribution
- Fare Distribution
- Correlation Heatmap
- Family Size Analysis
- Fare Density Plot
- Scatter Plot
- Violin Plot
- Passenger Distribution by Port
- Average Fare Analysis

---

# 📁 Project Structure

```
Titanic-EDA/
│
├── Titanic_EDA.ipynb
├── titanic_cleaned.csv
├── README.md
├── requirements.txt
│
├── dataset/
│   └── titanic.csv
│
└── images/
    ├── heatmap.png
    ├── scatterplot.png
    ├── boxplot.png
    ├── violinplot.png
    └── piechart.png
```

---

# 💻 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

---

# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Titanic-EDA.git
```

Install dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

Run the notebook

```bash
jupyter notebook Titanic_EDA.ipynb
```

---

# 📚 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis
- Data Visualization
- Feature Engineering
- Python Programming
- Statistical Analysis
- Data Wrangling
- Problem Solving

---

# 🚀 Future Improvements

- Build Machine Learning models for survival prediction.
- Develop an interactive dashboard using Streamlit or Power BI.
- Perform feature selection and model evaluation.
- Deploy the project as a web application.

---

# 👨‍💻 Author

## Nayan Maity

**Aspiring Data Analyst | Data Scientist | AI & Machine Learning Enthusiast**

**📧 Email:** maity2nayan@gmail.com

**🔗 LinkedIn:** https://linkedin.com/in/nayan-maity-it-workers

**💻 GitHub:** https://github.com/nayanmai

---

<div align="center">

### ⭐ If you found this project helpful, please give it a Star!

**Thank you for visiting my repository! 🚀**

</div>
