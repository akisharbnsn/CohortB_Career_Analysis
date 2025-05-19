# CohortB_Career_Analysis
# 🏆 Best Workplace in Atlanta: Nominee Data Evaluation

## 📖 Overview

**Bango**, a leading medical device manufacturing company, was nominated for the **Best Workplace in Atlanta** award by **The Knowledge House (TKH)**. In support of the evaluation process, TKH data analysts conducted a data-driven review of the company’s HR records to uncover insights into what drives employee retention and performance. 

The analysis focuses on four award criteria:
- **Turnover and Retention**
- **Performance Review Practices**
- **Compensation Equality**
- **Overall Employee Satisfaction**

This repository contains the data exploration, cleaning, and visualization process used to help the TKH board determine Bango’s eligibility to advance in the competition.

---

## 🧠 Key Business Questions & Categories

### 📉 Turnover and Retention
- Which recruitment sources are linked to higher retention?
- What are the most common termination reasons?
- How do termination reasons vary by:
  - Department
  - Tenure
  - Performance score

### 📊 Performance Review Practices
- How do absenteeism and lateness impact performance scores across departments?
- Do employees in higher-level job titles receive higher performance scores and salaries?
- Are these trends consistent across departments?

### 💰 Compensation Equality
- How do salaries vary across:
  - Race
  - Age
  - Marital status
  - Gender
- Are there instances of salary discrimination between genders who work in the same department?

### 😀 Employee Satisfaction
- What departments or managers have the highest levels of employee satisfaction?
- Is employee satisfaction associated with turnover?

---

## 🗂️ Dataset Information

The dataset contains HR records across the following columns:

| Column Name                  | Description                                            |
|-----------------------------|--------------------------------------------------------|
| Employee_Name               | Employee full name (used for internal reference only) |
| EmpID                       | Unique employee ID                                     |
| GenderID, Sex               | Encoded and textual gender information                |
| MaritalStatusID, MaritalDesc| Encoded and textual marital status                    |
| RaceDesc                    | Race/ethnicity                                         |
| DOB                         | Date of birth                                          |
| DateofHire, DateofTermination | Employment start/end dates                          |
| EmploymentStatus, TermReason| Employment state and reason for termination            |
| Salary                      | Annual salary in USD                                   |
| PositionID, Position        | Encoded and full job title                             |
| DeptID, Department          | Encoded and full department name                       |
| PerformanceScore            | Performance rating (e.g., "Exceeds Expectations")      |
| LastPerformanceReview_Date  | Date of last formal performance review                 |
| EngagementSurvey            | Self-reported engagement score (0–5)                   |
| EmpSatisfaction             | Self-reported satisfaction score (0–5)                 |
| SpecialProjectsCount        | Number of special projects handled                     |
| DaysLateLast30              | Days late in the past 30 days                          |
| Absences                    | Total number of recorded absences                     |
| ManagerName, ManagerID      | Supervisor identity information                        |
| RecruitmentSource           | Method by which employee was hired                     |
| FromDiversityJobFairID      | Diversity hiring flag                                  |
| CitizenDesc                 | Citizenship status                                     |
| Zip, State                  | Location information                                   |

---

## 🔧 Tools & Technologies

- **Python** (pandas, seaborn, matplotlib)
- **Jupyter Notebooks**
- **SQL** for preprocessing and query-based summaries
- **Data visualization libraries** for exploratory analysis

---

## 📈 How to Use This Project

1. Clone this repo and open the EDA notebook.
2. Load the dataset and run all cells to explore the structured analysis.
3. Navigate by category using notebook headers or table of contents.
4. Optional: Connect to a database or visualization dashboard for extended reporting.

---

## ✅ Outcome

The findings of this analysis helped TKH determine that Bango met several key indicators of a healthy, equitable, and productive workplace. The data-driven approach ensured transparency and integrity in the award evaluation process.

---

## 👩🏽‍💻 Author
**Akisha Robinson**  
Data Analyst & Fellow at The Knowledge House  
_Lifting as I climb. Empowering through data._  
