# HR Employee Insights

Data cleaning and analysis of HR employee records with insights on turnover and performance.

---

## 📁 Dataset

`hr_employee_data.csv`  
Synthetic HR dataset with 1,000 rows. Includes employee demographics, salary, tenure, performance scores, and appraisal history.

> 🔗 Download: [Link to CSV file](#) *(Replace with your file link or path)*

---

## 🛠️ Project Tasks

### 1. Data Cleaning

- Identify and quantify missing values across all columns.
- Apply suitable imputation techniques:
  - Mean or median for numerical columns.
  - Mode or constant values for categorical columns.
  - Drop rows only when data is irrecoverable or critical.

---

### 2. Key Employee Insights

- Average salary by department.
- Departments with the highest turnover (`Left_Company = "Yes"`).
- Average performance score by position.

---

### 3. Performance & Retention Analysis

- Do older employees tend to leave more?
- Relationship between `Years_at_Company` and `Performance_Score`.
- Compare performance scores of employees who left vs. those who stayed.

---

### 4. Appraisal Monitoring

- Number of employees not appraised in the last 2 years.
- Top 10 longest-serving employees and their last appraisal year.

---

### 5. Predictive Hint (Optional)

Use basic business logic to identify employees at risk of leaving (e.g. low salary + low performance).

---

## 🔧 Tools Used

- Python
  - pandas
  - matplotlib
  - seaborn
- Jupyter Notebook

---

## 📌 Outcome

This project demonstrates real-world HR data analysis — transforming raw, incomplete records into actionable insights. The analysis covers employee turnover, performance trends, tenure-based metrics, and simple predictive logic useful for HR decision-making.

---

## 📂 Project Structure
