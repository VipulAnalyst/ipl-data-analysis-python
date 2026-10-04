# IPL Data Analysis with Python

A practical **Exploratory Data Analysis (EDA)** project using IPL match data with **Python**, **pandas**, and **Matplotlib**.

## Project Objective

The goal of this project is to explore IPL match data and practice a structured analytical workflow: loading data, understanding its structure, selecting and filtering records, creating reusable analysis logic, and visualizing key patterns.

## Dataset

The project uses an IPL match dataset containing **636 rows and 18 columns**.

The dataset is included in this repository as:

```text
matches.csv
```

## Analysis Performed

- Loaded IPL match data with pandas
- Inspected dataset dimensions using `shape`
- Reviewed columns and data types using `info()`
- Generated descriptive statistics using `describe()`
- Selected individual and multiple columns
- Used `iloc` for row and column indexing
- Counted team appearances using `value_counts()`
- Filtered matches by city
- Created a reusable `get_city_count()` function
- Analyzed match winners
- Visualized winner frequency with a bar chart
- Analyzed toss decisions
- Visualized toss decisions with a pie chart

## Tools & Libraries

- Python
- pandas
- Matplotlib
- Jupyter Notebook

## Repository Structure

| File | Description |
|---|---|
| `ipl_data_eda.ipynb` | Main exploratory data analysis notebook |
| `matches.csv` | IPL match dataset |
| `requirements.txt` | Python dependencies |
| `.gitignore` | Common Python/Jupyter files excluded from version control |
| `README.md` | Project documentation |

## Skills Demonstrated

- Exploratory Data Analysis
- Data inspection
- DataFrame indexing and slicing
- Boolean filtering
- Frequency analysis
- Reusable Python functions
- Data visualization

## How to Run

1. Clone or download this repository.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Open `ipl_data_eda.ipynb` in Jupyter Notebook or VS Code.
4. Run the notebook cells.

## Portfolio Note

This project documents the analysis that is actually present in the notebook and is part of my growing Data Analyst portfolio.
