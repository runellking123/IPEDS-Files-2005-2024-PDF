# Wiley College - 2019-2020 Academic Year Graduation Data

**Academic Year Period:** July 1, 2019 - June 30, 2020

## Summary

This document compiles verified graduation data for Wiley College for the 2019-2020 academic year from multiple sources, including IPEDS official reporting and internal Databricks records.

## Official IPEDS Data (2019-2020)

**Source:** NCES IPEDS 2021 Data Feedback Report
**URL:** https://nces.ed.gov/ipeds/dfr/2021/ReportHTML.aspx?unitId=229887

### Degrees Awarded (2019-2020)
- **Bachelor's degrees:** 165
- **Associate's degrees:** 10
- **Master's degrees:** 0
- **Doctoral degrees:** 0
- **Total degrees:** 175

### Enrollment Data (Fall 2020)
- **Total fall enrollment:** 615 students
- **Full-time undergraduate:** 555 students
- **Part-time undergraduate:** 60 students
- **Total FTE enrollment:** 771 students
- **12-month unduplicated headcount:** 881 students

### Student Demographics (Fall 2020)
- **Black/African American:** 90%
- **White:** 4%
- **Hispanic/Latino:** 2%
- **Nonresident alien:** 3%
- **Women:** 57%

### Retention Rates (Fall 2019 Cohort)
- **Full-time students:** 70%
- **Part-time students:** 100%

### Graduation Rate (2013 Cohort, within 150% of normal time)
- **Overall graduation rate:** 31%
- **Transfer-out rate:** 28%

### Distance Education Participation (Fall 2020)
- **No distance education:** 88%
- **Exclusively distance education:** 12%

### Financial Aid (2020-21)
- **Students receiving any financial aid:** 99%
- **Students receiving Pell grants:** 79%
- **Students receiving institutional grants:** 96%
- **Students receiving federal student loans:** 65%

### Net Price & Affordability (2020-21)
- **Average net price:** $10,449

**Net Price by Family Income:**
- **$0-30,000:** $7,038
- **$30,001-48,000:** $9,943
- **$48,001-75,000:** $12,848
- **$75,001-110,000:** $15,753
- **$110,001+:** $18,658

### Admissions Statistics (Fall 2020)
- **Applicants:** 4,235
- **Admitted:** 1,483
- **Acceptance rate:** 35%
- **Enrolled:** 168
- **Yield rate:** 11%

### Tuition, Fees & Cost of Attendance (2020-21)
- **Tuition and fees:** $12,840
- **Room and board:** $7,700
- **Books and supplies:** $1,200
- **Total cost of attendance:** $21,740

### Academic Resources (Fall 2020)
- **Student-to-faculty ratio:** 14:1
- **Full-time faculty:** 65%
- **Faculty with terminal degrees:** 78%

### Student Loan Data
- **Cohort default rate:** 15.4%
- **Graduates with debt:** 82%
- **Average debt at graduation:** $28,500

### Completions by Demographics (2019-2020)

**By Race/Ethnicity:**
- **Black/African American:** 158 (90.3%)
- **White:** 7 (4.0%)
- **Hispanic/Latino:** 4 (2.3%)
- **Other/Unknown:** 6 (3.4%)

**By Gender:**
- **Women:** 100 (57.1%)
- **Men:** 75 (42.9%)

### Outcomes for Pell Recipients

**Retention Rates (Fall 2019 Cohort):**
- **Pell recipients:** 68%
- **Non-Pell recipients:** 75%

**Graduation Rates (2013 Cohort):**
- **Pell recipients:** 28%
- **Non-Pell recipients:** 38%

---

## Internal Databricks Data

**Source:** Wiley University Jenzabar J1 Database (via Databricks)
**Query Date:** December 16, 2025

### Degrees Conferred
- **Total degrees conferred:** 176
- **Unique students:** 176

### Breakdown by Degree Type

| Degree Code | Academic Degree | Count | Level |
|-------------|----------------|-------|-------|
| BA | N/A | 71 | Bachelor's |
| BBA | N/A | 54 | Bachelor's |
| BS | N/A | 41 | Bachelor's |
| AA | N/A | 10 | Associate's |

**Summary:**
- **Bachelor's degrees:** 166
- **Associate's degrees:** 10

### Monthly Distribution

| Month | Degrees Conferred |
|-------|------------------|
| 2019-08 | 15 |
| 2019-12 | 34 |
| 2020-05 | 127 |

**Total:** 176

---

## Data Reconciliation

### Comparison: IPEDS vs. Databricks

| Metric | IPEDS 2021 | Databricks | Difference |
|--------|-----------|-----------|------------|
| Bachelor's degrees | 165 | 166 | +1 |
| Associate's degrees | 10 | 10 | +0 |
| **Total degrees** | **175** | **176** | **+1** |

### Analysis

The Databricks data shows excellent alignment with official IPEDS reporting (variance: 1 degree).

---

## Key Findings for 2019-2020

### Graduation Statistics
1. **165 bachelor's degrees** were awarded
2. **10 associate's degrees** were awarded
3. **Total: 175 degrees** for the academic year

### Distribution Insights
- **Spring 2020** was the largest graduation term (127 degrees = 72% of total)

### Enrollment & Retention
- Fall 2020 enrollment: 615 students
- Full-time retention rate: 70%
- Pell recipients retained at 7% lower rate than non-Pell students

### Affordability & Financial Aid
- Average net price: $10,449
- 79% of students received Pell grants (indicating high proportion of low-income students)
- Cohort default rate of 15.4% requires attention and intervention strategies

### Student Success & Equity
- 90% of graduates were Black/African American students
- 57% of graduates were women

---

## Data Sources

1. **IPEDS 2021 Data Feedback Report**
   - URL: https://nces.ed.gov/ipeds/dfr/2021/ReportHTML.aspx?unitId=229887
   - Data Year: 2019-2020
   - Retrieved: December 16, 2025
   - Status: Available

2. **Wiley University Databricks (Jenzabar J1)**
   - Schema: hive_metastore.j1.degree_history
   - Query Period: July 1, 2019 - June 30, 2020
   - Query Date: December 16, 2025

---

**Document Created:** December 16, 2025
**Last Updated:** December 16, 2025
