
# Employees data Analysis Project

This project explores employee salary data from ABC Company, consisting of 458 rows and 9 columns. The objective was to preprocess the dataset, analyze employee attributes, and present findings through clear visualizations. The work demonstrates proficiency in Python programming, data preprocessing, exploratory analysis, and effective communication of insights.

---

## 📊 Preprocessing Steps
- **Missing Values (Salary):**  
  - Filled missing salary values using the **median** (robust against outliers).  
  - Alternative approach: group-wise median imputation by position/team.  

- **Missing Values (College):**  
  - Filled missing college entries using the **mode** (most frequent value).  
  - Group-wise mode imputation was also considered for more context-aware filling.  

- **Age Categorization:**  
  - Created four age groups: **20–30, 31–40, 41–50, 51–60** using `pd.cut`.  
  - This enabled grouped analysis and visualization of age demographics.  

- **Column Management:**  
  - Dropped unnecessary columns when required using `df.drop(columns=[...])`.  

---

## 📈 Analysis Tasks
1. **Predominant Age Group**  
   - Categorized employees into age groups.  
   - Visualized distribution using donut charts and lollipop charts.  
   - Identified the most common age group in the dataset.  

2. **Salary Expenditure by Team**  
   - Aggregated salary expenditure per team.  
   - Built **horizontal lollipop charts** with professional styling to show expenditure distribution.  

3. **Correlation Between Age and Salary**  
   - Explored relationship using scatterplots with regression lines.  
   - Built **density plots, hexbin plots, and jointplots** to visualize clustering and trends.  
   - Tested alternative best-fit lines (linear, polynomial, LOWESS, spline) to model the relationship.  

---

## 🎨 Graphical Representations
- **Donut Chart:** Age group distribution with counts and percentages.  
- **Lollipop Chart:** Salary expenditure by team (horizontal orientation, bright professional colors).  
- **Scatterplot + Regression Line:** Correlation between Age and Salary.  
- **pie chart **: Percentage distribution of employees by team
- **Bar Diagram**: percentage distribution of employees by position
---

## 💡 Insights Gained
- Majority of employees fall in the **20–30 age group**, indicating a younger workforce.  
- Certain teams consume a **disproportionate share of salary expenditure**, highlighted in lollipop charts-.  
- A **positive correlation** exists between Age and Salary, with salaries tending to increase with age.  
- Density plots reveal clustering of salaries in specific age ranges, supporting the regression findings.  

---

## ⚙️ Tools & Technologies
- **Python** (pandas, numpy, seaborn, matplotlib, statsmodels, scipy)  
- **Jupyter Notebook** for interactive analysis and documentation  
- **GitHub** for version control and project submission  

---

## 📂 Repository Structure
```
salary-analysis-project/
│
├── data/
│   └── salary_data.csv        # Dataset
│
├── salary_analysis.ipynb      # Jupyter Notebook with code & documentation
├── README.md                  # Project overview
├── .gitignore                 # Ignore unnecessary files
└── LICENSE                    # MIT License
```

---

## 📜 License
This project is licensed under the **MIT License** – free to use, modify, and distribute with attribution.



