# 🏆 Best Workplace in Atlanta: Nominee Data Evaluation

## Overview

**Bango**, a leading medical device manufacturing company, was nominated for the **Best Workplace in Atlanta** award by **The Knowledge House (TKH)**. In support of the evaluation process, TKH data analysts conducted a data-driven review of the company’s HR records to uncover insights into what drives employee retention and performance. 

The analysis focuses on four award criteria:
- **Turnover and Retention**
- **Performance Review Practices**
- **Compensation Equality**
- **Overall Employee Satisfaction**

This repository contains the data exploration, cleaning, and visualization process used to help the TKH board determine Bango’s eligibility to advance in the competition.

---
## Key Analytical Questions & Categories

### Turnover and Retention
- Which recruitment sources are linked to higher retention?
- What are the most common termination reasons?
- How do termination reasons vary by:
  - Department
  - Tenure
  - Performance score

- Summary: This notebook focuses on how recruitment sources, termination reasons, and performance patterns impact employee retention and satisfaction. Through this analysis Bango was able to conclude that the company website had the highest retention rate, while hires from search engines -Google- showed the highest termination rate. This highlighted the importance of the company's continued initiatives of targeted and intentional recruitment strategies. Bango also wanted to explore why terminated (voluntary or involuntary) employees left the company, and the role that employee satisfaction and performance scores impacted those decisions. The data reveals that most employees who left for another opportunity were ironically top performers with high company satisfaction scores. This suggested that while dissatisfaction is typically considered a primary reason for employees leaving, it was not the case for Bango, suggesting there was limited growth opportunities instead. As a next step, Bango is encouraged to refine hiring sources and support upward mobility in career development. 

### Performance Review Practices
- How do absenteeism and lateness impact performance scores across departments?

- Summary: Analyzed how absenteeism and lateness impact employee performance across departments. The dataset was first cleaned through EDA and ensured overall data quality. Univariate and bivariate analyses were performed to explore the distribution and relationships between key variables like absences, lateness, and performance scores. The data was then grouped by department and performance score to calculate and visualize average attendance patterns. The analysis revealed that lower performing employees had consistently higher absences and lateness across departments. In contrast, high performing employees showed strong attendance and punctuality. These findings highlight absenteeism and lateness as important behavioral indicators of performance. As a next step, companies are encouraged to monitor attendance patterns regularly and use them to identify and support employees at risk of performance decline.


### Compensation Equality
- How do salaries vary across:
  - Race
  - Age
  - Marital status
  - Gender
- Are there instances of salary discrimination between genders who work in the same department?

- Summary:

### Employee Satisfaction
- Which departments or managers have the highest employee satisfaction, and is this low satisfaction scores linked to employees' reasons for leaving?

- Summary: The Software Engineering and Sales departments have the highest employee satisfaction scores (4.09 and 4.03, respectively). Janet King received the highest manager ratings in 2 out of 5 departments, including a perfect score in the Executive Office, though her ratings were based on only one employee per department.   Employee satisfaction is not evenly balanced across the departments, with noticeable differences by department and manager. However, current and terminated employees reported nearly identical satisfaction scores (3.88 vs. 3.89), suggesting that satisfaction may not be a key driver of turnover at Bango.
---

## Outcome & Next Steps

The findings of this analysis helped TKH determine that Bango met several key indicators of a healthy, equitable, and productive workplace. The data-driven approach ensured transparency and integrity in the award evaluation process.

---