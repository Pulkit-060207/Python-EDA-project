# 📊 Students Performance in Exams - EDA

## About the Project

This project performs **Exploratory Data Analysis (EDA)** on the **Students Performance in Exams** dataset.

The main purpose of this project is to analyze students' performance in **Math, Reading, and Writing** and understand how different factors affect or relate to their scores.

## Dataset

The dataset is taken from Kaggle:

https://www.kaggle.com/datasets/spscientist/students-performance-in-exams

The dataset contains information about **1000 students**.

It includes:

* Gender
* Race/Ethnicity
* Parental Level of Education
* Lunch
* Test Preparation Course
* Math Score
* Reading Score
* Writing Score

## Technologies Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

## EDA Performed

The following analysis is performed on the dataset:

1. Checking the first few records of the dataset.
2. Checking the dataset information and statistical summary.
3. Checking for missing values.
4. Checking for duplicate values.
5. Finding average scores in Math, Reading, and Writing.
6. Comparing student performance based on different categories.

## Visualizations

### 1. Gender Distribution

A bar chart is used to show the number of male and female students.

### 2. Average Score by Gender

A bar chart compares the average Math, Reading, and Writing scores of male and female students.

### 3. Score Distribution

Histograms are used to understand the distribution of Math, Reading, and Writing scores.

### 4. Test Preparation vs Scores

A bar chart compares the average scores of students who completed the test preparation course with those who did not.

### 5. Parental Education vs Score

A bar chart compares average student scores according to their parents' education level.

### 6. Lunch Type vs Scores

A bar chart compares the average scores of students based on their lunch type.

### 7. Math Score vs Reading Score

A scatter plot is used to study the relationship between Math and Reading scores.

### 8. Correlation Between Subjects

A correlation visualization is created using Matplotlib to understand the relationship between Math, Reading, and Writing scores.

## Libraries Used

```python
import pandas as pd
import matplotlib.pyplot as plt
```

## Key Insights

* Students' Reading and Writing scores show a strong positive relationship.
* Math scores are also positively related to Reading and Writing scores.
* Students who completed the test preparation course generally have better average scores.
* There are differences in average scores between male and female students.
* Parental education level shows differences in students' average performance.
* Students with standard lunch generally have higher average scores than students with free/reduced lunch.

## Conclusion

This project uses **Exploratory Data Analysis** to understand student performance and identify important patterns in the dataset. Using **Pandas and Matplotlib**, the data is analyzed through statistical information and different visualizations. The analysis helps in understanding the relationship between student characteristics and their academic performance.
