# Hospital Emergency Room Visits Analysis (Interactive Dashboard creation using Power BI)
## Project Objective
The objective of this Hospital Emergency Room Visits Dashboard project is to provide real-time insights into patient visits, average wait times, satisfaction scores, and admission status (admitted vs. non-admitted). The dashboard aims to help healthcare administrators and staff make data-driven decisions to improve patient care, optimize resource allocation, and enhance operational efficiency within the emergency room setting. By analysing trends over time, the dashboard supports continuous performance monitoring and improvements.
## Dataset Used
<a href="https://github.com/mamatha203/Data-Analysis-Dashboard/blob/main/Hospital%20Data.csv">Dataset</a>

## Key Performance Indicators
- Satisfaction Score Card: Represents the average satisfaction score from patient feedback, giving insight into overall patient satisfaction with the care provided.
- Patient Visits by Date Hierarchy (3 Line Charts): Tracks patient visits, average wait time, and satisfaction scores over time (daily, monthly, yearly), offering trend analysis for each metric.
- Patient Visits by Age (Column Chart): Breaks down patient visits by age groups, helping identify demographics with the highest volume of visits to the ER.
- Patient Visits by Gender (Donut Chart): Shows the distribution of ER visits by gender, providing insight into gender-specific trends in patient care.
- % of Patient Visits within 30 Minutes (Target vs. Missed – Donut Chart): Visualizes the percentage of patients seen within the target time of 30 minutes versus those who missed the target, helping assess 
  operational efficiency.
- Patient Visits by Race (Bar Chart): Displays the distribution of ER visits by patient race, enabling a demographic analysis of care utilization across different racial groups.
- Patient Visits by Department Referral: Illustrates how patients are referred to different departments within the hospital, assisting in the understanding of care pathways and resource allocation.
- Matrix Containing Time Interval of Patient Visits (Days): Provides a matrix showing the frequency of patient visits by day, allowing detailed tracking of peak times and staffing needs.
- Year Slicer: Filters data by year, allowing users to analyse trends and performance across multiple years.
- Month Slicer: Filters data by month, enabling users to drill down into monthly performance metrics for detailed trend analysis.
- Dashboard Interaction <a href="https://github.com/mamatha203/Data-Analysis-Dashboard/blob/main/Hospital%20Emergency%20visits%20Analysis.pbix">View Dataset< /a>
## Process
- Split the combined date and time column into two separate columns (Date and Time) to allow for easier filtering and analysis based on each component.
- Combined the initial name and last name into a new column for full patient names, improving readability and simplifying data analysis.
- Created a conditional column to categorize patients into different age groups, enabling more granular analysis of patient demographics.
- Extracted the hour from the Time column to analyse patterns in patient visits based on specific hours of the day.
- Ensured the correct data types were assigned to each column (e.g., date, numeric, text) for proper analysis and visualization.
- Managed missing or null values in the dataset within Power Query, ensuring data integrity and avoiding errors in analysis.
- Created a calendar table to enable time-based analysis and leverage Date and Time Intelligence functions in Power BI, allowing for easier comparison and trend analysis across different time periods.
- Performed data modelling to establish relationships between tables, ensuring seamless interaction between datasets for accurate and efficient reporting.
- Added a calculated column to categorize patient visits by hour intervals, enabling analysis of patient flow and wait times during specific time blocks.
- Created a calculated column to categorize patient visits as "Admitted" or "Non-Admitted," allowing for better segmentation and analysis of ER performance.
- Split the combined date and time column into two separate columns (Date and Time) to allow for easier filtering and analysis based on each component.
- Combined the initial name and last name into a new column for full patient names, improving readability and simplifying data analysis.
- Created a conditional column to categorize patients into different age groups, enabling more granular analysis of patient demographics.
- Extracted the hour from the Time column to analyse patterns in patient visits based on specific hours of the day.
- Ensured the correct data types were assigned to each column (e.g., date, numeric, text) for proper analysis and visualization.
- Managed missing or null values in the dataset within Power Query, ensuring data integrity and avoiding errors in analysis.
- Created a calendar table to enable time-based analysis and leverage Date and Time Intelligence functions in Power BI, allowing for easier comparison and trend analysis across different time periods.
- Performed data modelling to establish relationships between tables, ensuring seamless interaction between datasets for accurate and efficient reporting.
- Added a calculated column to categorize patient visits by hour intervals, enabling analysis     of patient flow and wait times during specific time blocks.
- Created a calculated column to categorize patient visits as "Admitted" or "Non-Admitted," allowing for better segmentation and analysis of ER performance.


