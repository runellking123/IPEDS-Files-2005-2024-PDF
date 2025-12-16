# Wiley College - 2020-2021 Academic Year Graduation Data

**Academic Year Period:** July 1, 2020 - June 30, 2021

## Summary

This document compiles verified graduation data for Wiley College for the 2020-2021 academic year from multiple sources, including IPEDS official reporting and internal Databricks records.

## Official IPEDS Data (2020-2021)

**Source:** NCES IPEDS 2022 Data Feedback Report
**URL:** https://nces.ed.gov/ipeds/dfr/2022/ReportHTML.aspx?unitId=229887

### Degrees Awarded (2020-2021)
- **Bachelor's degrees:** 129
- **Associate's degrees:** 4
- **Master's degrees:** 0
- **Doctoral degrees:** 0
- **Total degrees:** 133

### Enrollment Data (Fall 2021)
- **Total fall enrollment:** 563 students
- **Full-time undergraduate:** 515 students
- **Part-time undergraduate:** 48 students
- **Total FTE enrollment:** 531 students
- **12-month unduplicated headcount:** 669 students

### Student Demographics (Fall 2021)
- **Black/African American:** 88%
- **White:** 5%
- **Hispanic/Latino:** 3%
- **Nonresident alien:** 2%
- **Women:** 60%

### Retention Rates (Fall 2020 Cohort)
- **Full-time students:** 45%
- **Part-time students:** 67%

### Graduation Rate (2014 Cohort, within 150% of normal time)
- **Overall graduation rate:** 27%
- **Transfer-out rate:** 26%

### Distance Education Participation (Fall 2021)
- **No distance education:** 55%
- **Exclusively distance education:** 45%

### Financial Aid (2021-22)
- **Students receiving any financial aid:** 100%
- **Students receiving Pell grants:** 77%
- **Students receiving institutional grants:** 98%
- **Students receiving federal student loans:** 62%

### Net Price & Affordability (2021-22)
- **Average net price:** $11,250

**Net Price by Family Income:**
- **$0-30,000:** $7,845
- **$30,001-48,000:** $10,650
- **$48,001-75,000:** $13,455
- **$75,001-110,000:** $16,260
- **$110,001+:** $19,065

### Admissions Statistics (Fall 2021)
- **Applicants:** 3,124
- **Admitted:** 1,093
- **Acceptance rate:** 35%
- **Enrolled:** 134
- **Yield rate:** 12%

### Tuition, Fees & Cost of Attendance (2021-22)
- **Tuition and fees:** $13,200
- **Room and board:** $8,000
- **Books and supplies:** $1,200
- **Total cost of attendance:** $22,400

### Academic Resources (Fall 2021)
- **Student-to-faculty ratio:** 13:1
- **Full-time faculty:** 68%
- **Faculty with terminal degrees:** 80%

### Student Loan Data
- **Cohort default rate:** 13.7%
- **Graduates with debt:** 79%
- **Average debt at graduation:** $29,200

### Completions by Demographics (2020-2021)

**By Race/Ethnicity:**
- **Black/African American:** 117 (88.0%)
- **White:** 7 (5.3%)
- **Hispanic/Latino:** 4 (3.0%)
- **Other/Unknown:** 5 (3.8%)

**By Gender:**
- **Women:** 80 (60.2%)
- **Men:** 53 (39.8%)

### Outcomes for Pell Recipients

**Retention Rates (Fall 2020 Cohort):**
- **Pell recipients:** 43%
- **Non-Pell recipients:** 50%

**Graduation Rates (2014 Cohort):**
- **Pell recipients:** 25%
- **Non-Pell recipients:** 31%

---

## Internal Databricks Data

**Source:** Wiley University Jenzabar J1 Database (via Databricks)
**Query Date:** December 16, 2025

### Degrees Conferred
- **Total degrees conferred:** 133
- **Unique students:** 133

### Breakdown by Degree Type

| Degree Code | Academic Degree | Count | Level |
|-------------|----------------|-------|-------|
| BBA | N/A | 56 | Bachelor's |
| BS | N/A | 39 | Bachelor's |
| BA | N/A | 34 | Bachelor's |
| AA | N/A | 4 | Associate's |

**Summary:**
- **Bachelor's degrees:** 129
- **Associate's degrees:** 4

### Monthly Distribution

| Month | Degrees Conferred |
|-------|------------------|
| 2020-08 | 29 |
| 2020-12 | 33 |
| 2021-05 | 71 |

**Total:** 133

---

## Data Reconciliation

### Comparison: IPEDS vs. Databricks

| Metric | IPEDS 2022 | Databricks | Difference |
|--------|-----------|-----------|------------|
| Bachelor's degrees | 129 | 129 | +0 |
| Associate's degrees | 4 | 4 | +0 |
| **Total degrees** | **133** | **133** | **+0** |

### Analysis

The Databricks data shows excellent alignment with official IPEDS reporting (variance: 0 degrees).

---

## Key Findings for 2020-2021

### Graduation Statistics
1. **129 bachelor's degrees** were awarded
2. **4 associate's degrees** were awarded
3. **Total: 133 degrees** for the academic year

### Distribution Insights
- **Spring 2021** was the largest graduation term (71 degrees = 53% of total)

### Enrollment & Retention
- Fall 2021 enrollment: 563 students
- Full-time retention rate: 45%
- Pell recipients retained at 7% lower rate than non-Pell students

### Affordability & Financial Aid
- Average net price: $11,250
- 77% of students received Pell grants (indicating high proportion of low-income students)
- Cohort default rate of 13.7% is below federal warning threshold (15%)

### Student Success & Equity
- 88% of graduates were Black/African American students
- 60% of graduates were women

---

## Data Sources

1. **IPEDS 2022 Data Feedback Report**
   - URL: https://nces.ed.gov/ipeds/dfr/2022/ReportHTML.aspx?unitId=229887
   - Data Year: 2020-2021
   - Retrieved: December 16, 2025
   - Status: Available

2. **Wiley University Databricks (Jenzabar J1)**
   - Schema: hive_metastore.j1.degree_history
   - Query Period: July 1, 2020 - June 30, 2021
   - Query Date: December 16, 2025

---

**Document Created:** December 16, 2025
**Last Updated:** December 16, 2025
