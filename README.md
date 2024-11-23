# data_week5
Data Bootcamp Week 5 - HW

Pymaceuticals Inc. Analysis

This project analyzes drug regimens' effectiveness in reducing tumor volumes in mice during a pharmaceutical study. The results include insights into various treatments, tumor volume distributions, and correlations between variables like weight and tumor size.

Overview

The notebook contains the following analyses:
Capomulin Treatment: Tumor volume analysis for individual mice under Capomulin treatment.
Summary Statistics: Key descriptive statistics for tumor volumes.
Bar and Pie Charts: Visual representation of data such as treatment distribution and gender representation.
Box and Violin Plots: Tumor volume comparisons across different drug regimens.
Correlation Analysis: Examines the relationship between mouse weight and tumor volume.


Key Results

1. Capomulin Treatment Effectiveness
Tumor volumes decreased significantly, particularly after Day 20, indicating Capomulin's potential as an effective drug.
2. Tumor Volume by Drug
Boxplot Analysis: Capomulin and Ramicane show lower median tumor volumes compared to other drugs.
Violin Plot Analysis: Distribution of tumor volumes supports that Capomulin and Ramicane have tighter and lower tumor volumes, indicating better efficacy.
3. Mouse Gender Representation
Male and female mice are almost evenly represented, ensuring balanced data analysis.
4. Correlation Between Weight and Tumor Volume
Positive correlation observed: Heavier mice tend to have larger tumor volumes, which may influence drug efficacy evaluations.


How to Use

Dependencies
Ensure the following libraries are installed:

matplotlib
pandas
numpy
scipy
seaborn


Data
Place the following datasets in the data/ folder:

Mouse_metadata.csv
Study_results.csv


Run the Notebook
Open HW5.ipynb in Jupyter Notebook.
Execute cells sequentially to load data, calculate statistics, and generate visualizations.


File Structure

HW5.ipynb: Main analysis notebook.
data/: Folder containing the datasets.
