## Description

This project focuses on practicing the use of the **Pandas** library for data analysis and manipulation in Python. Pandas is a powerful library that provides high-level data structures and tools for working with tabular data, widely used in data analysis, statistics, and scientific research.

## Installation

To use Pandas, install the library with pip:

```bash
pip install pandas
```

## Key Features

- **DataFrame Creation**: Easily create and manipulate DataFrames, which represent two-dimensional labeled data.
- **Data Selection**: Use `.loc` and `.iloc` methods for selecting data by labels and positions.
- **Handling Missing Values**: Tools for removing or filling in missing data.
- **Data Analysis**: Functions for aggregation, grouping, and pivot tables for quick statistical insights.

## Practice

In this project, I practice using Pandas on tasks such as:

- Creating DataFrames with student grades.
- Modifying data and adding new columns.
- Checking for duplicates and null values.

## Example

Here’s a simple example of creating a DataFrame with student grades:

```python
import pandas as pd

data = {
    'Name': ['Alice', 'Bob', 'Charlie'],
    'Math': [85, 90, 78],
    'Literature': [88, 92, 85]
}

df = pd.DataFrame(data)
print(df)
```

## Conclusion

Pandas is an essential tool for data analysis in Python. I continue to explore its features and apply them in various projects.
