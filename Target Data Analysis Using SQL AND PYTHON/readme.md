# Target Data Analysis and Visualization

This project involves analyzing and visualizing data from Target, a popular retail store in the USA. The data was explored and processed using SQL and Python, focusing on generating insights through a series of queries across different complexity levels.

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Data Transfer](#data-transfer)
- [Analysis and Visualization](#analysis-and-visualization)
- [Usage](#usage)

## Project Overview

The objective of this project was to perform comprehensive data analysis on Target's sales data using SQL and Python. The analysis involved querying the data to extract meaningful insights and visualizing the results to better understand the underlying patterns and trends.

## Technologies Used

- **Python**: For data manipulation, analysis, and visualization.
- **SQL (MySQL)**: For querying and managing data.
- **MySQL Connector**: For transferring data from CSV files to MySQL databases.
- **Jupyter Notebook**: For writing and executing Python and SQL queries.
- **SQL Connect**: For connecting Jupyter Notebook with MySQL databases.
- **Pandas**: For data manipulation and analysis.
- **Numpy**: For numerical computing.
- **Matplotlib**: For creating static, interactive, and animated visualizations.
- **Seaborn**: For making statistical graphics.

## Data Transfer

The raw data was stored in CSV files. MySQL Connector was used to transfer this data into a MySQL database, where it was then queried and analyzed.

## Analysis and Visualization

The data was analyzed using SQL queries, and the results were visualized using Python libraries like Matplotlib and Seaborn. Pandas and Numpy were utilized for data manipulation and preparation, enabling more effective analysis and visualization.

## Usage

To replicate the analysis:
1. **Install the required libraries**:
   ```bash
   pip install mysql-connector-python jupyter pandas numpy matplotlib seaborn
   ```
2. **Set up the MySQL database**:
   - Import the data from CSV files into MySQL using MySQL Connector.
   - Ensure the database is correctly connected to Jupyter Notebook.

3. **Run the analysis**:
   - Open the Jupyter Notebook.
   - Execute the provided SQL queries to analyze the data.

4. **Visualize the results**:
   - Use Matplotlib and Seaborn to create visualizations based on the analysis.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request for any improvements or additional analyses.
