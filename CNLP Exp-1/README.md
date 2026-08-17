# CNLP Lab

Coursework for the **CNLP Lab** — data analysis experiments in Python.

---

## Experiment 1 — Employee Data Analysis

Ten exercises over a 100-row employee dataset, covering grouped aggregations,
distributions, correlation and the matching visualisations.

### Files

| File | Description |
|---|---|
| [`Exp-1.ipynb`](Exp-1.ipynb) | The notebook — all ten experiments |
| [`employee_information_100.csv`](employee_information_100.csv) | Dataset: 100 records, 7 columns |
| [`Experiment-1.docx`](Experiment-1.docx) | Problem statement |

### Dataset schema

| Column | Type | Description |
|---|---|---|
| `Employee_ID` | string | Unique identifier (`E001`–`E100`) |
| `Name` | string | Employee name |
| `Department` | string | One of HR, IT, Finance, Marketing, Operations, Sales |
| `Age` | int | 22–59 |
| `Gender` | string | Male / Female |
| `Salary` | int | 30,000–119,000 |
| `Experience_Years` | int | 0–35 |

### The ten experiments

| # | Task |
|---|---|
| 1.1 | Average salary of each department (bar chart) |
| 1.2 | Number of employees in each department |
| 1.3 | Percentage of male and female employees (pie chart) |
| 1.4 | Salary distribution (histogram) |
| 1.5 | Experience vs. salary (scatter plot) |
| 1.6 | Top 10 employees by salary |
| 1.7 | Highest salary in every department |
| 1.8 | Employees earning above the overall average |
| 1.9 | Average years of experience per department |
| 1.10 | Age distribution (histogram) |

---

## Running it

```bash
pip install pandas matplotlib jupyter
jupyter notebook Exp-1.ipynb
```

The notebook loads the dataset by absolute path, so update the path in the
`pd.read_csv(...)` cell to point at your copy of `employee_information_100.csv`.

---

## Tools

`pandas` for data manipulation, `matplotlib` for visualisation, Jupyter Notebook as the
working environment.
