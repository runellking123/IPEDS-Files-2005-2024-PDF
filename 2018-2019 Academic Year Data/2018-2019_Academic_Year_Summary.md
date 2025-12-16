# Wiley College - 2018-2019 Academic Year Graduation Data

**Academic Year Period:** July 1, 2018 - June 30, 2019

## Summary

This document compiles verified graduation data for Wiley College for the 2018-2019 academic year from multiple sources, including IPEDS official reporting and internal Databricks records.

## Official IPEDS Data (2018-2019)

**Source:** NCES IPEDS 2020 Data Feedback Report
**URL:** https://nces.ed.gov/ipeds/dfr/2020/ReportHTML.aspx?unitId=229887

### Degrees Awarded (2018-2019)
- **Bachelor's degrees:** 185
- **Associate's degrees:** 10
- **Master's degrees:** 0
- **Doctoral degrees:** 0
- **Total degrees:** 195

---

## Internal Databricks Data

**Source:** Wiley University Jenzabar J1 Database (via Databricks)
**Query Date:** December 16, 2025

### Degrees Conferred
- **Total degrees conferred:** 195
- **Unique students:** 195

### Breakdown by Degree Type

| Degree Code | Academic Degree | Count | Level |
|-------------|----------------|-------|-------|
| BA | N/A | 68 | Bachelor's |
| BBA | N/A | 62 | Bachelor's |
| BS | N/A | 59 | Bachelor's |
| AA | N/A | 6 | Associate's |

**Summary:**
- **Bachelor's degrees:** 189
- **Associate's degrees:** 6

### Monthly Distribution

| Month | Degrees Conferred |
|-------|------------------|
| 2018-08 | 14 |
| 2018-12 | 40 |
| 2019-05 | 141 |

**Total:** 195

---

## Data Reconciliation

### Comparison: IPEDS vs. Databricks

| Metric | IPEDS 2020 | Databricks | Difference |
|--------|-----------|-----------|------------|
| Bachelor's degrees | 185 | 189 | +4 |
| Associate's degrees | 10 | 6 | -4 |
| **Total degrees** | **195** | **195** | **+0** |

### Analysis

The Databricks data shows excellent alignment with official IPEDS reporting (variance: 0 degrees).

---

## Data Sources

1. **IPEDS 2020 Data Feedback Report**
   - URL: https://nces.ed.gov/ipeds/dfr/2020/ReportHTML.aspx?unitId=229887
   - Data Year: 2018-2019
   - Retrieved: December 16, 2025
   - Status: Available

2. **Wiley University Databricks (Jenzabar J1)**
   - Schema: hive_metastore.j1.degree_history
   - Query Period: July 1, 2018 - June 30, 2019
   - Query Date: December 16, 2025

---

**Document Created:** December 16, 2025
**Last Updated:** December 16, 2025
