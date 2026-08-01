<div align="center">

# 🚢 Titanic Data Cleaning & Exploratory Data Analysis (EDA)

### 📊 End-to-End Data Cleaning, Preprocessing & Visualization using Python

<img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white">
<img src="https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge">
<img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge">
<img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge">

### ⭐ A complete beginner-friendly Data Analytics project demonstrating Data Cleaning, Data Preprocessing, Exploratory Data Analysis (EDA), Feature Engineering, and Data Visualization using the Titanic Dataset.

</div>

---

# 📖 Project Overview

This project demonstrates a complete **Data Analytics workflow** using the famous **Titanic Dataset**.

The primary objective is to transform raw data into a clean, structured, and analysis-ready dataset by applying industry-standard preprocessing techniques.

After cleaning the dataset, extensive **Exploratory Data Analysis (EDA)** is performed using professional visualizations and statistical summaries to uncover patterns related to passenger survival.

---

# 🎯 Objectives

✔ Load Raw Dataset

✔ Inspect Dataset Structure

✔ Handle Missing Values

✔ Remove Duplicate Records

✔ Convert Data Types

✔ Rename Columns

✔ Feature Engineering

✔ Exploratory Data Analysis (EDA)

✔ Generate Professional Visualizations

✔ Create Summary Tables

✔ Export Clean Dataset

---

# 🛠 Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| Pandas | Data Cleaning & Manipulation |
| NumPy | Numerical Computing |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Google Colab / Jupyter Notebook | Development Environment |

---

# 📂 Dataset Information

**Dataset:** Titanic Passenger Dataset

**Source**

https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv

**Dataset Size**

- 891 Records
- 12 Original Features

---

# 🧹 Data Cleaning Process

The following preprocessing steps were performed:

### ✅ Removed Duplicate Records

Duplicate observations were removed to improve data quality.

---

### ✅ Missing Value Treatment

| Column | Method |
|---------|---------|
| Age | Filled using Median |
| Embarked | Filled using Mode |
| Cabin | Replaced with "Unknown" |

---

### ✅ Data Type Conversion

Converted categorical columns into Category datatype:

- Survived
- Pclass
- Sex
- Embarked

Converted numerical column:

- Age → Integer

---

### ✅ Feature Renaming

Column names were standardized into a clean naming format.

| Original | Renamed |
|----------|-----------|
| PassengerId | passenger_id |
| Survived | survived |
| Pclass | pclass |
| SibSp | siblings_spouses |
| Parch | parents_children |
| Ticket | ticket_number |
| Embarked | embarked_port |

---

# 📈 Exploratory Data Analysis (EDA)

The notebook contains **12 professional visualizations**.

## 📊 Visualizations Included

### Passenger Analysis

- Survival Count
- Survival by Passenger Class
- Survival by Gender
- Survival by Embarkation Port
- Family Size Analysis

---

### Distribution Analysis

- Age Distribution
- Fare Distribution
- KDE Plot
- Violin Plot

---

### Relationship Analysis

- Correlation Heatmap
- Scatter Plot
- Box Plot
- Bar Plot

---

### Pie Charts

- Overall Survival Percentage
- Passenger Distribution by Embarkation Port

---

# 📋 Statistical Summary Tables

The notebook automatically generates:

- Dataset Summary
- Missing Value Report
- Data Type Summary
- Numerical Statistics
- Survival Matrix
- Port-wise Passenger Analysis

---

# 🔍 Key Insights

📌 Female passengers had a significantly higher survival rate.

📌 First-class passengers were more likely to survive.

📌 Higher ticket fares were generally associated with higher survival probability.

📌 Family size influenced survival outcomes.

📌 Missing values were successfully handled without discarding valuable observations.

---

# 📁 Project Structure

```
Titanic-Data-Cleaning-EDA
│
├── Titanic_EDA.ipynb
├── titanic_cleaned.csv
├── README.md
├── requirements.txt
│
├── images
│   ├── survival_count.png
│   ├── heatmap.png
│   ├── violinplot.png
│   ├── scatterplot.png
│   ├── piechart.png
│   └── boxplot.png
│
└── dataset
    └── titanic.csv
```

---

# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Titanic-Data-Cleaning-EDA.git
```

Move into the project directory

```bash
cd Titanic-Data-Cleaning-EDA
```

Install dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# 💻 Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

---

# 📊 Project Workflow

```
Raw Dataset
      │
      ▼
Load Dataset
      │
      ▼
Data Inspection
      │
      ▼
Data Cleaning
      │
      ▼
Handle Missing Values
      │
      ▼
Convert Data Types
      │
      ▼
Feature Engineering
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Statistical Summary
      │
      ▼
Data Visualization
      │
      ▼
Clean Dataset Export
```

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis
- Python Programming
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Feature Engineering
- Data Visualization
- Statistical Analysis
- Data Wrangling
- Problem Solving

---

# 🎓 Learning Outcomes

After completing this project, you will understand:

✔ Cleaning real-world datasets

✔ Handling missing values

✔ Working with categorical data

✔ Feature engineering

✔ Building professional EDA reports

✔ Creating insightful visualizations

✔ Preparing datasets for Machine Learning

---

# 🔮 Future Enhancements

- Machine Learning Prediction Model
- Streamlit Dashboard
- Power BI Dashboard
- Tableau Dashboard
- Interactive Visualizations
- Feature Selection
- Model Evaluation

---

# 👨‍💻 About Me

## Nayan Maity

Aspiring **Data Analyst | Data Scientist | AI & Machine Learning Enthusiast**

I enjoy building data-driven projects that transform raw datasets into meaningful insights through analysis and visualization.

### 📫 Connect with Me

- 💼 LinkedIn: https://linkedin.com/in/YOUR-LINKEDIN
- 💻 GitHub: https://github.com/YOUR-GITHUB
- 📧 Email: YOUR_EMAIL@gmail.com

---

<div align="center">

## ⭐ If you found this project helpful, please consider giving it a Star!

**Happy Coding! 🚀**

</div>
