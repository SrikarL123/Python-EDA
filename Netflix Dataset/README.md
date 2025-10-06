
# 🧠 Netflix Data EDA in Google Colab

This project demonstrates a **step-by-step Exploratory Data Analysis (EDA)** on the **Netflix dataset** using Python in **Google Colab**.
The main goal is to clean, explore, and visualize Netflix data to understand trends in content type, genres, release years, and IMDb ratings.

---

## 📁 1. Uploading the Dataset

The dataset (`netflix data.csv`) was uploaded directly to **Google Colab** using the built-in file upload feature.
After uploading, the file was read into a **Pandas DataFrame** for analysis.
The first few rows were displayed to confirm successful loading and to get an initial look at the structure of the dataset.

---

## 📊 2. Basic Dataset Information

Basic functions such as `df.info()`, `df.shape`, and `df.describe()` were used to understand the data types, number of rows and columns, and summary statistics of numerical columns.
This step provided insights into which columns are categorical or numerical and whether there might be missing or inconsistent values.

---

## 🧩 3. Checking Missing Values

To identify incomplete records, missing values were checked column by column.
A heatmap visualization was also created to show where missing data exists within the dataset.
This helped in visually identifying patterns — for example, if certain columns had many missing entries, which might affect later analysis.

---

## 🧹 4. Handling Missing or Duplicate Data

Duplicate rows were identified and removed to ensure the dataset contained only unique records.
Missing values were handled based on context — for example, dropping rows with missing titles or filling missing ratings with a default value like `"Unknown"`.
This cleaning step ensured that the analysis would be reliable and consistent.

---

## 🎭 5. Exploring Categorical Columns

Two categorical columns were explored in detail:

* **`type`** – showed the number of Movies vs TV Shows available on Netflix.
* **`age_certification`** – revealed the distribution of content ratings (like PG, R, 13+, etc.).

This step gave an idea of the kind of content Netflix primarily offers and how it’s classified by age suitability.

---

## 📈 6. Data Visualization

After cleaning and understanding the dataset, visualizations were used to discover trends and patterns.
The following four visualizations were created using **Seaborn** and **Matplotlib**:

### 🔹 1. Distribution of Content Type

A bar chart compared the number of **Movies** and **TV Shows** on Netflix.
This simple count visualization helped identify which category dominates the platform.

### 🔹 2. Trend Over Years

A count plot showed the number of titles released per year.
By observing the most frequent release years, we could see when Netflix had the highest content growth.

### 🔹 3. Top 10 Genres

A bar chart highlighted the **top 10 most common genres** in the dataset.
This visualization revealed which types of content Netflix produces or streams the most.

### 🔹 4. Distribution of IMDb Ratings

A histogram displayed how IMDb ratings are distributed across Netflix content.
This helped in understanding the quality perception of titles available on the platform — for instance, whether most content has average or high ratings.

---

## 💾 7. Saving the Cleaned Data

After cleaning and transforming the data, the final DataFrame was saved as a new CSV file (`netflix_cleaned.csv`).
The cleaned file was then downloaded from Colab for future use, such as machine learning or deeper analysis.

---

## 🧰 Tools Used

* **Python 3**
* **Google Colab**
* **Pandas** – for data loading, cleaning, and manipulation
* **Seaborn** & **Matplotlib** – for data visualization

---

You can down the datasets from the "Netflix Dataset folder"-
"netflix_data_before.csv" is the dataset before cleaning
"netflix_data_cleaned.csv" is the dataset after cleaning

To view the datasets-
"netflix_data_before.png" - the image of the dataset before cleaning
"netflix_data_cleaned.png" - the image of the dataset after cleaning

