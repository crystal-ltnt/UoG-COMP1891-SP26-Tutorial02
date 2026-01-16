# COMP1891 - Data Fundamentals

## Tutorial 02 | Spring 2026 | University of Greenwich

## Overview

This tutorial focuses on fundamental Python libraries for data science: **NumPy** for numerical computing and **Pandas** for data manipulation and analysis.

---

## Tasks

### Task 1: NumPy Arrays with `arange()`

Create NumPy arrays using the `arange()` function with the following parameters:

1. `5`
2. `6, 20, 2`
3. `0, 51, 5`
4. `10, 2, -2`

**Objective:** Understand how `np.arange()` generates arrays with start, stop, and step values.

---

### Task 2: Descriptive Statistics with NumPy

1. Create a list with a random sample of 10 numbers in the range from 1 to 15
2. Convert the list into a NumPy array
3. Apply descriptive statistics:
   - `sum()`
   - `min()`
   - `max()`
   - `mean()`
   - `var()` - variance
   - `std()` - standard deviation

---

### Task 3: Custom `generate()` Function

Write a function named `generate` that:

- Takes 3 parameters: `low`, `high`, and `num`
- Creates a sample of `num` random numbers between `low` and `high`
- Divides each number by 100
- Returns the output as a list

**Test Cases:**

1. `generate(100, 200, 10)`
2. `generate(1000, 10000, 10)`

Convert the output to a NumPy array and display in each case.

---

### Task 4: Pandas DataFrame - Temperature Data

Create a dictionary containing low and high temperature values for all seven days of the week.

Use `index`, `loc`, `iloc` functions and DataFrame to:

1. Create index for the rows as 'Low' and 'High'
2. Display the 'low' temperature of each day of the week
3. Display low and high temperatures for Tuesday
4. Display the temperatures for a range (Wednesday through Friday)

---

### Task 5: Country Data DataFrame

Create a dictionary with key-value pairs as follows:

| Key            | Value                                                |
| -------------- | ---------------------------------------------------- |
| `country`    | List of 5 countries                                  |
| `capital`    | List of 5 capitals of countries above                |
| `area`       | List of areas of each country (units of your choice) |
| `population` | List of current population of each country           |

**Note:** Search for up-to-date information on the countries' populations.

---

### Task 6: Titanic Dataset Analysis

Import the Titanic dataset to create a DataFrame and perform data analysis as demonstrated in the lecture notes.

---

### Task 7: GitHub Dataset Analysis

Search GitHub and use one dataset of your choice to:

1. Create a DataFrame
2. Perform data analysis as shown in the lecture notes

---

## Prerequisites

- Python 3.x
- NumPy
- Pandas

## Installation

```bash
pip install numpy pandas
```

---

## Learning Outcomes

After completing this tutorial, you should be able to:

- Create and manipulate NumPy arrays
- Apply descriptive statistical functions to data
- Write custom Python functions for data processing
- Create and navigate Pandas DataFrames
- Use indexing methods (`loc`, `iloc`) for data selection
- Perform basic data analysis on real-world datasets
