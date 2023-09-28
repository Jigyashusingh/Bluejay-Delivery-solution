# Assignment Timecard Analyzer

This Python program analyzes an Excel file containing employee timecard data and performs the following tasks:

1. Find employees who have worked for 7 consecutive days.
2. Identify employees with short but reasonable time between shifts.
3. Identify employees who have worked for more than 14 hours in a single shift.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Functions](#functions)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/yourusername/assignment-timecard-analyzer.git
```

2. Install the required libraries using pip:

```bash
pip install pandas openpyxl
```

## Usage

1. Place your Excel file containing timecard data in the root directory of the repository.

2. Modify the `file_path` variable in the code to specify the path to your Excel file:

```python
file_path = "/path/to/your/excel/file.xlsx"
```

3. Run the Python script to analyze the data:

```bash
python analyze_timecard.py
```

The program will print the results of the analysis to the console.

## Functions

### `find_employees_with_consecutive_days(df)`

This function finds employees who have worked for 7 consecutive days.

### `find_employees_with_short_shifts(df)`

This function identifies employees with short but reasonable time between shifts.

### `find_employees_with_long_shifts(df)`

This function identifies employees who have worked for more than 14 hours in a single shift.

## Contributing

Contributions to this project are welcome. You can open an issue or submit a pull request with your improvements.

## Auther

Jigyashu Singh Lodhi
```
