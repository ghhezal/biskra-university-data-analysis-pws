# PW1: Introduction to Data Analysis with Python

This practical work covers the basic steps of data analysis in Python using a small student dataset.

## What this PW covers

The dataset contains information about 10 students, including age, gender, study hours, grades, and absences.
The work includes:

- inspecting the dataset with `head()`, `tail()`, `shape`, and `info()`
- calculating descriptive statistics such as mean, median, minimum, maximum, and standard deviation
- checking categorical frequencies and proportions
- visualizing grade distribution with a histogram and boxplot
- detecting possible outliers using the IQR method
- finding and handling missing values
- checking and removing duplicated rows
- analyzing the relationship between study hours and grades with a scatter plot
- calculating and visualizing correlations
- comparing average grades, study hours, and absences by gender

## What I found

- The average grade is 12.3 and the median is 12.75.
- The grade histogram has more observations at the lower and higher ranges, with fewer grades in the middle.
- Study hours and grades have a strong positive correlation.
- Absences and grades have a strong negative correlation.
- Study hours and absences are also strongly negatively correlated.
- No clear grade outliers were detected with the IQR method.

## Data cleaning

The exercise also introduces some basic cleaning steps.

A missing grade is added manually using `np.nan`, then replaced with the mean grade. Duplicate rows are checked with `duplicated()` and can be removed using `drop_duplicates()`.

## Visualizations

The notebook includes:

- histogram
- boxplot
- scatter plot
- correlation heatmap

These were useful for checking the distribution of grades, possible outliers, and relationships between numeric variables.

## Stack

Python, NumPy, Pandas, Matplotlib, Seaborn
