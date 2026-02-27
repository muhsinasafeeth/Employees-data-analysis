
# Salary Analysis Project

This project explores employee salary data from ABC Company, consisting of 458 rows and 9 columns. The objective was to preprocess the dataset, analyze employee attributes, and present findings through clear visualizations. The work demonstrates proficiency in Python programming, data preprocessing, exploratory analysis, and effective communication of insights.

---

## Overview

The dataset provides information about employees across various teams and positions. The project involved cleaning the data, handling missing values, categorizing age groups, and investigating salary expenditure patterns. Graphical representations were used to highlight trends and correlations, making the analysis accessible and professional.

---

## Preprocessing

- Corrected the **height** column by replacing values with random numbers between 150 and 180 to ensure consistency.  
- Handled missing values in the **Salary** column by imputing the median, ensuring robustness against outliers.  
- Filled missing values in the **College** column using the mode (most frequent value).  
- Categorized the **Age** column into four groups: **20–30, 31–40, 41–50, 51–60**.  
- Dropped unnecessary columns when required to streamline the dataset.  

---

## Analysis

1. **Team Distribution**  
   - Calculated the number of employees per team and their percentage split relative to the total workforce.  

2. **Position Segregation**  
   - Segregated employees by position to understand organizational structure.  

3. **Predominant Age Group**  
   - Identified that the majority of employees fall into the **20–30 age group**, indicating a younger workforce.  

4. **Salary Expenditure**  
   - Determined which team and position account for the highest salary expenditure, highlighting resource allocation.  

5. **Correlation Between Age and Salary**  
   - Investigated the relationship between age and salary.  
   - Found a **positive correlation**, with salaries tending to increase with age.  

---

## Visualizations

- **Donut Chart:** Age group distribution.  
- **Lollipop Chart (Horizontal):** Salary expenditure by team.  
- **Treemap:** Salary expenditure by position.  
- **Scatterplot + Regression Line:** Correlation between Age and Salary.  
- **Density Plot (KDE):** Smooth contours showing clustering of Age vs Salary.  
- **Hexbin Plot:** Density visualization using hexagonal bins.  
- **Jointplot (KDE):** Combined density contours with marginal distributions.  

---

## Insights

- The workforce is predominantly young, with most employees in the **20–30 age group**.  
- Certain teams consume a **disproportionate share of salary expenditure**, which may indicate specialized or high-value roles.  
- Salary expenditure varies significantly across positions, with some roles commanding higher costs.  
- A clear **positive correlation** exists between age and salary, though clustering suggests salary growth stabilizes in certain age ranges.  

---

## Tools & Technologies

- **Python** (pandas, numpy, seaborn, matplotlib, statsmodels, scipy)  
- **Jupyter Notebook** for interactive analysis and documentation  
- **GitHub** for version control and project submission  

---

## Repository Structure
licensed under the **MIT License** – free to use, modify, and distribute with attribution.
