# 📊 Data Professional Survey Breakdown – Power BI Dashboard


## 🧠 Project Overview

This Power BI project provides a **comprehensive breakdown of survey data** collected from data professionals around the world.
It visualizes demographics, job satisfaction, salaries, and programming language preferences, offering actionable insights into the **data industry landscape**.

---

## 🎯 Objective

To analyze and visualize the professional trends of data practitioners, including:

* Country-wise distribution
* Average salaries by job role and gender
* Programming language preferences
* Work-life balance and salary satisfaction levels

---

## 📂 Dataset Information

**File Used:** `Data Professional Job Survey.xlsx`
**Source:** Survey dataset (Excel format) containing responses from 630 participants.

### 📑 Key Columns:

* `Country`
* `Job Title`
* `Average Salary`
* `Favorite Programming Language`
* `Happiness with Work/Life Balance`
* `Happiness with Salary`
* `Gender`
* `Age`

---

## ⚙️ Tools & Technologies

| Tool                           | Purpose                                          |
| ------------------------------ | ------------------------------------------------ |
| 🟡 Microsoft Power BI          | Data cleaning, transformation, and visualization |
| 📘 Microsoft Excel             | Data source file                                 |
| 📊 DAX                         | Calculations and measures                        |
| 🎨 Power BI Visualization Pane | Custom visuals and formatting                    |

---

## 🪜 Step-by-Step Project Workflow

### 1️⃣ Importing the Data

* Imported the Excel file (`Data Professional Job Survey.xlsx`) into Power BI.
* Previewed all sheets and selected the relevant table for analysis.

### 2️⃣ Data Cleaning (Power Query)

* Removed unnecessary columns.
* Handled missing and inconsistent values (e.g., blank salaries, job titles).
* Renamed columns for readability.
* Ensured correct data types (e.g., numeric for salary, text for job titles).

### 3️⃣ Data Transformation

* Created calculated columns and measures such as:

  * `Average of Average Salary`
  * `Count of Survey Takers`
  * `Average Age`
* Used **DAX functions** to calculate averages and percentages by category.

### 4️⃣ Data Modeling

* Verified relationships between tables (if multiple sheets used).
* Ensured a star schema model for optimal performance.

### 5️⃣ Dashboard Design

Built an **interactive and visually appealing dashboard** with the following visuals:

| Visualization               | Insight                                     |
| --------------------------- | ------------------------------------------- |
| 🌍 **Treemap**              | Country-wise distribution of survey takers  |
| 💼 **Bar Chart**            | Average salary by job title                 |
| 🧑‍🤝‍🧑 **Donut Chart**    | Average salary comparison by gender         |
| 💻 **Stacked Column Chart** | Favorite programming languages by job title |
| 😊 **Gauge Charts**         | Happiness with work-life balance and salary |
| 🔢 **Cards**                | Total survey takers and average age         |

### 6️⃣ Formatting & Aesthetics

* Applied a **consistent color theme** using Power BI’s formatting pane.
* Added **titles, labels, and KPIs** for clarity.
* Enhanced layout alignment and spacing for professional presentation.

---

## 📈 Key Insights

* **Python** dominates as the favorite programming language.
* **Data Scientists** have the highest average salary.
* **Work-life balance** scored better (5.74/10) than **salary satisfaction** (4.27/10).
* **Males** slightly out-earn **females** on average.
* Most participants are aged around **30 years**.

---

## 📘 Learnings

This project enhanced my understanding of:

* Power BI data cleaning and transformation workflows.
* DAX measure creation for dynamic insights.
* Dashboard design and storytelling with data visualization.

---

## 🚀 Future Improvements

* Add filters for **country**, **job role**, and **language**.
* Include time-series trends (if year-wise data available).
* Integrate Power BI Service for interactive online sharing.

---

## 💡 Conclusion

The **Data Professional Survey Dashboard** delivers meaningful insights into the global data community.
It combines **clean data modeling**, **effective DAX usage**, and **intuitive visuals** to create an informative and professional report.

---

## 🧾 Repository Contents

```
📁 Data-Professional-Survey-Breakdown/
│
├── 📊 Dashboard.png                 # Power BI dashboard screenshot
├── 📘 Data Professional Job Survey.xlsx  # Original dataset
├── 📄 README.md                    # Project documentation (this file)
└── 📁 PowerBI_Project.pbix         # Power BI file (if you upload it)
```

⭐ *If you found this project insightful, don’t forget to star the repository!*
