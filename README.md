# pandas-challenge - Detailed analysis inclued in the code as markdowns
Module 4 homework - pandas-challenge
This module involved the analysis of the district-wide standardized test results. The code includes the aggregation and sorting of the data to showcase trends between district and carter school performances.

Code analysis details:

Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.
Total number of unique schools
Total students
Total budget
Average math score
Average reading score
% passing math (the percentage of students who passed math)
% passing reading (the percentage of students who passed reading)
% overall passing (the percentage of students who passed math AND reading)

School Summary Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.
School name
School type
Total students
Total school budget
Per student budget
Average math score
Average reading score
% passing math (the percentage of students who passed math)
% passing reading (the percentage of students who passed reading)\
% overall passing (the percentage of students who passed math AND reading)

Highest-Performing Schools (by % Overall Passing) Sort the schools by % Overall Passing in descending order and display the top 5 rows.

Lowest-Performing Schools (by % Overall Passing) Sort the schools by % Overall Passing in ascending order and display the top 5 rows.

Math Scores by Grade Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Reading Scores by Grade Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Scores by School Spending Create a table that breaks down school performance based on average spending ranges (per student).

Use the code provided below to create four bins with reasonable cutoff values to group school spending.

spending_bins = [0, 585, 630, 645, 680] labels = ["<$585", "$585-630", "$630-645", "$645-680"] Use pd.cut to categorize spending based on the bins.

calculate mean scores per spending range.

Include the following metrics in the table:

Average math score
Average reading score
% passing math (the percentage of students who passed math)
% passing reading (the percentage of students who passed reading)
% overall passing (the percentage of students who passed math AND reading)

Scores by School Size Use the following code to bin the per_school_summary.

size_bins = [0, 1000, 2000, 5000] labels = ["Small (<1000)", "Medium (1000-2000)", "Large (2000-5000)"] Use pd.cut on the "Total Students" column of the per_school_summary DataFrame.

Create a DataFrame that breaks down school performance based on school size (small, medium, or large).

Scores by School Type Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary.

This new DataFrame should show school performance based on the "School Type".

