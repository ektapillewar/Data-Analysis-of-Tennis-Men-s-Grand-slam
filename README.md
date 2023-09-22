# Data-Analysis-of-Tennis-Men-s-Grand-slam
This project involves analyzing and visualizing tennis Grand Slam data using Python and Power BI. It includes data cleaning, preparation, and creating interactive visualizations for tennis enthusiasts and data enthusiasts alike.

#Project Overview
This project aims to analyze and visualize tennis Grand Slam data to gain insights into player performance, trends over the years, and distribution of wins among players. It involves two main components: Python for data cleaning and preparation and Power BI for creating interactive dashboards and visualizations.

#Requirements
To run the Python code and use Power BI for visualization, you'll need the following:

Python (version 3.x)
Jupyter Notebook or an IDE of your choice
Pandas library for data manipulation
Matplotlib library for data visualization in Python
Power BI Desktop (for creating dashboards)

#Python Data Cleaning and Preparation
Data Loading: The project starts by loading tennis Grand Slam data from an Excel file using the Pandas library.

Data Cleaning: Missing values are removed from the dataset using the dropna function. Rows with missing values in specific columns are dropped.

Data Type Conversion: Some columns, such as 'WINNER_ATP_RANKING' and 'RUNNER-UP_ATP_RANKING,' are converted to integer data types for numerical analysis.

Duplicate Removal: Duplicate rows are removed from the dataset using the drop_duplicates function.

Text Data Transformation: Text data in columns like 'WINNER' and 'RUNNER-UP' is transformed to lowercase, and 'TOURNAMENT' and 'WINNER_NATIONALITY' are transformed to lowercase and uppercase, respectively.

Data Filtering: The dataset is filtered to include only records from the year 2000 to 2023.

Data Export: The cleaned and transformed dataset is exported to a CSV file named 'cleaned_tennis_grand_slam_data.csv' for further analysis and visualization.

#Power BI Visualization
Data Import: The cleaned CSV file is imported into Power BI Desktop.

Data Modeling: Relationships between tables are established, and measures are created to analyze player wins per year and player total wins.

Visualization Creation: Interactive visualizations, including bar charts showing the number of wins per year for players, a pie chart showing the distribution of wins among players, and more, are created in Power BI.

Dashboard Design: Dashboards are designed to provide a user-friendly interface for exploring the data and gaining insights.

#Features
Data Loading: Load tennis Grand Slam data from an Excel file.

Data Cleaning: Remove missing values, drop duplicates, and transform text data.

Data Preparation: Convert data types, filter data for specific years.

Data Export: Export cleaned and prepared data to a CSV file.

Power BI Integration: Import cleaned data into Power BI Desktop.

Data Modeling: Establish data relationships and create measures for analysis.

Visualization Creation: Generate interactive visualizations such as bar charts and pie charts.

Dashboard Design: Create user-friendly dashboards for data exploration.

Player Analysis: Analyze player wins per year and total wins.
