# STUDENT-STUDY-AND-PERFOMANCE-ANALYSIS

## Project Overview

This project uses **Python and Matplotlib** to analyze the relationship between students' study hours and their academic performance.

The project demonstrates two fundamental data visualization techniques:

* **Line Plot** — used to visualize student scores.
* **Scatter Plot** — used to investigate the relationship between study hours and scores.

The goal is to practice turning raw data into meaningful visual insights using Python.

---

## Objectives

The main objectives of this project are to:

* Visualize student scores using a line plot.
* Compare study hours with student scores using a scatter plot.
* Identify the student with the highest score.
* Identify the student with the lowest score.
* Examine the relationship between study hours and scores.
* Calculate and interpret the correlation between study hours and scores.
* Practice using Matplotlib for data visualization.

---

##  Technologies Used

* **Python**
* **Matplotlib**
* **NumPy**

---

## Dataset

The dataset contains information about 10 students.

| Student | Study Hours | Score |
| ------- | ----------: | ----: |
| Ann     |           2 |    50 |
| Brian   |           3 |    55 |
| Carol   |           4 |    62 |
| David   |           5 |    68 |
| Eric    |           6 |    72 |
| Faith   |           7 |    78 |
| George  |           8 |    85 |
| Hellen  |           4 |    60 |
| Ian     |           6 |    75 |
| Jane    |           9 |    92 |

---

## Visualizations

### 1. Student Scores — Line Plot

The line plot displays the scores achieved by each student.

It includes:

* Student names on the X-axis
* Scores on the Y-axis
* Circular markers
* Grid lines
* An annotation for the highest score
* An annotation for the lowest score

The highest score was achieved by **Jane with 92**, while the lowest score was achieved by **Ann with 50**.

### 2. Study Hours vs Scores — Scatter Plot

The scatter plot compares students' study hours with their scores.

* X-axis → Study Hours
* Y-axis → Scores
* Point size → 100
* Transparency → 0.7

The scatter plot shows a **strong positive relationship** between study hours and scores.

---

## Correlation Analysis

The Pearson correlation coefficient was calculated using NumPy:

```python
import numpy as np

correlation = np.corrcoef(study_hours, scores)[0, 1]

print(correlation)
```

The result was approximately:

```text
0.999
```

This indicates an **extremely strong positive linear correlation** between study hours and scores in this dataset.

In general, students who studied more hours tended to achieve higher scores.

> **Note:** Correlation indicates an association between two variables. It does not, by itself, prove that increased study hours cause higher scores.

---

##  Key Insights

1. **Jane achieved the highest score** with 92 marks.
2. **Ann achieved the lowest score** with 50 marks.
3. The scatter plot shows a strong positive relationship between study hours and scores.
4. Students with higher study hours generally achieved higher scores.
5. The calculated correlation coefficient of approximately **0.999** indicates an extremely strong linear relationship in this particular dataset.

---

##  What I Learned

Through this project, I practiced:

* Creating line plots with Matplotlib.
* Creating scatter plots.
* Customizing chart titles and axis labels.
* Adding grid lines.
* Rotating X-axis labels.
* Annotating important observations.
* Finding maximum and minimum values programmatically.
* Using NumPy to calculate correlation.
* Interpreting visual patterns as a data analyst.
* Distinguishing correlation from causation.

---

##  Future Improvements

Possible improvements to this project include:

* Add more student records.
* Calculate additional statistics such as mean, median, and standard deviation.
* Add a trend line to the scatter plot.
* Use pandas DataFrames instead of Python lists.
* Create a regression analysis.
* Build an interactive version using Plotly or Power BI.

---

## Project Structure

```text
student-study-performance/
│
├── student_performance.py
├── README.md
└── images/
    ├── student_scores.png
    └── study_hours_vs_scores.png
```

---

##  Author

**George Njau**

Aspiring Data Analyst | Python | SQL | Excel | Power BI

---

## Project Purpose

This project was created as part of my **Python Data Analysis and Matplotlib learning journey**, with a focus on developing practical data visualization and analytical skills.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9d4606a0-a27d-4cd8-9aa5-41750bfa9899" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/40953a49-b356-44e5-bd11-fd5b00e02353" />

