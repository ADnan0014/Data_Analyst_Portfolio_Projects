# Movie Correlation Analysis (Python Data Analysis Project)

## Project Overview

This project analyses a movie dataset to find which factors influence movie earnings.  
The analysis focuses on identifying correlations between different movie features such as budget, votes, score, and gross revenue.

The goal of this project is to practice data cleaning, exploratory data analysis, and correlation analysis using Python.

---

## Tools Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## Dataset Features

The dataset includes information about movies such as:

- Movie Name  
- Genre  
- Rating  
- Release Year  
- Score  
- Votes  
- Budget  
- Gross Earnings  
- Director  
- Company  
- Runtime  

---

## Project Steps

### 1. Data Loading

The movie dataset was loaded using Pandas.

### 2. Data Exploration

Initial exploration was done using:

- `head()`
- `dtypes`
- checking missing values

### 3. Data Cleaning

Some columns were converted to proper data types.  
A new column for the correct year was created from the release date.

### 4. Data Visualization

Scatter plots and regression plots were used to visualise the relationship between:

- Budget and Gross Earnings

### 5. Correlation Analysis

Correlation analysis was performed to identify relationships between numeric variables.

A heatmap was used to visualise the correlation matrix.

### 6. Feature Encoding

Categorical columns were converted into numeric codes to include them in the correlation analysis.

---

## Key Insights

The analysis showed that:

- The budget has a strong correlation with Gross Earnings  
- Votes also have a strong correlation with Gross Earnings  
- Production company has low correlation with earnings  

This suggests that higher budgets and higher audience engagement often lead to higher movie revenue.

---

## Project Goal

This project is part of my Data Analyst learning journey and portfolio.  
It demonstrates my ability to perform data cleaning, exploratory data analysis, and correlation analysis using Python.
