# CHESS GAMES ANALYSIS DASHBOARD

## 1. Project Overview

This project analyzes chess game data using Microsoft Excel. It summarizes game results, opening popularity, player ratings, and monthly game activity through PivotTables, charts, lookup formulas, and an interactive dashboard.

## 2. Workbook Sheets

- **Dashboard:** Displays key statistics, charts, filters, and the Top 8 Openings summary.
- **Clean Data:** Contains the cleaned chess dataset used for analysis.
- **Pivot - Results:** Summarizes games by winner.
- **Pivot - Openings:** Summarizes statistics for chess openings.
- **Pivot - Monthly:** Supports monthly game analysis.
- **Monthly Summary:** Displays monthly game counts and outcome summaries.
- **Lookup:** Contains the opening reference table and advanced formula examples.
- **Documentation:** Provides additional workbook information.

## 3. Data Cleaning and Preparation

The dataset was imported and prepared for analysis. Duplicate records were removed, missing values were checked and handled, and a month field was created from the game creation date for monthly analysis.

## 4. Advanced Excel Formulas

- **VLOOKUP:** Finds an opening name using its ECO code.
- **INDEX-MATCH:** Retrieves an opening name using an alternative lookup method.
- **IF:** Classifies an opening based on its family.
- **Nested IF:** Applies multiple conditions to categorize opening families.
- **DATE, YEAR, MONTH:** Prepares date values for monthly summaries.

## 5. How to Use the Dashboard

1. Open the Dashboard sheet.
2. Use the Winner and Rated status filters or slicers to explore different groups of games.
3. Use the start-date and end-date filters to examine a selected period.
4. Review the charts to compare game winners, victory status, and monthly game volume.
5. Review the Top 8 Openings summary to compare opening activity.
6. Clear the filters to return to the broader view.

## 6. PivotTables and Data Visualization

PivotTables summarize game results, opening statistics, and monthly activity. Charts present the results visually, while conditional formatting helps highlight values in the Top 8 Openings summary.

## 7. Updating the Workbook

When adding new game records:
1. Confirm the new records are included in the Clean Data range.
2. Refresh the relevant PivotTables.
3. Check that charts and dashboard summaries reflect the updated data.
4. Verify the source ranges if new records are not included automatically.

## 8. Limitations

A native Excel Timeline was not added because the workbook was prepared in Excel Online. Start-date and end-date filters are provided instead.
