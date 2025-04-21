Homework 8 - World Bank Indicator Analysis
🌍 Homework 8 – World Bank SQL Analysis 📊

This project explores a real-world dataset from the World Bank using SQL to uncover patterns about countries, income levels, and regional groupings. 🧠💾
🔍 Overview

We analyzed the wdi_country table derived from WDICountry.csv, filtering out non-country aggregates, and examining:

    ✅ Total number of countries
    🌎 Distribution by region and income group
    🧩 Data cleanup (like missing income groups)
    📈 Pivot tables and percentage breakdowns

All tasks were answered using pure SQL, with extra attention to data quality and interpretation.
🛠️ Skills Practiced

    SQL basics: SELECT, WHERE, GROUP BY, ORDER BY, COUNT, JOIN
    Intermediate techniques: CASE, CTEs, CROSS JOIN, filtering NULLs
    Data analysis: crosstabs, income distribution, regional summaries
    Data cleaning: blank/null detection and correction (e.g., Venezuela 🇻🇪 fix)

🧪 How to Run

All SQL code is structured as Quarto .qmd Python+SQL code blocks and can be executed with a properly connected MySQL/MariaDB environment.
✨ Highlights

    Built a clean wdi_country table with just actual countries (217 rows)
    Identified mismatches in abbreviation codes 🆚 WB-2 code
    Created pivot-style views and percent-of-total metrics
    Investigated missing Region-Income pairings like a data detective 🕵️‍♂️

🧠 Lessons Learned

    Always inspect for blanks and nulls in real-world datasets.
    Use CTEs to build complex queries in clear steps.
    Think like a data analyst: what’s missing, what’s skewed, what’s surprising?

📁 Files

    loader.qmd – Loads the World Bank dataset into SQL
    report.qmd – Contains all SQL task answers + reflection
    WDICountry.csv – Main dataset (countries & regions)
    WDISeries.csv – Supplementary (not used here)

Made with 🤓, 💻, and ☕.
