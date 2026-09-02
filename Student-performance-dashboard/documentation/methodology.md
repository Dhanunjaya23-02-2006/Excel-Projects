# Methodology

## 1. Data Preparation
The Students Performance in Exams dataset was imported and cleaned using Power Query.

## 2. Cleaning
- Reviewed column names
- Checked data types
- Checked missing/inconsistent values
- Standardized categorical values
- Changed Test Preparation Course `none` to `Not Completed`

## 3. Calculated Columns
Created:
- Total Score
- Average Score
- Pass/Fail
- Performance Category

## 4. Pass Rule
A student passes only if all three subjects have a score of at least 40.

## 5. Analysis
Pivot Tables are used to compare:
- Subjects
- Gender
- Race/Ethnicity
- Parental education
- Lunch
- Test preparation
- Pass/fail
- Performance categories

## 6. Dashboard
Pivot Charts, KPI cards, slicers, conditional formatting, and dashboard layout are used to present the findings.

## 7. Quality Checklist
- [ ] Data types checked
- [ ] Test preparation values standardized
- [ ] Calculated columns verified
- [ ] KPI values validated
- [ ] Pivot Tables refreshed
- [ ] Charts have clear titles
- [ ] Slicers work
- [ ] Insights match workbook results
