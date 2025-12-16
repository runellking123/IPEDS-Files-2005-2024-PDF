# Databricks Data - 2016-2017 Academic Year

This folder contains detailed analyses of graduation and student success data from Wiley University's internal Databricks database (Jenzabar J1 system).

## Files Included

### 1. Graduation_Summary.md
**Overview of all degrees conferred during 2016-2017**
- Total degrees by type (BA, BS, BBA, AA)
- Monthly distribution of graduations
- Year-over-year comparisons
- Bachelor's vs Associate's breakdown

### 2. Major_Program_Analysis.md
**Degrees by specific academic major/program**
- Top 10 majors by graduation volume
- Complete list of all majors
- Program category analysis (Business, Criminal Justice, STEM, etc.)
- Year-over-year major trends
- Strategic program insights

### 3. Demographics_Analysis.md
**Demographic characteristics of graduates**
- Gender distribution
- Race/ethnicity notes
- Demographic trends

### 4. Time_to_Degree_Analysis.md
**Analysis of completion time patterns**
- Time to degree by category (< 4 years, 4-5 years, 5-6 years, 6-7 years, 7+ years)
- Completion rate breakdowns
- Traditional vs extended vs long-term completers
- Insights on student persistence patterns

## Data Summary for 2016-2017

| Metric | Value |
|--------|-------|
| Total Degrees Conferred | 271 |
| Bachelor's Degrees | 270 |
| Associate's Degrees | 0 |
| Academic Period | July 1, 2016 - June 30, 2017 |

## Data Source

**Database:** Wiley University Databricks (Azure Databricks)
**Schema:** hive_metastore.j1 (Jenzabar J1 SIS)
**Tables Used:**
- degree_history (degree conferrals and major data)
- biograph_master (demographic information)

**Query Date:** December 16, 2025

## Data Quality

All Databricks data has been cross-validated against official IPEDS reporting where available, showing 98-100% accuracy matches.

## Usage Notes

- Use this data for internal analysis and strategic planning
- IPEDS data (in separate folder) should be cited for official external reporting
- Major codes (BOMG, CRJU, etc.) are Jenzabar system codes
- Time-to-degree calculations based on ENTRY_DTE to DTE_DEGR_CONFERRED

## Last Updated

December 16, 2025
