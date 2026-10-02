# Iris Dataset – Exploratory Data Analysis (EDA)

**Task 2 – Exploratory Data Analysis**
Veda Technology | Data Analytics Track

## About
In this project I explored the Iris dataset (150 flowers, 3 species) to find patterns, relationships and outliers before drawing any conclusions. Every chart answers one question and has a written observation in the notebook.

## What I did
- Checked the shape, missing values and duplicates
- Calculated summary statistics (`describe()` and averages per species)
- Made 6 visualizations:
  1. Count plot of species
  2. Histograms of all 4 measurements
  3. Box plots to find outliers
  4. Correlation heatmap
  5. Scatter plot of petal length vs petal width
  6. Box plot of petal length by species
- Wrote a "Top 3 insights" section

## Top 3 insights
1. Petal measurements separate the species best. Setosa petals (1.0 to 1.9 cm) never overlap with the other two species.
2. Petal length and petal width are almost the same information (correlation 0.96).
3. Sepal width is the weakest feature. It is the only one with outliers (4 points) and it has a weak negative correlation with the others.

## Files
- `Task2_EDA_Iris.ipynb` – notebook with code, charts and observations

## Tools used
Python, Pandas, Matplotlib, Seaborn, Google Colab

## How to run
1. Open the notebook in Google Colab
2. Tap Runtime / Run all (the dataset loads from scikit-learn, no download needed)

## Author
Rabia
