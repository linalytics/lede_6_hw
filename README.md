# Homework 6: Data Analysis with Pandas

## Overview

This assignment consists of two Jupyter notebooks designed to build practical data analysis skills using **pandas**. The exercises focus on loading datasets, exploring data, filtering records, calculating statistics, creating new columns, grouping data, and producing visualizations.

The goal is to become comfortable performing common exploratory data analysis (EDA) tasks that form the foundation of data journalism and data science workflows.

---

## Part 1: Animals Dataset (`01-Animals.ipynb`)

### Dataset

The notebook uses **animals.csv**, a small dataset containing information about different animals.

### Tasks

1. Import pandas.
2. Read the animal dataset into a dataframe.
3. Examine dataset dimensions and column types.
4. Display the first three animals.
5. Find the three longest animals.
6. Calculate the mean and standard deviation of animal lengths.
7. Count the number of cats and dogs.
8. Display only dogs.
9. Display animals longer than 40 cm.
10. Create a new column converting length from centimeters to inches.
11. Create separate dataframes for cats and dogs.
12. Find cats longer than 12 inches.
13. Calculate average lengths for cats and dogs.
14. Use `groupby` to summarize average length by animal type.
15. Create a histogram of dog lengths.
16. Create a horizontal bar chart of animal lengths.
17. Create a sorted horizontal bar chart of cat lengths.
18. Compare the number of cats and dogs with a visualization.

---

## Part 2: Billionaires Dataset (`02-Billionaires.ipynb`)

### Dataset

The notebook uses **richpeople.xlsx** and **billionaires.json**, containing information about billionaires such as.

### Tasks

1. Import pandas.
2. Load the billionaire dataset from Excel.
3. Inspect dataset shape, columns, and data types.
4. Identify the ten richest billionaires.
5. Compare counts of male and female billionaires.
6. Calculate gender percentages.
7. Compare average wealth by gender.
8. Determine the most common source of wealth.
9. Compare wealth sources between men and women.
10. Find companies with the most billionaires.
11. Visualize the top companies with a horizontal bar chart.
12. Calculate the combined wealth of billionaires from the top companies.
13. Determine which countries hold the most billionaire wealth.
14. Calculate the average age of billionaires.
15. Compare ages of self-made and non-self-made billionaires.
16. Identify the youngest and oldest billionaires.
17. Plot the distribution of billionaire ages.
18. Create a scatterplot of age versus net worth.
19. Visualize the wealth of the ten richest billionaires.
20. Load and inspect updated billionaire data from a JSON file.

---

## Skills Practiced

Throughout both notebooks, students gain experience with:

- `pd.read_csv()`
- `pd.read_excel()`
- `pd.read_json()`
- DataFrame inspection (`head`, `shape`, `dtypes`)
- Sorting and ranking
- Filtering and querying
- Creating new columns
- Summary statistics
- Value counting
- Grouping and aggregation
- Histograms
- Bar charts
- Scatterplots
- Exploratory data analysis workflows

---

## Expected Outcome

After completing the assignment, students should be able to:

- Load and inspect datasets from multiple file formats
- Perform common data cleaning and exploration tasks
- Generate descriptive statistics
- Answer analytical questions using pandas
- Create basic visualizations to communicate findings
- Apply data analysis techniques to real-world datasets

---

## Technologies Used

- Python
- Pandas
- Jupyter Notebook
- Matplotlib

---

## Repository Structure

```text
.
├── 01-Animals.ipynb
├── 02-Billionaires.ipynb
└── README.md
```