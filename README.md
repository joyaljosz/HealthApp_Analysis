# HealthApp_Analysis

1. Data Loading and Preprocessing:
The code reads a CSV file ('HealthApp_2k.log_structured.csv') into a Pandas DataFrame.
Converts the 'Time' column to a datetime format and extracts additional features like hour, day, month, and year.

2.Filtering Steps Data:
Filters the DataFrame to include only rows where the 'EventTemplate' column matches a specific condition related to step changes.
Extracts the number of steps from the 'Content' column and creates a new 'Steps' column.
Aggregates daily steps by summing the 'Steps' column.

3.Plotting Daily Steps:
Plots a line graph to visualize the daily steps taken over time.

4.Aggregating Active Hours:
Groups the original DataFrame by the hour of the day and counts the number of events in each hour.

5.Plotting Active Hours:
Plots a bar chart to visualize the distribution of events across different hours of the day.

6.Previewing Data:
Outputs the first few rows of the aggregated daily steps and active hours DataFrames for a quick preview.
