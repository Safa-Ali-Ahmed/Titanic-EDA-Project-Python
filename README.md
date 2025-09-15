# Titanic - Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project explores the **Titanic: Machine Learning from Disaster** dataset (Kaggle).  
The goal is to practice **data cleaning, exploration, and visualization** using Python.  

We analyze survival patterns based on features like **gender, class, age**, and visualize key insights.

---

## ⚙️ Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🔍 Steps Performed

### 1. Data Cleaning
- Handled missing values:
  - Filled `Age` with **median** (robust to outliers).
  - Filled `Embarked` with **mode** (most frequent port).
  - Dropped `Cabin` (too many missing values).
- Converted data types:
  - `Survived` → categorical  
  - `Pclass` → categorical
- Checked for duplicates and removed them if present.

### 2. Exploratory Data Analysis (EDA)
- Summary statistics for numerical & categorical features.
- Outlier detection using **boxplots**.
- Cross-tabulations (e.g., survival by gender & class).
- Correlation analysis.

### 3. Data Visualization
- Bar plots for survival distribution.
- Heatmap for missing values.
- Correlation heatmap.
- Distribution plots for key features (Age, Fare).
- Survival rate comparisons by gender & class.

---

## 📊 Key Insights
- **Women had higher survival rates than men.**
- **First-class passengers** survived at higher rates than second/third class.
- Younger passengers (children) were more likely to survive.
- Missing values in `Cabin` made it unsuitable for analysis.
