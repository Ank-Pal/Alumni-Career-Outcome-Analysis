# Alumni Career Outcome Analysis

## 📌 Project Overview

This project analyzes the career outcomes of alumni from **College A** and **College B**, categorized into:
- 🎓 Higher Studies (HS)
- 💼 Service/Job (SJ)
- 🚀 Self-Employment (SE)

The aim is to extract meaningful insights about alumni career paths using SQL, Python, Excel, and Tableau.

---

## 🗂️ Features

- **MySQL Database Setup:** A database named `alumni` is created and populated with CSV data.
- **Data Cleaning:** Null values are removed, and text data (e.g., names) is normalized.
- **SQL Views:** Created to filter and process data effectively.
- **Python Scripting:** Used for importing, querying, and analyzing data.
- **Excel & Tableau Visualizations:** Created to showcase career trends and college comparisons.

---

## 📁 Project Structure

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

---

## ⚙️ Setup & Installation

### 1. Database Configuration
- Run `create_database.sql` to create the `alumni` database.
- Use `import_data.sql` to import CSV data into MySQL tables.
- Execute `views.sql` to create filtered and normalized views.

### 2. Python Environment
Install dependencies:

```bash
pip install -r requirements.txt
### 3. Run Python Scripts

- `data_analysis.py` – for querying and summarizing data from the database.
- `visualize_data.py` *(optional)* – for extra visualizations.

---

## 📊 Visualizations (Tableau)

Open the `alumni_career_outcome.twbx` Tableau file to explore:

- 📅 Year-wise distribution of career paths  
- 🏫 College A vs College B comparisons  
- 📈 Visual dashboards for career insights  

---

## 📦 Data Sources

- `college_a_alumni.csv`  
- `college_b_alumni.csv`  

These files include records of alumni and their categorized career outcomes.

---

## 🤝 Contribution

Feel free to fork this repository, suggest improvements, or raise issues.
