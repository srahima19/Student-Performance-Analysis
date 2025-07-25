# 🎓 Student Performance Analysis

This project explores a dataset of students’ academic performance to uncover insights related to gender, test preparation, lunch types, and parental education. The project includes in-depth Exploratory Data Analysis (EDA) using Python and a dynamic Power BI dashboard to visualize findings.

---

## 📊 Project Goals

- Analyze factors affecting student performance across math, reading, and writing.
- Identify performance clusters and demographic trends.
- Build an interactive Power BI dashboard to showcase results visually.

---

## 📁 Dataset

- **Source**: Provided in project file
- **Records**: 1000+ students
- **Features**:
  - `gender`
  - `race/ethnicity`
  - `parental_level_of_education`
  - `lunch`
  - `test_preparation_course`
  - `math_score`
  - `reading_score`
  - `writing_score`

---

## 🔍 EDA Questions Answered

1. Which parental education level is linked with the highest average math score?
2. Is there a significant score difference between males and females across all subjects?
3. How much does completing the test preparation course improve performance in each subject?
4. Which combination of gender, lunch type, and test preparation status produces the top 10% of scores?
5. Does lunch type impact performance uniformly across race/ethnicity groups?
6. What is the correlation between reading and writing scores?
7. Who are the top 5% performers, and what are their demographic profiles?
8. Can we cluster students into performance categories using basic logic?

---

## 🧠 Feature Engineering (Python)

- Created `average_score` for total performance comparison.
- Engineered a `performance_category` column using average score thresholds:
  - High (≥90)
  - Medium (70–89)
  - Low (<70)

---

## 📈 Power BI Dashboard

The dashboard consists of **4 interactive pages**, named as follows:

---

### 📄 **1. Overview**

- 📌 KPI Cards: Total Math, Reading, Writing Scores
- 📊 Clustered Column Chart: Subject-wise scores by gender
- 📉 Bar Chart: Sum of average scores
- 🎛 Slicers: Gender, Race/Ethnicity, Test Preparation Course

---

### 📄 **2. Demographic Analysis**

- 📊 Average Math Scores by Parental Education
- 📊 Average Scores by Lunch Type
- 📊 Impact of Test Preparation on Subject Scores
- 🧾 Table: Top 10% scorers with Gender + Lunch + Test Prep

---

### 📄 **3. Correlation & Score Trends**

- 🔥 Python Heatmap: Correlation between Math, Reading, Writing
- 🧩 Scatter Plot: Reading vs Writing Scores (by Performance Category)
- 📊 Table: Cluster Summary (Low, Medium, High performers)

---

### 📄 **4. Performer Insights**

- 🧾 Table: Top 5% Students with Demographics
- 📊 Bar Charts: Top Performers by Gender, Lunch, Test Prep
- 🥧 Pie Chart: Race Breakdown of Top 5% Students

---

## 📂 Deliverables

- 📓 `Student_Performance_Analysis.ipynb` → Python notebook for EDA
- 📊 `StudentPerformanceDashboard.pbix` → Power BI dashboard file
- 📄 `StudentsPerformance.csv` → Cleaned dataset
- 📝 `README.md` → Project summary

---

## 🚀 Tools Used

- Python (Pandas, Seaborn, Matplotlib)
- Power BI Desktop
- Jupyter Notebook

---

## 📬 Contact

📧 Rahima Ali  
📨 s.rahimaali00@gmail.com

---

## ⭐ If you found this project helpful, feel free to star ⭐ the repository and leave feedback!
