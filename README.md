# -task-14-Pandas-Series-Basics


## Overview
This project demonstrates how to create and manipulate **Pandas Series**, including indexing, filtering, arithmetic operations, and basic statistical analysis.

## Objective
Understand the fundamental one-dimensional data structure in Pandas.

## Tools and Technologies
- Python
- Pandas
- Jupyter Notebook / Google Colab

## Installation
If Pandas is not installed, run:

```python
pip install pandas
```

## Examples

### 1. Import Pandas and create a Series
```python
import pandas as pd

marks = pd.Series([85, 92, 76, 88, 95])
print(marks)
```

### 2. Create a Series with custom indexes
```python
marks = pd.Series(
    [85, 92, 76, 88, 95],
    index=["Ravi", "Priya", "Arun", "Sneha", "Kiran"]
)
print(marks)
```

### 3. Access values using indexing
```python
print(marks["Priya"])
print(marks[["Ravi", "Kiran"]])
```

### 4. Filter values
```python
print(marks[marks >= 85])
```

### 5. Perform arithmetic operations
```python
print(marks + 5)
print(marks * 2)
```

### 6. Calculate basic statistics
```python
print("Mean:", marks.mean())
print("Maximum:", marks.max())
print("Minimum:", marks.min())
print("Summary:")
print(marks.describe())
```

## Suggested Dataset
You can use a small student marks dataset as shown above, or create a Series from a sales dataset.

## Deliverables
- Examples of creating Pandas Series
- Indexing and filtering examples
- Arithmetic operations
- Basic statistical analysis using `mean()`, `max()`, `min()`, and `describe()`

## Interview Questions

**1. What is a Pandas Series?**  
A Pandas Series is a one-dimensional labeled array that can store values of different data types.

**2. How is a Series different from a DataFrame?**  
A Series is one-dimensional, while a DataFrame is a two-dimensional table with rows and columns.

**3. How do you filter a Series?**  
Use a condition inside square brackets, such as `marks[marks >= 85]`.

## How to Run
1. Open Jupyter Notebook or Google Colab.
2. Import Pandas.
3. Copy and run each code example.
4. Review the printed values and statistics.

## Author
Data Science Intern — Veda Technology
