# Wiley College - 2021-2022 Academic Year Graduation Data

**Academic Year Period:** July 1, 2021 - June 30, 2022

## Summary

This document compiles verified graduation data for Wiley College for the 2021-2022 academic year from multiple sources, including IPEDS official reporting and internal Databricks records.

## Official IPEDS Data (2021-2022)

**Source:** NCES IPEDS 2023 Data Feedback Report
**URL:** https://nces.ed.gov/ipeds/dfr/2023/ReportHTML.aspx?unitId=229887

### Degrees Awarded (2021-2022)
- **Bachelor's degrees:** 108
- **Associate's degrees:** 6
- **Master's degrees:** 0
- **Doctoral degrees:** 0
- **Total degrees:** 114

---

## Internal Databricks Data

**Source:** Wiley University Jenzabar J1 Database (via Databricks)
**Query Date:** December 16, 2025

### Degrees Conferred
- **Total degrees conferred:** 114
- **Unique students:** 114

### Breakdown by Degree Type

| Degree Code | Academic Degree | Count | Level |
|-------------|----------------|-------|-------|
| BBA | N/A | 40 | Bachelor's |
| BS | N/A | 36 | Bachelor's |
| BA | N/A | 32 | Bachelor's |
| AA | N/A | 6 | Associate's |

**Summary:**
- **Bachelor's degrees:** 108
- **Associate's degrees:** 6

### Monthly Distribution

| Month | Degrees Conferred |
|-------|------------------|
| 2021-08 | 13 |
| 2021-12 | 41 |
| 2022-05 | 60 |

**Total:** 114

---

## Data Reconciliation

### Comparison: IPEDS vs. Databricks

| Metric | IPEDS 2023 | Databricks | Difference |
|--------|-----------|-----------|------------|
| Bachelor's degrees | 108 | 108 | +0 |
| Associate's degrees | 6 | 6 | +0 |
| **Total degrees** | **114** | **114** | **+0** |

### Analysis

The Databricks data shows excellent alignment with official IPEDS reporting (variance: 0 degrees).

---

## Data Sources

1. **IPEDS 2023 Data Feedback Report**
   - URL: https://nces.ed.gov/ipeds/dfr/2023/ReportHTML.aspx?unitId=229887
   - Data Year: 2021-2022
   - Retrieved: December 16, 2025
   - Status: Available

2. **Wiley University Databricks (Jenzabar J1)**
   - Schema: hive_metastore.j1.degree_history
   - Query Period: July 1, 2021 - June 30, 2022
   - Query Date: December 16, 2025

---

**Document Created:** December 16, 2025
**Last Updated:** December 16, 2025
