# Pandas Challenge: PyCitySchools  

## Background  
As the new **Chief Data Scientist** for your city's school district, this project focuses on using **Pandas** to analyze school and standardized test data. The goal is to aggregate and interpret data trends to support strategic decisions for school budgets and priorities. This analysis is conducted using **Python** within a **Jupyter Notebook**.

---

## Repository Structure  

The repository is organized as follows:  

```
pandas-challenge/  
│  
├── PyCitySchools/  
│   ├── PyCitySchools.ipynb    # Jupyter Notebook containing the analysis  
│   ├── Resources/             # Folder containing input CSV files  
│   └── analysis/              # Folder for output files and results (optional)  
│  
└── README.md                  # This README file  
```

---

## Objectives  

The analysis uses Pandas to clean, manipulate, and summarize school and student performance data. It provides actionable insights into district-wide and school-specific performance metrics.  

### Deliverables:  
1. **District Summary**:  
   - Total unique schools, students, and budget  
   - Average math and reading scores  
   - Percentage of students passing math, reading, and overall  

2. **School Summary**:  
   - Key metrics for each school (e.g., school type, size, budget, and average scores)  

3. **Performance Analysis**:  
   - Top 5 and bottom 5 performing schools by overall passing percentage  

4. **Grade-Level Performance**:  
   - Average math and reading scores for each grade level by school  

5. **Performance by Spending**:  
   - School performance grouped by spending ranges per student  

6. **Performance by School Size**:  
   - School performance categorized by size (small, medium, large)  

7. **Performance by School Type**:  
   - Metrics broken down by school type (e.g., district vs. charter schools)  

---

## Installation and Usage  

### Prerequisites:  
- Python 3.x  
- Jupyter Notebook  
- Required Libraries: Pandas, NumPy  

### Steps to Run the Analysis:  
1. **Clone the Repository**:  
   ```bash  
   git clone https://github.com/your-username/pandas-challenge.git  
   cd pandas-challenge/PyCitySchools  
   ```  

2. **Install Required Libraries** (if not already installed):  
   ```bash  
   pip install pandas numpy  
   ```  

3. **Run the Notebook**:  
   - Open the Jupyter Notebook:  
     ```bash  
     jupyter notebook PyCitySchools.ipynb  
     ```  
   - Follow the step-by-step code to generate the required analysis.  

4. **View Results**:  
   - Results are displayed within the notebook and can be saved in the `analysis/` folder if required.  

---

## Data Overview  

The analysis uses data from two main CSV files:  

- **Schools Data**: Contains details about each school (e.g., name, type, budget).  
- **Students Data**: Contains individual student scores and associated school details.  

---

## Key Features  

1. **District-Wide Metrics**:  
   - High-level overview of performance across the entire school district.  

2. **School-Specific Insights**:  
   - Metrics such as average scores, passing percentages, and per-student budget efficiency.  

3. **Comparison by Groupings**:  
   - Performance analyzed based on spending ranges, school sizes, and types.  

4. **Grade-Level Trends**:  
   - Drill-down into average math and reading performance by grade at each school.  

5. **Actionable Trends**:  
   - Identify high-performing schools and areas for improvement.  

---

## Observed Trends  

1. **Charter Schools vs. District Schools**:  
   - Charter schools consistently outperform district schools in math and reading scores.  

2. **School Spending**:  
   - Schools with higher per-student spending do not necessarily achieve better performance, suggesting diminishing returns for excessive spending.  

3. **School Size**:  
   - Smaller schools generally perform better, with higher passing rates in both math and reading.  

---
