# Employee Performance Tracker

## Introduction

This report outlines the development and implementation of an employee performance evaluation system. The project’s objective was to create a comprehensive system to evaluate and monitor employee performance across various dimensions. By analyzing key performance metrics, the aim was to identify top performers and areas for improvement, thereby enabling data-driven decisions to enhance organizational effectiveness.

## Data Preparation and Cleaning

**Tools Used:** Microsoft Excel

### Data Cleaning:
- **Removing Duplicates:** Ensured there were no duplicate entries to maintain data integrity.
- **Handling Missing Values:** Addressed missing values by either imputing with "Nil" or removing empty rows.
- **Converting Data Types:** Ensured all columns had appropriate data types for accurate analysis.

### Dataset Columns:
- **employee_id:** Unique identifier for each employee.
- **department:** Department where the employee works.
- **region:** Geographic region of the employee.
- **education:** Educational qualification of the employee.
- **gender:** Gender of the employee.
- **recruitment_channel:** Channel through which the employee was recruited.
- **no_of_trainings:** Number of trainings attended by the employee.
- **age:** Age of the employee.
- **previous_year_rating:** Performance rating of the previous year.
- **length_of_service:** Duration of service in the company.
- **KPIs_met_more_than_80:** Number of Key Performance Indicators met by the employee exceeding 80%.
- **awards_won:** Number of awards won by the employee.
- **avg_training_score:** Average score obtained by the employee in trainings.

## Performance Score Calculation

**Formula Used:** 
**Performance_Score = (KPIs_met_more_than_80 * 0.5) + (awards_won * 0.3) + (avg_training_score * 0.2)


### Explanation of Weights:
- **KPIs_met_more_than_80 (50%):** This metric is given the highest weight as meeting key performance indicators is a direct measure of an employee’s effectiveness in their role.
- **awards_won (30%):** Awards are significant indicators of exceptional performance and contribution, hence a substantial weight.
- **avg_training_score (20%):** Training scores reflect the employee’s willingness and ability to learn and apply new skills, important but less direct compared to KPIs and awards.

## Data Analysis and Visualization

**Tools Used:** Power BI

### Visualizations Created:
- **Performance by Department:** Bar charts showing average performance scores across departments.
- **Length of Service Analysis:** Line charts depicting performance trends relative to the length of service.
- **Regional Performance:** Column chart indicating performance variations across regions.
- **Recruitment Channel Effectiveness:** Column charts illustrating performance based on recruitment channels.
- **Education Impact:** Column chart showing the relationship between education level and performance scores.
- **Training Performance:** Line chart showing impact of training performance.

### Interactive Filters:
- A single **employee_id** filter was added to enable detailed analysis of individual performance metrics across all visualizations.

## Insights Uncovered

### 1. Departmental Performance:
- Identified top-performing departments and those needing improvement.
- Noticed a strong correlation between specific departments and higher performance scores.

### 2. Regional Analysis:
- Highlighted regions with consistently high or low performance scores.

### 3. Impact of Recruitment Channels:
- Analyzed the effectiveness of various recruitment channels in bringing high-performing employees.
- Found that referral channels consistently sourced better performers.

### 4. Educational Influence:
- Discovered trends showing higher performance scores among employees with certain educational backgrounds.

### 5. Length of Service:
- Identified performance trends over the length of service, helping to tailor retention and career development programs.

### 6. Training Score:
- Noticed employees with higher training scores had better performance.

## Outcomes
- **Identification of Top Performers:** Recognized employees who consistently met or exceeded performance expectations.
- **Improvement Areas:** Pinpointed departments, regions, and demographics requiring additional support.
- **Data-Driven Decision Making:** Equipped HR and management teams with actionable insights to enhance training programs, recruitment strategies, and overall employee development.

## Way Forward

### 1. Continuous Monitoring:
- Implement regular updates to the performance evaluation system to keep track of changing trends and metrics.

### 2. Targeted Training Programs:
- Develop training programs tailored to the needs of departments or regions identified as underperforming.

### 3. Enhanced Recruitment Strategies:
- Refine recruitment strategies based on insights into the most effective recruitment channels.

### 4. Employee Development Initiatives:
- Initiate development programs focused on boosting performance in areas highlighted by the analysis.

## Conclusion

The employee performance evaluation project successfully created a robust system for monitoring and assessing employee performance. By leveraging data cleaning in Excel and powerful visualization capabilities in Power BI, I provided comprehensive insights into various factors influencing performance. The outcomes of this project enable informed decision-making to foster an environment of continuous improvement and excellence within the organization.

