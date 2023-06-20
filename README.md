## SalesAnalysis-with-Python

The dataset includes detailed information about hundreds of thousands of electronics store purchases, such as month, product type, cost, purchase address, and more.

### Project Highlights
The project walkthrough includes the following key points:

#### 1. Data Cleaning
* Merge 12 months' worth of sales data into masterdata
* Removing NaN values from the DataFrame
* Dropping rows based on specific conditions
* Changing column types using methods like to_numeric, to_datetime, and astype

#### 2. Data Exploration
Explore five high-level business questions related to the sales data:

* What was the best month for sales? How much revenue was earned during that month?
* Which city had the highest product sales?
* What is the optimal time to display advertisements to maximize the likelihood of customer purchases?
* Which products are most frequently sold together?
* Which product had the highest sales? What factors may have contributed to its success?

#### 3. Pandas and Matplotlib Techniques
Throughout the tutorial, we utilize various Pandas and Matplotlib methods, including:

* Concatenating multiple CSV files to create a consolidated DataFrame (pd.concat)
* Adding new columns to the DataFrame
* Parsing string cells to create new columns (using .str methods)
* Utilizing the .apply() method
* Performing aggregate analysis using groupby
* Visualizing results through bar charts and line graphs using Matplotlib
* Adding labels to enhance the clarity of graphs
