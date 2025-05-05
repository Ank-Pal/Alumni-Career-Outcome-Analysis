Alumni Career Outcome Analysis
Project Overview
This project focuses on analyzing the career outcomes of alumni from College A and College B. The analysis is based on three career categories:

Higher Studies (HS)

Self-Employment (SE)

Service/Job (SJ)

The goal is to use the provided alumni data, perform data cleaning, and generate meaningful insights into the alumni's career trajectories.

Key Features
Database Setup:
A MySQL database (alumni) is created to store the alumni career data.

Data Cleaning:

Data is imported from CSV files and cleaned by removing any null values.

Text normalization is performed on the data (e.g., converting names to lowercase).

Data Import and Analysis:

Python is used to fetch and process data from the database.

Views are created for filtering out null values and normalizing text data.

Visualizations:

The cleaned data is analyzed and visualized in Excel and Tableau.

Visualizations include trends and comparisons of alumni career paths over time and by college.

Comparison of Colleges:

Data from both College A and College B is compared to evaluate their alumni's career outcomes.

Project Structure
graphql
Copy
Edit
├── data/
│   ├── college_a_alumni.csv       # CSV data for College A alumni
│   ├── college_b_alumni.csv       # CSV data for College B alumni
│   └── cleaned_data.csv           # Final cleaned data
│
├── sql/
│   ├── create_database.sql        # SQL script to create MySQL database
│   ├── import_data.sql            # SQL script to import data from CSV files
│   └── views.sql                  # SQL script for data views and procedures
│
├── python/
│   ├── data_analysis.py           # Python script for data analysis and extraction
│   └── visualize_data.py          # Python script to visualize data (if necessary)
│
├── tableau/
│   └── alumni_career_outcome.twbx  # Tableau workbook with visualizations
│
├── README.md                      # Project documentation
└── requirements.txt               # Python dependencies
Setup and Installation
1. Database Setup
To set up the database, run the following SQL scripts:

create_database.sql: Creates the MySQL database.

import_data.sql: Imports data from the CSV files into the database.

views.sql: Creates views to filter null values and normalize text.

2. Python Dependencies
The Python scripts require the following libraries:

pandas for data manipulation.

mysql-connector-python for database interaction.

matplotlib and seaborn for data visualization (if applicable).

openpyxl for working with Excel files.

Install the dependencies using:

bash
Copy
Edit
pip install -r requirements.txt
3. Running the Python Scripts
Data Analysis:
Run data_analysis.py to analyze the alumni data from the database and generate key statistics.

Visualization (Optional):
If you need to generate additional visualizations, run visualize_data.py.

4. Tableau Visualizations
The alumni_career_outcome.twbx file is a Tableau workbook containing visualizations of the career outcomes. It contains the following features:

Trend analysis of alumni's career paths.

Comparative analysis between College A and College B.

Geographic and categorical breakdowns of alumni outcomes.

Data Source
The data is provided in CSV format for both colleges:

college_a_alumni.csv

college_b_alumni.csv

These files contain alumni information categorized by career outcomes (Higher Studies, Self-Employment, Service/Job).

Contribution
Feel free to fork this repository, contribute, or open issues if you find any problems.
