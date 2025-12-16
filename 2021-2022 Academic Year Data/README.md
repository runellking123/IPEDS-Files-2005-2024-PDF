# 2021-2022 Academic Year Data

This folder contains comprehensive graduation and enrollment data for Wiley College for the 2021-2022 academic year (July 1, 2021 - June 30, 2022).

## Files Included

### 2021-2022_Academic_Year_Summary.md
Complete academic year summary including:
- Official IPEDS 2023 report data
- Internal Databricks graduation data
- Data reconciliation analysis (100% total match)
- Degree conferral breakdowns
- Enrollment and retention statistics
- Post-pandemic recovery indicators
- Year-over-year comparisons

## Data Summary

### Degrees Conferred (2021-2022)

| Source | Bachelor's | Associate's | Total |
|--------|-----------|-------------|-------|
| Databricks | 108 | 6 | 114 |
| IPEDS 2023 | 107 | 7 | 114 |
| **Variance** | **+1** | **-1** | **0** |

**Data Quality:** 100% total match between IPEDS and internal data

### Degree Type Distribution (Databricks)

| Degree | Count | Percentage |
|--------|-------|-----------|
| BBA (Bachelor of Business Administration) | 40 | 35.1% |
| BS (Bachelor of Science) | 36 | 31.6% |
| BA (Bachelor of Arts) | 32 | 28.1% |
| AA (Associate of Arts) | 6 | 5.3% |

### Enrollment (Fall 2022)

| Metric | Count | Change from Fall 2021 |
|--------|-------|----------------------|
| Total fall enrollment | 698 | +33 (+5.0%) |
| Full-time | 652 | - |
| Part-time | 46 | - |
| 12-month FTE | 659 | - |

### Retention and Graduation Rates

| Metric | Rate | Previous Year |
|--------|------|---------------|
| Full-time retention (Fall 2021 cohort) | 54% | 34% (Fall 2020) |
| Part-time retention (Fall 2021 cohort) | 13% | 36% (Fall 2020) |
| Graduation rate (2016 cohort, 150% time) | 24% | 27% (2015 cohort) |
| Transfer-out rate (2016 cohort) | 16% | 39% (2015 cohort) |

### Graduation Rates by Race/Ethnicity (2016 Cohort)

| Demographic | Rate |
|-------------|------|
| Black/African American | 23% |
| Hispanic/Latino | 18% |
| White | 33% |

### Bachelor's Degree Completion (2014 Cohort)

| Timeline | Rate |
|----------|------|
| 4-year | 18% |
| 6-year | 28% |
| 8-year | 28% |

## Key Findings

1. **Continued decline:** 114 total degrees (down from 133 in 2020-21)
2. **14.3% decrease:** Fourth consecutive year of decline
3. **Perfect data match:** 100% total alignment between IPEDS and Databricks
4. **Retention recovery:** Improved to 54% (up from 34%)
5. **Enrollment stabilization:** 5% enrollment growth
6. **More balanced programs:** Better distribution across degree types
7. **Transfer-out improvement:** Dropped to 16% (from 39%)

## Year-over-Year Comparison (Databricks)

| Metric | 2020-2021 | 2021-2022 | Change |
|--------|-----------|-----------|--------|
| Total Degrees | 133 | 114 | -19 (-14.3%) |
| Bachelor's | 129 | 108 | -21 (-16.3%) |
| Associate's | 4 | 6 | +2 (+50.0%) |

## Post-Pandemic Recovery Indicators

### Positive Signs:
- **Retention recovery:** 54% (up 20 percentage points)
- **Enrollment growth:** 698 students (+5.0%)
- **Transfer-out decline:** 16% (down from 39%)
- **Program balance:** More even distribution across BA, BS, BBA
- **Data quality:** Perfect IPEDS alignment

### Ongoing Challenges:
- **Graduation decline:** Still declining despite better retention
- **Low 6-year rate:** Only 28% of 2014 cohort graduated in 6 years
- **Overall graduation rate:** 24% (2016 cohort) below historical levels
- **Lag effect:** Low retention from previous years still impacting graduations

## Degree Program Balance

Unlike previous years with BBA dominance:
- **BBA:** 35.1% (more balanced)
- **BS:** 31.6% (improved share)
- **BA:** 28.1% (recovered share)
- **AA:** 5.3% (increased from previous year)

## Historical Context

- First signs of post-pandemic stabilization
- Retention recovery critical for future graduation improvement
- Enrollment growth reverses multi-year decline
- Transfer-out rate improvement suggests better student satisfaction
- Graduation lag effect: will take years for retention gains to show in graduation numbers

## Data Sources

1. **IPEDS 2023 Data Feedback Report**
   - URL: https://nces.ed.gov/ipeds/dfr/2023/ReportHTML.aspx?unitId=229887
   - Data Year: 2021-2022
   - Retrieved: December 16, 2025

2. **Wiley University Databricks (Jenzabar J1)**
   - Schema: hive_metastore.j1.degree_history
   - Query Period: July 1, 2021 - June 30, 2022
   - Query Date: December 16, 2025

## Usage

This data should be used as:
- Evidence of post-pandemic stabilization
- Reference for retention recovery strategies (54% achievement)
- Analysis of enrollment growth patterns
- Understanding graduation lag effects
- Baseline for continued improvement planning

## Last Updated
December 16, 2025
