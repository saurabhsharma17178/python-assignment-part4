# Python Assignment — Part 4

## Data Visualization & Machine Learning

### Student Performance Analysis & Prediction

## Project Overview

This project analyzes a student performance dataset, creates visualizations, and builds a machine learning model to predict whether a student will pass or fail.

The project uses:

* Pandas for data analysis
* Matplotlib for data visualization
* Seaborn for advanced visualization
* Scikit-learn for machine learning

---

## Dataset

The dataset is stored in **students.csv** and contains the following columns:

* name
* math
* science
* english
* history
* pe
* attendance_pct
* study_hours_per_day
* passed (1 = Pass, 0 = Fail)

---

## Task 1 — Data Exploration (Pandas)

In this task:

* Loaded the dataset using pandas
* Displayed first 5 rows
* Checked dataset shape and data types
* Generated summary statistics
* Counted number of students who passed and failed
* Calculated average subject scores for pass and fail students
* Found the student with the highest overall average score

---

## Task 2 — Data Visualization (Matplotlib)

Created the following plots:

* Bar chart — Average score per subject
* Histogram — Distribution of math scores
* Scatter plot — Study hours vs average score
* Box plot — Attendance percentage for pass vs fail students
* Line plot — Math and Science scores per student

All plots were saved as PNG files.

---

## Task 3 — Data Visualization (Seaborn)

Created:

* Seaborn bar plot for average math and science scores by pass/fail
* Seaborn scatter plot for attendance vs average score with regression lines

Plots were saved as PNG files.
# Python Assignment — Part 4

## Data Visualization & Machine Learning

### Student Performance Analysis & Prediction

---

## Project Overview

This project analyzes a student performance dataset, creates visualizations, and builds a machine learning model to predict whether a student will pass or fail.

Technologies used:

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## Dataset

The dataset is stored in **students.csv** and contains the following columns:

* name
* math
* science
* english
* history
* pe
* attendance_pct
* study_hours_per_day
* passed (1 = Pass, 0 = Fail)

---

## Task 1 — Data Exploration with Pandas

In this task:

* Loaded the dataset using pandas
* Displayed first 5 rows using `head()`
* Checked dataset shape and data types
* Generated summary statistics using `describe()`
* Counted number of students who passed and failed
* Calculated average subject scores for pass and fail students
* Found the student with the highest overall average score

This task helped understand the dataset structure and performance trends.

---

## Task 2 — Data Visualization with Matplotlib

Created the following plots:

* Bar chart — Average score per subject
* Histogram — Distribution of math scores
* Scatter plot — Study hours vs average score
* Box plot — Attendance percentage for pass vs fail students
* Line plot — Math and Science scores per student

All plots were saved as PNG image files.

---

## Task 3 — Data Visualization with Seaborn

Created:

* Seaborn bar plot showing average math and science scores split by pass/fail
* Seaborn scatter plot showing attendance vs average score with regression lines

Seaborn made visualization easier and cleaner compared to Matplotlib.

---

## Task 4 — Machine Learning with Scikit-Learn

In this task:

* Selected features:

  * math
  * science
  * english
  * history
  * pe
  * attendance_pct
  * study_hours_per_day
* Target variable: passed
* Split data into training (80%) and testing (20%)
* Scaled features using StandardScaler
* Trained Logistic Regression model
* Calculated training accuracy and test accuracy
* Predicted results for test students
* Displayed feature importance using model coefficients
* Predicted pass/fail for a new student

This task demonstrated the complete machine learning workflow:
Data → Train → Test → Predict → Interpret model.

---

## Files in Project Folder

```
python-assignment-part4/
    part4_visualization_ml.ipynb
    students.csv
    plot_bar.png
    plot_histogram.png
    plot_scatter.png
    plot_box.png
    plot_line.png
    seaborn_bar.png
    seaborn_scatter.png
    feature_importance.png
    README.md
```

---

## Conclusion

This project demonstrates:

* Data analysis using Pandas
* Data visualization using Matplotlib and Seaborn
* Machine learning using Logistic Regression
* Model evaluation and prediction

The project shows a complete data analysis and machine learning workflow in Python.
