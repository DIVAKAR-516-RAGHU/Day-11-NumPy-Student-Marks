````markdown
# Day 11 – NumPy Student Marks

## VEDA Technology – AI & ML Internship

### Task 11: NumPy Student Marks

---

## Objective

To create a NumPy array containing student marks and perform basic statistical analysis using NumPy functions.

The following statistical values are calculated:

- Mean
- Median
- Maximum
- Minimum
- Standard Deviation

---

## Task Description

In this task, a NumPy array containing the marks of 10 students was created. NumPy statistical functions were used to analyze the marks and calculate important numerical values.

This task demonstrates how NumPy can be used for numerical data analysis in Python.

---

## Technologies Used

- Python
- NumPy
- Jupyter Notebook
- GitHub

---

## Student Marks

The following marks were used for the analysis:

78, 85, 92, 67, 74, 88, 95, 81, 69, 90

---

## Implementation

### Import NumPy

```python
import numpy as np
````

### Create Student Marks Array

```python
marks = np.array([78, 85, 92, 67, 74, 88, 95, 81, 69, 90])

print("Student Marks:")
print(marks)
```

### Calculate Statistical Values

```python
mean_marks = np.mean(marks)
median_marks = np.median(marks)
maximum_marks = np.max(marks)
minimum_marks = np.min(marks)
standard_deviation = np.std(marks)
```

### Display Results

```python
print("===== Student Marks Statistics =====")
print("Number of Students:", len(marks))
print("Mean:", mean_marks)
print("Median:", median_marks)
print("Maximum:", maximum_marks)
print("Minimum:", minimum_marks)
print("Standard Deviation:", standard_deviation)
```

---

## Results

| Statistic          | Value |
| ------------------ | ----: |
| Number of Students |    10 |
| Mean               | 81.90 |
| Median             | 83.00 |
| Maximum            |    95 |
| Minimum            |    67 |
| Standard Deviation |  9.04 |

---

## Explanation

### Mean

The mean represents the average marks of all the students.

Mean = 81.90

### Median

The median represents the middle value of the dataset after arranging the values in ascending order.

Median = 83.00

### Maximum

The maximum value represents the highest mark obtained by a student.

Maximum = 95

### Minimum

The minimum value represents the lowest mark obtained by a student.

Minimum = 67

### Standard Deviation

Standard deviation indicates how much the marks vary from the mean.

Standard Deviation ≈ 9.04

---

## NumPy Functions Used

| Function      | Purpose                           |
| ------------- | --------------------------------- |
| `np.array()`  | Creates a NumPy array             |
| `np.mean()`   | Calculates the mean               |
| `np.median()` | Calculates the median             |
| `np.max()`    | Finds the maximum value           |
| `np.min()`    | Finds the minimum value           |
| `np.std()`    | Calculates the standard deviation |

---

## Learning Outcomes

Through this task, I learned:

* How to create NumPy arrays.
* How to perform statistical calculations using NumPy.
* How to calculate mean and median.
* How to find maximum and minimum values.
* How to calculate standard deviation.
* How NumPy can be used for numerical data analysis.
* How numerical data processing is useful in Machine Learning.

---

## Interview Questions

### 1. What is NumPy?

NumPy, which stands for Numerical Python, is a Python library used for numerical and scientific computing. It provides multidimensional arrays and efficient functions for performing mathematical and numerical operations.

### 2. Why is NumPy useful in Machine Learning?

NumPy is useful in Machine Learning because it provides efficient array operations, mathematical functions, statistical calculations, and matrix operations for numerical data processing.

### 3. What is a NumPy array?

A NumPy array is a data structure provided by NumPy that stores elements and supports efficient numerical operations.

Example:

```python
marks = np.array([78, 85, 92, 67, 74])
```

### 4. What is the difference between mean and median?

The mean is the average of all values in a dataset, while the median is the middle value after arranging the data in ascending or descending order.

### 5. What is standard deviation?

Standard deviation is a statistical measure that indicates the amount of variation or dispersion in a dataset relative to its mean.

A lower standard deviation generally indicates that the values are closer to the mean, while a higher standard deviation indicates greater spread.

### 6. How do you calculate the mean using NumPy?

The `np.mean()` function is used.

```python
np.mean(marks)
```

### 7. How do you calculate standard deviation using NumPy?

The `np.std()` function is used.

```python
np.std(marks)
```

---

## Conclusion

This task demonstrated the use of NumPy for basic statistical analysis of student marks. By using functions such as `np.mean()`, `np.median()`, `np.max()`, `np.min()`, and `np.std()`, numerical data can be analyzed efficiently using Python.

The task provided practical experience with NumPy arrays and statistical operations that are commonly used in data analysis and Machine Learning.

---

## Internship Details

**Organization:** VEDA Technology
**Program:** AI & ML Internship
**Day:** 11
**Task:** NumPy Student Marks
**Tools:** Python, NumPy, Jupyter Notebook

```
```
