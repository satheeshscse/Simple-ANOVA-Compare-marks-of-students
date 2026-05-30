# Simple ANOVA Compare Marks of Students

## Description
This Python program performs a **One-Way ANOVA (Analysis of Variance)** test to compare the marks of students from three different classes. It determines whether there is a statistically significant difference between the average marks of the classes.

The program also displays a boxplot to visualize the distribution of marks in each class.

## Features
- Compares marks from three classes.
- Performs One-Way ANOVA using SciPy.
- Displays F-statistic and P-value.
- Determines statistical significance.
- Visualizes data using a boxplot.

## Requirements

Install the required libraries:

```bash
pip install numpy scipy matplotlib
```

## Libraries Used
- NumPy
- SciPy
- Matplotlib

## Sample Data

```python
class_A = [75, 80, 85, 90, 95]
class_B = [70, 72, 78, 74, 76]
class_C = [88, 85, 91, 89, 87]
```

## How to Run

```bash
python simple_anova_compare_marks_of_students.py
```

## Output
The program displays:

- Marks of each class
- F-Statistic value
- P-Value
- Statistical conclusion
- Boxplot showing marks distribution

## Example Result

```text
F-Statistic: 24.56
P-Value: 0.0001
Significant difference exists between groups
```

## Conclusion
ANOVA helps determine whether the mean marks of multiple groups are significantly different. This project demonstrates the use of statistical analysis and data visualization in Python.
