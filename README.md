README
# Module 4 Challenge<br>

![education image](./Images/education.png)

* In this challenge, the information given includes the students's math and reading scores, and information about the schools they attend. I was tasked to analyze standardized test results across a city's school district. The Jupyter Notebook code attached aggregates the data with pandas in order to demonstrate trends in student performance for each school. CSV files contain information on the schools and students were included. <br>

*Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends based on the data:* <br>
# District Summary: <br>
* Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.<br>
* Include the following: Total number of unique schools, Total students, Total budget, Average math score, Average reading score, % passing math (the percentage of students who passed math), % passing reading (the percentage of students who passed reading), % overall passing (the percentage of students who passed math AND reading).<br>

# School Summary: <br>
* Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.<br>
* Include the following: School name, School type, Total students, Total school budget, Per student budget, Average math score, Average reading score,% passing math (the percentage of students who passed math), % passing reading (the percentage of students who passed reading), % overall passing (the percentage of students who passed math AND reading).<br>

# Highest-Performing Schools (by % Overall Passing) <br>
 * Sort the schools by % Overall Passing in descending order and display the top 5 rows.
 * Save the results in a DataFrame called "top_schools".<br>

# Lowest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in ascending order and display the top 5 rows.
Save the results in a DataFrame called "bottom_schools".<br>

# Math Scores by Grade <br>
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.<br>

# Reading Scores by Grade <br>
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.<br>

# Scores by School Spending <br>
Create a table that breaks down school performance based on average spending ranges (per student).<br>

* Use the code provided below to create four bins with reasonable cutoff values to group school spending. spending_bins = [0, 585, 630, 645, 680]
labels = ["<$585", "$585-630", "$630-645", "$645-680"]<br>

* Use pd.cut on the "Total Students" column of the per_school_summary DataFrame.<br>
# Size Summary <br>
* Create a DataFrame that breaks down school performance based on school size (small, medium, or large).<br>

# Scores by School Type. <br>
* Use the per_school_summary DataFrame from the previous step to create a new DataFrame called type_summary. This new DataFrame should show school performance based on the "School Type".

# Written Report <br>
* To receive all points, the written report presents a cohesive written analysis that: Summarizes the analysis (5 points), Draws two correct conclusions or comparisons from the calculations (10 points).