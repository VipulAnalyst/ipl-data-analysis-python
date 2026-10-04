# IPL Data Analysis with Python

A practical Exploratory Data Analysis (EDA) project using IPL match data with **Python**, **pandas**, and **Matplotlib**.

## Project Objective

The goal of this project is to explore IPL match data and practice a complete analytical workflow: loading data, understanding its structure, selecting and filtering records, creating reusable analysis logic, and visualizing key patterns.

## Work Performed

- Loaded IPL match data with pandas
- Inspected dataset dimensions using `shape`
- Reviewed columns and data types using `info()`
- Generated descriptive statistics using `describe()`
- Selected individual and multiple columns
- Used `iloc` for row and column indexing
- Counted team appearances with `value_counts()`
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
| `ipl_data_eda.ipynb` | Main analysis notebook |
| `README.md` | Project documentation |

## Dataset

The notebook expects the IPL match dataset to be available locally as:

```text
matches.csv
```

The dataset itself is not included in this repository yet.

## Skills Demonstrated

- Data inspection
- DataFrame indexing and slicing
- Boolean filtering
- Frequency analysis
- Reusable Python functions
- Exploratory data analysis
- Data visualization

## Note

This repository reflects the analysis contained in the notebook itself. Additional cleaning or preprocessing steps should only be documented when they are present in the project code.
