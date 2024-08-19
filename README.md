# Database_Projects
# Road Safty 
# Project Overview:
# 1. Table Creation
Accidents Table: A table named Accidents was created to store data about road accidents. It includes details such as accident ID, location, road, weather conditions, time of the accident, severity, number of vehicles involved, injuries, and deaths. The table is partitioned by year based on the accident_time column.
Primary Key: A composite primary key was created using accident_id and accident_time to support partitioning.
# 2. Data Insertion
Sample Data: Inserted records into the Accidents table to simulate real-world data. This data includes various accident scenarios with different severity levels, times, and outcomes.
# 3. Data Analysis Queries
Accidents by Severity: Queried the table to count accidents by severity, providing insights into how many accidents fall into categories like "Severe," "Moderate," etc.
Accidents by Year: Counted accidents by year to identify trends or spikes in particular years.
Accidents by Location: Analyzed accidents based on location to determine which areas experience more accidents.
# 4. Performance Optimization
Indexes: Created indexes on frequently queried columns (accident_time, severity, and location_id) to improve query performance.
# 5. Advanced Analysis
CTEs and Window Functions:
Accident Count by Hour: Analyzed accidents by the hour of the day to understand peak times for accidents.
Cumulative Accident Count: Used a window function to calculate a cumulative count of accidents over time.
# 6. Views for Reporting
Accident Severity Distribution View: Created a view to easily access a distribution of accidents by severity across different years, simplifying the reporting process.
# 7. Stored Procedure
Dynamic Accident Reporting: Developed a stored procedure (GetAccidentReport) to generate dynamic reports based on severity and date range inputs. This allows flexible querying for different reporting needs.
# 8. Testing and Usage
Procedure Execution: The stored procedure was tested with sample inputs to generate reports, confirming its functionality and utility for generating custom accident reports.
