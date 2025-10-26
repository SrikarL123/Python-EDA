
# Student Habits and Exam Performance Analysis

## Project Overview

This project involves an Exploratory Data Analysis (EDA) of a dataset containing information on student habits, background, and their final exam scores. The goal is to clean the data, explore the distributions of different variables, and uncover potential relationships between factors like study hours, social media usage, and academic performance.

This analysis is conducted in the `shp.ipynb` Jupyter Notebook.

-----

## Dataset

The dataset used is `student_habits_performance.csv`. It contains 1000 entries and 16 columns.

### Key Features:

  * **`student_id`**: A unique identifier for each student.
  * **Demographics**: `age`, `gender`, `parental_education_level`
  * **Student Habits**: `study_hours_per_day`, `social_media_hours`, `netflix_hours`, `sleep_hours`, `exercise_frequency`, `diet_quality`
  * **Student Status**: `part_time_job`, `attendance_percentage`, `extracurricular_participation`
  * **Other Factors**: `internet_quality`, `mental_health_rating`
  * **Target Variable**: `exam_score` (the final exam score for each student)

-----

## Analysis & Cleaning Steps

1.  **Data Loading:** The dataset is loaded into a pandas DataFrame.
2.  **Initial Inspection:** `df.head()`, `df.info()`,'df.dtypes' and `df.describe()` are used to get an overview of the data structure, data types, and summary statistics.
3.  **Data Cleaning:**
      * **Handling Missing Values:** The `parental_education_level` column contains 91 entries with the string `'None'`, which is treated as a valid category and is not modified.
      * **Duplicate Check:** The dataset is checked for duplicate rows (none were found).
      * **Irrelevant Columns:** The `student_id` column is dropped as it is not a predictive feature.
4.  **Exploratory Data Analysis (EDA):**
      * **Univariate Analysis:**
          * Histograms are plotted for all numerical variables (`age`, `study_hours_per_day`, `exam_score`, etc.) to understand their distributions.
      * **Bivariate Analysis:**
          * A **correlation heatmap** is created to show the linear relationships between all numerical variables.
          * **Scatter plots** are used to visualize the relationship between `exam_score` and key numerical features (e.g., `study_hours_per_day`, `attendance_percentage`).

-----
