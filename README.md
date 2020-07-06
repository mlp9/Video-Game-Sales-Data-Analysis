# Video-Game-Sales-Data-Analysis
The data set used in this analysis describes information about historical video game sales. Categorical information includes: rank (in sales), title, platform (system), year of release, genre, publisher, and sales amount (in millions) for the regions of: North America, Europe, Japan, and Other Countries. Approach to Data Analysis includes using Pandas, reading and using Python library documentation, and incorporating data visualization with analysis with Series and DataFrames.
1. (5 points) Load the data from the file into a data frame with the rank denoted as the index.
a. Print the total number of video games.
b. Print a formatted table of data containing the top 15 video games with the highest rank,
including all data known about them.
2. (5 points) The total for global sales is missing, but you realize it would be helpful to provide insights.
This is the sum of sales for all regions and other sales. Create and populate a new column in your data
frame for global sales. Display a revised formatted table of data, including global sales, for the top 15
video games with the highest rank, including all data known about them.
3. (5 points) Display descriptive statistics that include:
a. Total number of video games.
b. Global Sales: min, max, mean, median, and standard deviation.
c. Percentage of video games that earned at least $5,000,000 in global sales starting in the year
2000 or later.
4. (10 points) Write a Python function with parameters of data frame, category, value, and a number that
specifies the number of rows to display in the result. The category and value should have default
values of 'None' and the number of rows (n) should have a default value of 10. n will specify the
number of rows to display in the result. The function should return a data frame containing the top n
rows of video games, based on global sales for a specific value in the category, only if both category
and value are provided. If both category and value are not provided, the top n video games overall
should be displayed.
