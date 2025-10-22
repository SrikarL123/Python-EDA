# 📊 Facebook User Data - Exploratory Data Analysis (EDA)

This project explores user behavior patterns in a **Facebook user dataset (`pseudo_facebook.csv`)** through data cleaning and visualization.  
It focuses on understanding how user demographics and activity levels (like gender, age, tenure, and friend count) influence engagement on the platform.

---

## 🧠 Project Overview
The dataset contains information about Facebook users such as:
- **Age**
- **Gender**
- **Friend Count**
- **Tenure (days since joining Facebook)**
- **Likes and engagement metrics**

The goal of this project is to:
- Clean and preprocess the dataset  
- Handle missing and inconsistent values  
- Perform exploratory data analysis (EDA)  
- Visualize relationships between key variables

---

## 🧹 Data Cleaning Steps
1. **Handled Missing Values**
   - Filled missing `gender` values with `"Unknown"`.
   - Filled missing `tenure` values with the median.
2. **Converted Data Types**
   - Ensured all numeric columns (like `tenure`) were properly numeric.
3. **Removed Inconsistencies**
   - Cleaned unwanted strings such as `"Unknown"` from numeric columns.

---

## 📈 Exploratory Data Analysis
The following visualizations were created to understand user patterns:

1. **Distribution of Gender** – to see the gender ratio in the dataset  
2. **Distribution of Tenure** – to explore how long users have been on Facebook  
3. **Friend Count by Gender** – to compare friend counts across genders  
4. **Likes vs Age** – to examine how engagement changes with user age  
5. **Correlation Between Numerical Columns** – to identify relationships between features such as `age`, `friend_count`, `likes`, and `tenure`

Each visualization was created using **Matplotlib** and **Seaborn** for clear, attractive plots.

---

## 📊 Key Libraries Used
- **pandas** → Data manipulation  
- **numpy** → Numerical calculations  
- **matplotlib** → Plotting  
- **seaborn** → Statistical visualization  

---

## 💾 Output
After cleaning, the dataset was saved as:

