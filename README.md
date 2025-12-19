# Coffee Sales Data Preprocessing

This project demonstrates a complete data preprocessing workflow using Python and pandas.
The goal is to transform heterogeneous, multi-year Excel sales data into a clean,
consistent, and analysis-ready dataset.

---

## Project Overview

Sales data from a fictional coffee company was collected over multiple years
(2019–2021) and stored in separate Excel files. Due to manual data entry,
the raw datasets contain typical real-world issues such as:

- inconsistent column names
- mixed data types and formats
- spelling variations in categorical values
- missing values
- duplicate records
- potential outliers

This project focuses on systematically identifying and addressing these issues
while documenting all preprocessing decisions transparently.

---

## Data Sources

- Three Excel files containing yearly sales data:
  - `Kaffeebohnen_2019.xlsx`
  - `Kaffeebohnen_2020.xlsx`
  - `Kaffeebohnen_2021.xlsx`

The original files are stored unchanged in the `data/raw/` directory.

---

## Key Preprocessing Steps

- Loading and inspecting multiple Excel data sources
- Standardizing column names across datasets
- Consolidating yearly data into a single DataFrame
- Assessing data quality (missing values, duplicates, data types)
- Correcting spelling variations in categorical columns
- Converting columns to appropriate numeric and datetime types
- Identifying and evaluating potential outliers
- Removing duplicate records
- Validating the final dataset
- Exporting a cleaned, analysis-ready Excel file

---

## Project Structure

```text
coffee-sales-data-preprocessing/
│
├── README.md
├── notebook.ipynb
│
├── data/
│   ├── raw/
│   │   ├── Kaffeebohnen_2019.xlsx
│   │   ├── Kaffeebohnen_2020.xlsx
│   │   └── Kaffeebohnen_2021.xlsx
│   │
│   └── processed/
│       └── Kaffeebohnen_2019_2021_clean.xlsx
