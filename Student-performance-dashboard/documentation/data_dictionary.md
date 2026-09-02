# Data Dictionary

| Column | Description | Usage |
|---|---|---|
| gender | Student gender | Gender analysis |
| race/ethnicity | Demographic group | Demographic analysis |
| parental level of education | Parent/guardian education | Education analysis |
| lunch | Lunch category | Lunch analysis |
| test preparation course | Preparation status | Preparation analysis |
| math score | Mathematics score | Subject analysis |
| reading score | Reading score | Subject analysis |
| writing score | Writing score | Subject analysis |

## Calculated Columns

**Total Score**
```text
Math + Reading + Writing
```

**Average Score**
```text
(Math + Reading + Writing) / 3
```

**Pass/Fail**
```text
Pass if Math >= 40 AND Reading >= 40 AND Writing >= 40
Otherwise Fail
```

**Performance Category**
```text
>=80  Excellent
>=60  Good
>=40  Average
<40   Needs Improvement
```

## Data Cleaning
`none` in Test Preparation Course was standardized to `Not Completed`.
Final values are `Completed` and `Not Completed`.
