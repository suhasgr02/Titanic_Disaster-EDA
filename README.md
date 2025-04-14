# Titanic Disaster EDA

## Overview

This project focuses on **Exploratory Data Analysis (EDA)** of the Titanic disaster dataset. The analysis aims to uncover trends, patterns, and relationships among the features to better understand survival outcomes.

## Objectives
- Perform an in-depth exploratory analysis of the Titanic dataset.
- Visualize the data to identify trends and patterns.
- Provide insights into survival rates based on various factors like gender, age, class, and fare.

## Dataset

- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- **Files Used**:
  - `train.csv`: Training dataset containing survival information.
  - `test.csv`: Test dataset without survival information.

## Tools and Libraries
- **Programming Language**: Python
- **Libraries**:
  - `Pandas`: Data manipulation and analysis.
  - `NumPy`: Numerical operations.
  - `Matplotlib` & `Seaborn`: Data visualization.

## Key Analyses and Insights
1. **Data Overview**:
   - Summary statistics using `.info()` and `.describe()`.
   - Missing value analysis.

2. **Feature Distributions**:
   - Visualized age and fare distributions using histograms.
   - Observed that most passengers were younger (20–30 years) and paid lower fares.

3. **Survival by Gender and Class**:
   - Higher survival rates for females compared to males.
   - Passengers in 1st class had better survival outcomes than those in lower classes.

4. **Correlation Analysis**:
   - Strong inverse correlation between `Pclass` and `Fare`.
   - Moderate correlation between `Survived` and features like `Pclass` and `Fare`.

5. **Visualizations**:
   - Pairplots to explore relationships between numerical variables.
   - Heatmaps to identify correlations.
   - Boxplots to compare survival with fare and age.

## Visuals and Outputs
- Histograms and KDE plots for distributions.
- Bar plots showing survival by class and gender.
- Heatmap for correlation analysis.
- Boxplots for survival vs. continuous features.

## How to Run
1. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Titanic_Disaster_EDA.ipynb
   ```
3. Run all cells to reproduce the analysis.

## Observations and Findings
- Gender and class were the most influential factors in determining survival.
- Younger passengers had slightly better survival rates, particularly in higher classes.
- Fare played a role, with higher-paying passengers having better survival outcomes.

## Files in the Repository
- `Titanic_Disaster_EDA.ipynb`: Jupyter Notebook containing the complete analysis.
- `train.csv` & `test.csv`: Datasets for analysis.
- `Titanic_EDA_Report.pdf`: Summary report of the findings.

## Contributing
Contributions are welcome! Please fork this repository and create a pull request.

---

Let me know if there are specific details you'd like to add or adjust!
