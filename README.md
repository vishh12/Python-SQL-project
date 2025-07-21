
# 📊 Job Market Insights: Data Analyst Job Postings Analysis using SQL and Python

## 📝 **Project Objective**
Analyze job market data for **Data Analyst roles** to uncover insights about:
- **Salary trends**
- **Company hiring patterns**
- **In-demand skills**

The analysis combines **Python** for data cleaning and visualization with **SQL** for querying structured insights.

---

## 🛠 **Tools & Technologies Used**
- **Python** (Pandas, NumPy)  
- **SQLAlchemy + SQLite**  
- **SQL**  
- **Matplotlib, Seaborn** (Visualizations)  
- **Jupyter Notebook**

---

## 📂 **Dataset Details**
- **Source:** Likely Glassdoor / Kaggle job listings  
- **Records:** 2,252 job postings  
- **Main Features:**
  - Job Title
  - Company Name
  - Location (City / State)
  - Salary Estimate
  - Industry
  - Type of Ownership
- **Engineered Features:**
  - `min_salary`, `max_salary`, `avg_salary`
  - `Job_Title_Group`
  - `Skills` extraction (Python, SQL, Excel, Tableau, etc.)
  - Cleaned city and state columns

---

## 🔧 **Project Structure**
```
📁 data_analysis_by_sql.ipynb         # SQL-based analysis via Python
📁 datacleaning.ipynb                 # Data cleaning and preparation steps
📁 Data_Science_Jobs_in_India.csv     # Original dataset
📁 final_cleaned_data.csv             # Cleaned dataset ready for analysis
📁 cleaned_analyst_data.csv           # Intermediate cleaned dataset
📁 DataAnalyst.csv                    # Supporting dataset for reference
📁 Job Posting Analysis.docx          # Documentation with findings
```

---

## 🔍 **Analysis Performed**
### ✅ **Data Cleaning (Python)**
- Removed nulls, standardized formats
- Extracted structured fields: salaries, cities, states
- Generated salary ranges & job title groups

### ✅ **Data Analysis (SQL in Python)**
- Company-wise job posting analysis
- Average salary insights by company, industry, and job role
- State & city-level demand concentration
- Skills frequency analysis for Data Analyst roles

---

## 📈 **Key Findings**
- **Top Hiring Cities:** New York, San Francisco, Chicago
- **Top Hiring Companies:** Identified via SQL queries
- **Average Salary Insights:** Senior roles and certain industries (Tech, Finance) offer higher averages.
- **In-demand Skills:**  
  - Most frequent: **SQL, Python, Excel, Tableau, Statistics**  
  - Visualized skill distribution using pie charts.
- **Location Trends:** State-level and city-level demand insights

---

## 🖼 **Sample Visualizations**
- Salary distribution charts
- Skill demand pie charts
- Industry vs. salary comparisons

---

## 🚀 **How to Run This Project**
1. Clone this repository:
   ```bash
   git clone https://github.com/vishakhamore/data-analyst-job-posting-analysis.git
   ```
2. Open `datacleaning.ipynb` in Jupyter Notebook for data cleaning steps.
3. Open `data_analysis_by_sql.ipynb` to explore SQL-based analysis.
4. Review final insights in `Job Posting Analysis.docx`.

---

## 📬 **Connect with Me**
- [LinkedIn](https://www.linkedin.com/in/vishakha-more1205)
- [GitHub](https://github.com/vishh12)
