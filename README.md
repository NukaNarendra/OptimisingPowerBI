Power BI Performance Analysis Project

Overview

This project focuses on analyzing Power BI performance by integrating data from CSV and MySQL, processing it using Python, and visualizing it in Power BI. The project follows a structured workflow involving data extraction, processing, database management, Power BI analysis, and visualization.

Workflow

Load the CSV file (pizza.csv) into the Python environment.

Execute the first Python script (main.py) to process the CSV data.

Open MySQL and run the necessary commands from my sql code.txt to store processed data in the database.

Connect MySQL to Power BI using the Power BI MySQL connector.

Open the Power BI project file (final_project_of_mine.pbix) and analyze the data.

Generate PowerBIPerformanceData.json using the Power BI Performance Analyzer.

Load the JSON file into Python and run the second Python script (main-2.py).

Visualize the results using Matplotlib and Seaborn, which generates:

Boxplot (for event duration distribution)

Bar chart (for event frequency)

Line plot (for event occurrence trends over time)

Setup and Installation

Prerequisites

Python 3.8 or above

MySQL

Power BI Desktop

Installation

Clone the repository:

git clone https://github.com/YaswanthBellana/PowerBI-Performance-Analysis.git
cd PowerBI-Performance-Analysis

Install the required Python libraries:

pip install pandas mysql-connector-python
pip install matplotlib seaborn

Usage

1. Run the First Python Script (main.py)

python main.py

This processes the CSV file and prepares data for MySQL.

2. Execute MySQL Commands

Open MySQL and run:

source "my sql code.txt"

This creates necessary tables and inserts data.

3. Load Data into Power BI

Open Power BI

Connect MySQL database using MySQL Connector

Open final_project_of_mine.pbix

Use Performance Analyzer to generate PowerBIPerformanceData.json

4. Run the Second Python Script (main-2.py)

python main-2.py

This visualizes Power BI performance data.

Results

The following visualizations are generated:

Boxplot: Analyzes Power BI event durations.

Bar Chart: Displays the frequency of different event types.

Line Plot: Shows the occurrence of events over time.

Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to enhance the project.

