# EDA Student Performance

This project is an Exploratory Data Analysis (EDA) of student performance data from secondary education.

## Dataset

The analysis uses the student-por.csv file included in this repository.

Based on the file name and the column structure, this dataset appears to match the original UCI Student Performance dataset for the Portuguese language course:
[UCI Student Performance Dataset](https://archive.ics.uci.edu/ml/datasets/Student%20Performance)

The dataset includes information such as:
- school
- gender
- age
- address type
- family background
- parents' education and jobs
- study time
- past failures
- internet access
- extra activities
- alcohol consumption
- absences
- grades G1, G2, and G3

## What Happens In This EDA

In the notebook, the dataset is first loaded and checked using:
- shape and data type inspection
- null value checks
- basic overview of columns

After that, the notebook explores student-related patterns through visualizations and comparisons, including:
- school distribution
- age distribution
- urban vs rural address distribution
- reason for choosing school
- extracurricular activity participation
- weekday and weekend alcohol consumption
- parents' education levels
- study time vs grades
- internet access vs final grade
- gender and address compared with final grade
- numeric feature spread using boxplots
- correlation analysis with a heatmap

## Purpose

The main purpose of this EDA is to understand which student and lifestyle factors are associated with academic performance.

This project helps answer questions like:
- which student groups appear more in the dataset
- how study time relates to grades
- whether internet access shows any difference in performance
- how family and lifestyle variables connect with student outcomes
- how grades G1, G2, and G3 relate to each other

## Files

- 5. EDA Student Performance.ipynb : Jupyter notebook with the full EDA
- student-por.csv : dataset used in the analysis