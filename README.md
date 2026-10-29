# Employee Data Analysis and Visualization

## Project Overview
This project analyzes employee data using Python, Pandas, Matplotlib, and Seaborn. It explores employee distribution, salary statistics, department-wise and city-wise comparisons, and visual patterns through charts.

## Dataset
The dataset is stored in `clean_data.csv` and contains the following columns:

- `id` — Employee ID
- `name` — Employee name
- `department` — Department name
- `salary` — Monthly salary in INR
- `city` — Employee's city

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn

## Project Structure

```text
employee-data-analysis/
├── clean_data.csv
├── requirements.txt
├── README.md
├── your_script.py
└── reports/
    └── figures/
        ├── 01_department_bar.png
        ├── 02_salary_histogram.png
        ├── 03_employee_scatter.png
        ├── 04_sorted_salary_line.png
        └── 05_salary_boxplot.png
```

Replace `your_script.py` with the actual name of your Python script.

## Requirements

- Python 3.9 or later
- pip package manager

## How to Run the Project

### Step 1: Clone or download the project

If using Git:

```bash
git clone YOUR_REPOSITORY_URL
cd employee-data-analysis
```

Alternatively, open the downloaded project folder in VS Code.

### Step 2: Create a virtual environment (recommended)

```bash
python -m venv .venv
```

Activate it on Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

### Step 3: Install dependencies

```bash
python -m pip install -r requirements.txt
```

### Step 4: Check the dataset

Make sure `clean_data.csv` is in the project root folder, alongside the Python script.

### Step 5: Run the analysis

```bash
python your_script.py
```

Replace `your_script.py` with your actual Python filename.

The script displays five charts and saves them as PNG files in `reports/figures/`. The output folder is created automatically if it does not exist.

## Visualizations

1. Bar chart — employee count by department
2. Histogram — salary distribution
3. Scatter plot — employee ID versus salary
4. Line chart — sorted salary values
5. Box plot — salary distribution and potential outliers

Each chart includes a title, labelled axes, units where applicable, and an insight statement.

## Key Findings

- IT has the highest employee count, with 3 employees.
- The average monthly salary is ₹58,500.
- Mumbai has the highest average monthly salary in this sample, at ₹69,000.

## Limitations

The dataset contains only eight employees. Results may not represent the wider organization. The line chart shows sorted salaries rather than a time trend because the dataset has no date column.

## Author
Employee Data Analysis Project
