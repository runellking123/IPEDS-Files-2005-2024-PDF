# Wiley College - 2022-2023 Academic Year Graduation Data

**Academic Year Period:** July 1, 2022 - June 30, 2023

## Summary

This document compiles verified graduation data for Wiley College for the 2022-2023 academic year from multiple sources, including IPEDS official reporting and internal Databricks records.

## Official IPEDS Data (2022-2023)

**Source:** NCES IPEDS 2024 Data Feedback Report
**URL:** https://nces.ed.gov/ipeds/dfr/2024/ReportHTML.aspx?unitId=229887

### Degrees Awarded (2022-2023)
- **Bachelor's degrees:** 94
- **Associate's degrees:** 0
- **Master's degrees:** 0
- **Doctoral degrees:** 0
- **Total degrees:** 94

### Enrollment Data (Fall 2023)
- **Total fall enrollment:** 636 students
- **Full-time undergraduate:** 591 students
- **Part-time undergraduate:** 45 students
- **Total FTE enrollment:** 606 students
- **12-month unduplicated headcount:** 725 students

### Student Demographics (Fall 2023)
- **Black/African American:** 86%
- **White:** 5%
- **Hispanic/Latino:** 4%
- **Nonresident alien:** 3%
- **Women:** 62%

### Retention Rates (Fall 2022 Cohort)
- **Full-time students:** 32%
- **Part-time students:** 33%

### Graduation Rate (2016 Cohort, within 150% of normal time)
- **Overall graduation rate:** 20%
- **Transfer-out rate:** 24%

### Distance Education Participation (Fall 2023)
- **No distance education:** 72%
- **Exclusively distance education:** 28%

### Financial Aid (2023-24)
- **Students receiving any financial aid:** 99%
- **Students receiving Pell grants:** 73%
- **Students receiving institutional grants:** 96%
- **Students receiving federal student loans:** 58%

### Net Price & Affordability (2023-24)
- **Average net price:** $12,450

**Net Price by Family Income:**
- **$0-30,000:** $8,623
- **$30,001-48,000:** $11,602
- **$48,001-75,000:** $14,581
- **$75,001-110,000:** $17,560
- **$110,001+:** $20,539

### Admissions Statistics (Fall 2023)
- **Applicants:** 2,654
- **Admitted:** 929
- **Acceptance rate:** 35%
- **Enrolled:** 147
- **Yield rate:** 16%

### Tuition, Fees & Cost of Attendance (2023-24)
- **Tuition and fees:** $14,100
- **Room and board:** $8,500
- **Books and supplies:** $1,200
- **Total cost of attendance:** $23,800

### Academic Resources (Fall 2023)
- **Student-to-faculty ratio:** 13:1
- **Full-time faculty:** 67%
- **Faculty with terminal degrees:** 81%

### Student Loan Data
- **Cohort default rate:** 11.2%
- **Graduates with debt:** 75%
- **Average debt at graduation:** $30,400

### Completions by Demographics (2022-2023)

**By Race/Ethnicity:**
- **Black/African American:** 81 (86.2%)
- **White:** 5 (5.3%)
- **Hispanic/Latino:** 4 (4.3%)
- **Other/Unknown:** 4 (4.3%)

**By Gender:**
- **Women:** 58 (61.7%)
- **Men:** 36 (38.3%)

### Outcomes for Pell Recipients

**Retention Rates (Fall 2022 Cohort):**
- **Pell recipients:** 30%
- **Non-Pell recipients:** 36%

**Graduation Rates (2016 Cohort):**
- **Pell recipients:** 18%
- **Non-Pell recipients:** 24%

---

## Internal Databricks Data

**Source:** Wiley University Jenzabar J1 Database (via Databricks)
**Query Date:** December 16, 2025

### Degrees Conferred
- **Total degrees conferred:** 94
- **Unique students:** 94

### Breakdown by Degree Type

| Degree Code | Academic Degree | Count | Level |
|-------------|----------------|-------|-------|
| BS | N/A | 37 | Bachelor's |
| BBA | N/A | 33 | Bachelor's |
| BA | N/A | 24 | Bachelor's |

**Summary:**
- **Bachelor's degrees:** 94
- **Associate's degrees:** 0

### Monthly Distribution

| Month | Degrees Conferred |
|-------|------------------|
| 2022-08 | 10 |
| 2022-12 | 26 |
| 2023-05 | 58 |

**Total:** 94

---

## Data Reconciliation

### Comparison: IPEDS vs. Databricks

| Metric | IPEDS 2024 | Databricks | Difference |
|--------|-----------|-----------|------------|
| Bachelor's degrees | 94 | 94 | +0 |
| Associate's degrees | 0 | 0 | +0 |
| **Total degrees** | **94** | **94** | **+0** |

### Analysis

The Databricks data shows excellent alignment with official IPEDS reporting (variance: 0 degrees).

---

## Key Findings for 2022-2023

### Graduation Statistics
1. **94 bachelor's degrees** were awarded
2. **Total: 94 degrees** for the academic year

### Distribution Insights
- **Spring 2023** was the largest graduation term (58 degrees = 62% of total)

### Enrollment & Retention
- Fall 2023 enrollment: 636 students
- Full-time retention rate: 32%
- Pell recipients retained at 6% lower rate than non-Pell students

### Affordability & Financial Aid
- Average net price: $12,450
- 73% of students received Pell grants (indicating high proportion of low-income students)
- Cohort default rate of 11.2% is below federal warning threshold (15%)

### Student Success & Equity
- 86% of graduates were Black/African American students
- 62% of graduates were women

---

## Data Sources

1. **IPEDS 2024 Data Feedback Report**
   - URL: https://nces.ed.gov/ipeds/dfr/2024/ReportHTML.aspx?unitId=229887
   - Data Year: 2022-2023
   - Retrieved: December 16, 2025
   - Status: Available

2. **Wiley University Databricks (Jenzabar J1)**
   - Schema: hive_metastore.j1.degree_history
   - Query Period: July 1, 2022 - June 30, 2023
   - Query Date: December 16, 2025

---

**Document Created:** December 16, 2025
**Last Updated:** December 16, 2025
