# My Portfolio – Messy CSV Cleanup

This is a Python script that cleans up messy expense data from a CSV file and gives back:

- A Clean Excel Sheet
- A Bar Chart of Category-wise Spending
- A Text Summary with Total + Top 3 Categories (₹-wise)

## What it does

- Removes Stuff like ₹, Rs, $, commas from the amount column
- Fixes typos in Categories (like "Transpot" → "Transport")
- Parses weird Date Formats properly
- Drops any rows with missing values in Date, Amount or Category
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
