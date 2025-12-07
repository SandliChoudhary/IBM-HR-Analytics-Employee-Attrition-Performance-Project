# 🧑‍💼 IBM HR Analytics — Employee Attrition & Performance Project

## 🧩 Introduction  
Employee attrition is one of the most critical challenges for organizations, especially in competitive industries.  
This project analyzes the **IBM HR Employee Attrition & Performance Dataset** using R programming to uncover patterns and factors that influence employee turnover.

The aim of this study is to examine how variables such as **monthly income, job satisfaction, age, promotions, working years, and performance rating** impact employee attrition.  
Through exploratory analysis and visualizations, we identify trends and relationships that help HR teams understand workforce behavior.

Multiple visualizations such as **density plots, pair plots, scatter plots with regression lines, and categorical analysis** were designed to highlight key insights.  
The entire analysis was compiled into a structured R project and published for public viewing.

This project provides a clear understanding of how demographic and job-related factors correlate with attrition and how organizations can use analytics to improve retention.

---

## ❓ Problem Statement  
> Organizations face increasing challenges in retaining talent and understanding the factors behind employee turnover.  
> HR data is often complex and multi-dimensional, making it difficult to identify which employee attributes strongly influence attrition.  
>  
> **Goal:** To analyze the IBM HR dataset and uncover insights about employee attrition by studying income levels, job satisfaction, experience, promotions, and performance indicators.

---

## 🔬 Research Questions & Key Findings  

### 🔍 Research Questions and Findings

1. **What demographic and job characteristics show higher attrition rates?**  
   Younger employees with lower income, fewer working years, and minimal growth opportunities showed the highest attrition.

2. **Does salary significantly influence employee turnover?**  
   Yes. Employees with lower monthly income had a higher probability of leaving the organization.

3. **How does job satisfaction impact attrition?**  
   Lower job satisfaction ratings strongly correlated with higher turnover.

4. **Do promotions affect performance and retention?**  
   Employees with fewer or delayed promotions demonstrated higher attrition trends.

5. **Is there a relationship between age, total working years, and salary?**  
   A positive correlation was found — older employees tend to have more experience and higher income.

6. **Which job roles experience the most and least attrition?**  
   Sales roles and entry-level positions showed higher attrition, while senior-level roles showed stability.

---

## 🧾 Dataset Description  
- **Source:** IBM HR Analytics — Kaggle  
- **Records:** 1,470 employees  
- **Variables:** 35 HR attributes including:  
  - Age  
  - Monthly Income  
  - Total Working Years  
  - Years at Company  
  - Job Satisfaction  
  - Job Role  
  - Attrition  
  - OverTime  
  - Promotion History  
  - Performance Rating  

---

## ⚙️ Data Preprocessing  
- Cleaned and inspected dataset using `str()`, `summary()`, and `skimr`.  
- Detected no missing values — dataset was complete.  
- Converted numeric categorical variables into meaningful factors such as:  
  - Job Satisfaction  
  - Environment Satisfaction  
  - Job Involvement  
  - Performance Rating  
- Created new variables for analysis where required.  
- Focused on **visual analysis and interpretation**.

---

## 📈 Steps Performed in R  

1. **Data Loading & Inspection**  
   - Imported data using `read_csv()`  
   - Performed structural analysis and summary statistics  

2. **Feature Engineering**  
   - Converted numeric ratings to categorical labels  
   - Grouped variables for comparison  

3. **Exploratory Data Analysis (EDA)**  
   - Visualized distributions  
   - Identified high-attrition groups  
   - Compared income vs attrition  

4. **Visualizations Created:**  
   - Density Plot (Monthly Income vs Attrition)  
   - Scatter Plot with Regression Line  
   - Pair Plots (Age, Salary, Experience)  
   - Bar Plots for Categorical Attributes  
   - Facet Plots (Promotion vs Income)  

---

## 💡 Insights & Findings  

- **Income Impact:**  
  Lower income employees had the highest attrition rates.

- **Experience Trend:**  
  As total working years increase, attrition decreases.

- **Age Factor:**  
  Younger employees tend to switch jobs more frequently.

- **Promotion Effect:**  
  Limited promotions or long gaps negatively impact retention.

- **Job Satisfaction:**  
  Higher satisfaction levels correlate with reduced attrition.

- **Work–Life Balance:**  
  Overtime employees showed significantly higher attrition.

---

## 🧠 Conclusion  
The IBM HR Analytics Project highlights the key drivers behind employee attrition and provides actionable insights for HR departments.  
Income, experience, job satisfaction, and promotion frequency play major roles in determining whether an employee stays or leaves.  

This analysis demonstrates how data-driven HR decisions can reduce attrition and improve workplace satisfaction.

---

## 🧮 Tools Used  
- **R Programming**  
- **ggplot2**  
- **dplyr**  
- **tidyr**  
- **readr**  
- **corrplot / GGally**  
- **R Markdown / RPubs**

---

## 🧰 Future Enhancements  
- Build a predictive model (Logistic Regression / Random Forest)  
- Add shapefile-based HR geospatial mapping  
- Create an interactive Shiny Dashboard  
- Automate report generation for HR managers  

---


