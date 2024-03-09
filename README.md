Title: Exploratory Data Analysis of Homicide Data

Objective:
The objective of this project is to conduct exploratory data analysis (EDA) on homicide data using Python. 
The dataset contains information about homicides, including details such as the region, subregion, count of homeside people, year, and rate. 
The goal is to gain insights into the data through various data visualization techniques and analysis methods, ultimately providing a better understanding of the factors influencing homicides across different regions and subregions over time.


Solution:
To achieve the objective, the following steps were taken:

Importing Python Libraries:
Necessary Python libraries including pandas, numpy, matplotlib, seaborn, and plotly were installed and imported to perform data manipulation and visualization tasks.
Removing Null Values:
Null values were checked for and removed from the dataset to ensure data quality and integrity.
Changing the Datatype of Certain Columns:
Datatype conversion was performed on certain columns to facilitate further exploration and analysis.
Visualizing Top 5 Rows by Count:
The top 5 rows based on count were extracted and visualized using a pie chart to understand the distribution of homicide counts across different categories.
Analyzing Count of Homicides by Homeside People:
The count of homeside people involved in homicides was summed, and a bar plot was created to visualize the distribution of counts.
Grouping and Visualizing Data by Subregion:
The dataset was grouped by the 'Subregion' column and visualized to understand the distribution of homicides across subregions.
Filtering Data and Comparing Trends:
The dataset was filtered to include only rows where the region is either 'Asia' or 'Europe', and the year is greater than 2016. The filtered data was then compared using a line chart to analyze trends over time.
Grouping Data by Year and Summing Rate:
The dataset was grouped by the 'Year' column, and the sum of the 'Rate' was calculated to analyze the overall homicide rate over the years.
Visualizing Count by Year and Region:
The 'Year', 'Region', and 'Count' columns were extracted from the dataset, and the result was grouped by 'Year' and 'Region'. Bar plots were then used to visualize homicide counts across different regions over time.
Grouping Data by Subregion and Visualizing Count:
The dataset was grouped by the 'Subregion' column, and the 'Count' values were summed within each group. The result was visualized on a treemap to understand the distribution of homicides across subregions.
