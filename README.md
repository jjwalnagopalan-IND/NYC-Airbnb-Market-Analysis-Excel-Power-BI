## NYC-Airbnb-Market-Analysis-Excel-Power-BI
An exploratory analysis of New York City Airbnb listings using Microsoft Excel and Power BI to examine pricing, room types, host activity, review patterns, and listing availability.

# Project Overview
This portfolio project demonstrates an Excel-to-Power BI analytics workflow: inspect listing data, document cleaning steps, create analytical categories, summarize results with Pivot Tables, and communicate findings through dashboard visuals.

The workbook includes raw data, a cleaned worksheet, Pivot Tables, charts, and an Excel dashboard. The accompanying PDF presents the Power BI dashboard and individual visualizations.

# Business Questions
1. How do average listing prices differ across NYC boroughs?
2. How do prices compare across room types?
3. How are listings distributed across host-scale categories?
4. What do review activity and availability reveal about the listings?
5. Where are listings located across New York City?

# Tools and Skills
1. Microsoft Excel: data inspection, missing-value checks, duplicate checks, formulas, calculated columns, Pivot Tables, charts, and dashboards.
2. Power BI: KPI cards, categorical comparisons, slicers, and geographic visualization.
3. Analytics: exploratory data analysis, segmentation, descriptive statistics, dashboard design, and communicating limitations.

# Dataset and Analysis Scope
Source: New York City Airbnb Open Data on Kaggle

# Data Preparation
The project documentation describes the following workflow:
1. Check duplicate records and inspect missing values using filters and COUNTBLANK.
2. Handle missing host, review-date, and monthly-review fields.
3. Standardize numeric and date fields for analysis.
4. Create analytical fields for pricing, availability, minimum stays, review intensity, review year, and host scale.
5. Build Pivot Tables to compare boroughs, room types, host categories, and review activity.

# Key Findings from the Exported Report
1. Manhattan has the highest average listing price among the displayed boroughs.
2. Entire homes/apartments have the highest average price: $194.93, compared with $98.14 for private rooms and $69.83 for shared rooms.
3. Single-listing hosts account for the most listings: 607 of the 954 listings in the report view.
4. Low review intensity is the largest displayed review category: 625 listings.

These observations describe the supplied historical data and report view; they should not be treated as current market estimates.

# Limitations and Validation Notes
1. The cleaned workbook and exported dashboard have different record counts. Reconcile the dashboard filters and source range before claiming full-dataset results.
2. The price-band chart displays values in millions rather than listing-count units. Confirm its value field and aggregation before interpreting its percentages as shares of listings.
3. Availability is not an occupancy measure. Available days alone cannot establish bookings, realized revenue, or profitability.
4. Review activity is not a direct measure of demand or visibility.
5. Zero-filled monthly-review values should be distinguished from genuinely observed zeros when interpreting review intensity.
6. The source is a historical NYC Airbnb dataset, not a live market feed.

# How to Explore the Project
1. Open the Excel workbook in Microsoft Excel and review the Cleaned, Pivot_table, and Dashboard worksheets.
2. Open the PDF for a quick view of the Power BI dashboard and its individual charts.
3. Read the documentation for the preparation process, calculated-field formulas, and dashboard explanations.
4. Check the scope and validation notes before extending the analysis.
   
# Future Improvements
1. Align the Power BI report scope with the cleaned workbook and document all filters.
2. Validate chart aggregations and missing-value handling.
3. Add the original .pbix file and a data dictionary.
4. Compare median prices alongside averages to reduce the influence of extreme prices.
5. Explore price modeling using clearly defined training and evaluation data.
   
## Author
* Jwalna G *
Created as a data analytics portfolio project using Excel and Power BI.
