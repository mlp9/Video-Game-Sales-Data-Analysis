# Video-Game-Sales-Data-Analysis
The data set used in this analysis describes information about historical video game sales. Categorical information includes: rank (in sales), title, platform (system), year of release, genre, publisher, and sales amount (in millions) for the regions of: North America, Europe, Japan, and Other Countries. Approach to Data Analysis includes using Pandas, reading and using Python library documentation, and incorporating data visualization with analysis with Series and DataFrames.

Data Analysis tasks performed: 
1. Loading the data from the file into a data frame with the rank denoted as the index.
    a. Print the total number of video games.
    b. Print a formatted table of data containing the top 15 video games with the highest rank,
including all data known about them.

2. Created and populated a new column in data frame for global sales. Displayed a revised formatted table of data, including global sales, for the top 15 video games with the highest rank, including all data known about them.

3. Displayed descriptive statistics that include:
    a. Total number of video games.
    b. Global Sales: min, max, mean, median, and standard deviation.
    c. Percentage of video games that earned at least $5,000,000 in global sales starting in the year 2000 or later.
    
4.  Wrote a Python function with parameters of data frame, category, value, and a number that
specifies the number of rows to display in the result. The category and value have default values of 'None' and the number of rows (n) have a default value of 10. n will specify the number of rows to display in the result. The function returns a data frame containing the top n rows of video games, based on global sales for a specific value in the category, only if both category and value are provided. If both category and value are not provided, the top n video games overall are be displayed.

5) Created a linear correlation matrix between sales in each market (e.g. NA, EU, etc.) and global sales. 

6. Created two more linear correlation matrices between sales in each market (e.g. NA, EU, etc.) and global sales – the first for the year 2000 and the second for the year 2015.
