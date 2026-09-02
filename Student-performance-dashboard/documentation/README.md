# 🎓 Student Performance Analytics Dashboard

## Project Overview
An interactive Microsoft Excel dashboard analyzing student examination performance to help school management identify performance patterns and students/groups needing support.

## Business Objective
- Monitor overall academic performance
- Compare math, reading, and writing performance
- Analyze gender and demographic patterns
- Evaluate parental education and lunch-type differences
- Measure the relationship between test preparation and performance
- Identify high- and low-performing students
- Monitor pass/fail performance

## Dashboard KPIs
- Total Students
- Average Marks
- Highest Marks
- Pass Percentage
- Top Performer

## Dashboard Charts
- Average Marks by Subject
- Gender-wise Performance
- Parent Education vs Marks
- Lunch Type vs Marks
- Test Preparation Impact
- Pass/Fail Distribution
- Score Distribution

## Filters
- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch
- Test Preparation Course

## Business Questions

### Student Performance
1. How many students are enrolled?
2. What is the average score?
3. Who scored the highest?
4. Who scored the lowest?
5. Which subject has the highest average score?
6. Which subject has the lowest average score?
7. Which students are failing?
8. What percentage of students passed?
9. Which students are the top performers?
10. Which students require additional academic support?

### Demographic Analysis
11. Does gender relate to performance?
12. Which gender has the highest average score?
13. Does parental education relate to performance?
14. Which parental education group has the highest average score?
15. Does lunch type relate to performance?
16. Which lunch group has the highest average score?
17. Which race/ethnicity group performs best?
18. Which demographic group has the highest pass rate?
19. Which demographic group has the most failures?
20. Which demographic group requires additional support?

### Test Preparation
21. Does completing the test preparation course improve performance?
22. Which preparation group has the higher average score?
23. Which preparation group has the higher pass rate?
24. Should the school encourage more students to complete test preparation?

### Subject Analysis
25. Which subject needs the most academic support?
26. Which students are weak in a particular subject?
27. Which students perform consistently well across all subjects?
28. Which students have a large difference between subject scores?

## Calculated Columns
- Total Score
- Average Score
- Pass/Fail
- Performance Category

Performance categories:
- 80+ = Excellent
- 60–79.99 = Good
- 40–59.99 = Average
- Below 40 = Needs Improvement

Pass rule:
A student passes when math, reading, and writing scores are all >= 40.

## Excel Skills
Power Query, Excel Tables, IF, nested IF, IFS, AND, AVERAGE, AVERAGEIF, COUNTIF, COUNTIFS, RANK, LARGE, SMALL, Conditional Formatting, Pivot Tables, Pivot Charts, Slicers, Data Validation, KPI design.

## Workflow
Raw Dataset → Power Query → Clean Data → Calculated Columns → Pivot Tables → Pivot Charts → Slicers → KPI Cards → Dashboard → Insights → Recommendations

## Data Limitations
The standard dataset does not contain Class, Section, Attendance, Teacher, Semester, Previous Scores, or Student Names/IDs. Therefore those analyses are not claimed in this project.

## Project Structure
```text
Student-Performance-Dashboard/
├── dataset/
├── screenshots/
├── Student_Performance_Analytics_Dashboard.xlsx
├── README.md
├── business_questions.md
├── insights.md
├── data_dictionary.md
├── methodology.md
└── dashboard_guide.md
```

## Author
**Dhanunjaya**
B.Tech — Artificial Intelligence & Machine Learning
