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
