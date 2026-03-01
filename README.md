# Salary_survey_academic_project
This repository contains the final analysis of a data project developed as part of an academic course. The project aims to perform an exploratory data analysis (EDA), clean and prepare the data, select relevant features, and handle duplicates using a specific dataset.

The analysis is documented in a single Jupyter Notebook, which describes the complete process, from data exploration to the steps of cleaning and feature selection.

#### Files in the Repository

csv file, notebook.ipynb: Jupyter Notebook containing the final analysis, with all steps of Exploratory Data Analysis (EDA), Data Cleaning, Feature Selection, and Duplicate Handling.

requirements.txt: File containing the list of dependencies needed to run the Jupyter Notebook.

### Justifications for the Choices
1. Exploratory Data Analysis (EDA)

The data exploration was crucial to identify patterns, distributions, and relationships between the variables. Visualizations such as scatter plots, histograms, and correlation heatmaps were used to investigate interactions between the variables and gather initial insights. This process helped identify highly correlated variables, which influenced the selection of features for further analysis.

2. Data Cleaning

Data cleaning was performed to address missing values, outliers, and inconsistencies. Missing data were handled using techniques such as mean imputation or removal, depending on the situation. Data normalization was applied to ensure that variables were on a consistent scale, and outliers were treated to avoid distorting the results.

3. Feature Selection

To reduce dimensionality and improve model performance (if applicable), the most relevant features were selected based on statistical methods and machine learning techniques. Correlation analysis and feature importance helped discard redundant or irrelevant attributes for the analysis.

4. Duplicate Handling

Removing duplicates was necessary to ensure data integrity. Duplicate records were identified based on unique identifiers and removed, ensuring the analysis was not distorted by repeated entries.

### Visualizations in the Project

###### Chart 1: Scatter plot showing the relationship between two key variables in the dataset.

###### Chart 2: Histogram visualizing the distribution of a specific variable.

###### Chart 3: Correlation heatmap used to observe relationships between variables.

These visualizations were generated during Exploratory Data Analysis (EDA) and are used to support the decisions made in the following steps.
