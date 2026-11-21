# Wine Dataset – Exploratory Data Analysis (EDA)

## Project Overview

This project performs **basic Exploratory Data Analysis (EDA)** on the UCI Wine dataset. It explores chemical measurements of wines belonging to three different classes using Python, NumPy, Pandas, and Matplotlib.

The dataset contains **178 rows (wine records)** and represents three wine classes.

**Dataset source:** [UCI Machine Learning Repository – Wine Dataset](https://archive.ics.uci.edu/dataset/109/wine)

## Project Objectives

The aim is to understand the dataset, summarize important chemical measurements, compare the three wine classes, identify data-quality issues, and visualize selected results.

## Questions to Explore

1. How many wines belong to each class?
2. What are the mean, median, minimum, and maximum alcohol values?
3. Which class has the highest average alcohol and magnesium values?
4. Which records have the highest color intensity?
5. Are there any missing values or duplicate records?
6. How do the average alcohol, malic acid, and color intensity values compare across the three classes?

## Tools and Libraries

- **Python** – Main programming language.
- **NumPy** – Numerical calculations and statistical analysis.
- **Pandas** – Data loading, inspection, filtering, sorting, and grouping.
- **Matplotlib** – Data visualization.

Install the required libraries using:

```bash
pip install -r requirements.txt
```

## Dataset Information

- **Dataset name:** Wine
- **Source:** UCI Machine Learning Repository
- **Number of records:** 178
- **Number of classes:** 3
- **Data type:** Chemical measurements of wine samples

The dataset includes features such as alcohol, malic acid, magnesium, and color intensity, along with a class label.

## Project Tasks

### 1. Load and Inspect the Dataset

Load the Wine dataset and display:

- `head()` – First five rows.
- `tail()` – Last five rows.
- `shape` – Number of rows and columns.
- `info()` – Column names, data types, and non-null counts.
- `describe()` – Descriptive statistical summary.

### 2. Class Distribution

Use Pandas `value_counts()` to count the number of wines in each class.

### 3. Alcohol Statistics

Use NumPy to calculate the following alcohol statistics:

- Mean
- Median
- Minimum
- Maximum

### 4. Class-wise Comparison

Use Pandas `groupby()` to calculate average alcohol and magnesium values for each class. Identify the class with the highest average for each measurement.

### 5. Highest Color Intensity

Use Pandas sorting and filtering to identify the record or records with the highest color intensity.

### 6. Data Quality Check

Check the dataset for:

- Missing values using `isnull().sum()`.
- Duplicate records using `duplicated().sum()`.

### 7. Compare Chemical Measurements

Group the data by class and compare the average values of:

- Alcohol
- Malic acid
- Color intensity

### 8. Data Visualization

Create the following two simple charts using Matplotlib:

1. **Class-count bar chart** – Shows the number of wines in each class.
2. **Alcohol histogram** – Shows the distribution of alcohol values.

## Common Requirements Checklist

- [ ] Use Python, NumPy, and Pandas.
- [ ] Load the Wine dataset.
- [ ] Display `head()`, `tail()`, `shape`, `info()`, and `describe()`.
- [ ] Check missing values and duplicate records.
- [ ] Use at least one NumPy array for calculations.
- [ ] Use Pandas `value_counts()`, `groupby()`, filtering, and sorting where relevant.
- [ ] Create a class-count bar chart.
- [ ] Create an alcohol histogram.
- [ ] Write three observations based on the analysis.

## Three Observations

After completing the analysis, write three observations supported by the results. For example:

1. State which wine class has the highest number of records.
2. Describe the alcohol distribution using the calculated statistics and histogram.
3. Identify differences between the classes in average alcohol, malic acid, or color intensity.

**Note:** Fill in the actual findings after running the analysis. Do not assume the observations before checking the dataset.

## Project Scope

This project covers **basic EDA only**. It does not include machine learning, model training, prediction, or classification.

## How to Run the Project

1. Clone or download the project.
2. Open the project folder in VS Code or another Python editor.
3. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Python analysis file:

   ```bash
   python main.py
   ```

   Replace `main.py` with the actual Python filename if it is different.

5. Review the printed analysis, charts, and three observations.

## Conclusion

This project uses basic Python data-analysis tools to explore the UCI Wine dataset, understand the distribution of wine classes, summarize chemical measurements, compare class-wise averages, check data quality, and present findings through simple visualizations.
