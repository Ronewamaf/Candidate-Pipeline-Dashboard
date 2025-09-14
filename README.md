# Candidate_Pipeline_PowerBI_Dashboard

### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiNTJmMDcxNmMtOGMwOS00OWNlLTgyNDgtYTdlODgxNTJlZjgzIiwidCI6IjQ0MWRiNzQ0LWY5NzUtNGI2Ny04YzU3LTA1NDFkMTI3NjM2MyJ9

## Problem Statement

This dashboard helps organizations involved in talent development programs better understand the status and progress of their learners. It provides insights into each stage of the learner journey like availability, interviews, placements, resignations, and stipends thus allowing stakeholders to monitor real-time performance and identify areas needing attention. Through dynamic visuals and filters, the dashboard highlights learner statuses, timelines, and stipend activity, making it easier to pinpoint bottlenecks or drop-off points.
For instance, if a large number of learners remain in the 'available' or 'interviewing' stages for extended periods, it signals delays in placement processes. Similarly, tracking resignation trends or missed stipends helps management intervene early and improve learner experience. By identifying these issues through the dashboard, stakeholders are empowered to take action and improve the overall efficiency of the placement pipeline.


## Steps Followed
Step 1: Loaded learner pipeline data from a CSV file into Power BI Desktop.

Step 2: Opened Power Query Editor and enabled “Column Distribution,” “Column Quality,” and “Column Profile” under the View tab to assess 
data structure and completeness.

Step 3: Changed profiling settings to use the entire dataset instead of just the top 1,000 rows for more accurate profiling.

Step 4: Cleaned the data by checking for nulls and inconsistencies. Columns were renamed and formatted for clarity (e.g., date fields, stipend amounts).

Step 5: Transformed data types and created calculated columns where necessary (e.g., status logic, total top-ups).

Step 6: Moved to the Report View and applied a professional theme under the View tab.

Step 7: Designed the main dashboard (Page 1) with the following visuals:

•	Card visual for total number of learners.

•	Clustered bar chart showing number of learners per cohort and learnership type.

•	Stacked column chart visualizing stipend and top-up amounts per client.

•	Line chart displaying WIL (Work Integrated Learning) start dates by month and client.

•	Table visual providing detailed learner-level data.

•	3 slicers/filters: Learnership Type, Start Date, and End Date.

Step 8: Created the second dashboard page with:

•	Stacked bar chart displaying learner status distribution.

•	3 slicers/filters: Placement Category, Learner Status, and Date.

Step 9: Published the final report to Power BI Service for sharing and collaboration.

