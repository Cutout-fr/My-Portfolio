# My Portfolio – Expense Tracker Script

This is a Python script that cleans up messy expense data from a CSV file and gives back:

- A clean Excel sheet
- A bar chart of category-wise spending
- A text summary with total + top 3 categories

## What it does

- Removes stuff like ₹, Rs, $, commas from the amount column
- Fixes typos in categories (like "Transpot" → "Transport")
- Parses weird date formats properly
- Drops any rows with missing values in date, amount or category
- Groups expenses by category and calculates totals

## Output files

- `cleaned_sheet.xlsx` – cleaned-up Excel report
- `chart_exp.png` – bar chart of spending per category
- `summary.txt` – total spend and top 3 categories
- `code.py` – main script
- `messy_file.csv` – sample messy input

## Tech used

Just `pandas`, `matplotlib`, `openpyxl`, and `dateutil`.

---
Made by a 15 yo 11th grader passionate about Python and automation.  
Reach out if you want something like this cleaned fast
