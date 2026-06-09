# 📺 Netflix Data Analysis Project

This project involves analyzing a Netflix dataset using Python (pandas and SQL), cleaning the data, and visualizing insights with Power BI. The objective is to explore content distribution, types, durations, and trends over time.

## 📁 Folder Structure

netflix-data-analysis/
├── data/
│ ├── netflix_titles.xlsx # Raw Netflix dataset
│ └── CLEANED_DATA.xlsx # Cleaned data after preprocessing
├── scripts/
│ ├── clean.py # Python script for data cleaning
│ └── clean_using_sql.py # Python script to query data using SQLite
├── database/
│ └── cleaned_data.db # SQLite database generated from cleaned data
├── dashboard/
│ └── netflix_dashboard.pbix # Power BI dashboard file
├── README.md # Project documentation


---

## 📊 Key Tasks Performed

### ✅ Data Cleaning
- Removed or handled null values
- Standardized column formats (e.g., `date_added`, `duration`)
- Resolved data type mismatches (e.g., year to integer)

### ✅ Data Querying
- Used `sqlite3` and `pandas.read_sql()` to run SQL queries on the dataset
- Extracted insights like:
  - Number of shows per year
  - Movies vs TV shows distribution
  - Country-wise production frequency
  - Duration patterns by content type

### ✅ Dashboard (Power BI)
- Map of content distribution by country 🌍
- Line/bar chart showing release trends over the years 📈
- Comparison of durations across content types ⏱
- Filters by genre, country, and type

---

## 🧰 Tools & Technologies Used

- **Python** (pandas, sqlite3)
- **Power BI** (interactive dashboards)
- **SQLite** (in-memory + persistent queries)
- **Excel** (for initial and final data handling)

---

## Author:Debi Beura
