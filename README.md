# matplotlib_challenge

## Project Overview: 

The Matplotlib project for the University of Toronto Data Analytics Bootcamp program. This project involves a comprehensive analysis of a real-world dataset from Pymaceuticals, Inc., a pharmaceutical company specializing in anti-cancer medications. The dataset encompasses the results of an animal study where 249 mice, identified with squamous cell carcinoma (SCC) tumors, underwent various drug regimens. This 45-day study aimed to observe and measure tumor development.

As a senior data analyst, the task is to conduct an in-depth analysis of the data and generate requisite tables and figures for the technical report of the clinical study. The primary objective is to compare the performance of Pymaceuticals' drug of interest, Capomulin, against other treatment regimens.

## Instructions:

The assignment is structured into distinct tasks, including data preparation, summary statistics generation, and the creation of various visualizations (bar charts, pie charts, box plots, line plots, and scatter plots). The tasks evaluate proficiency in utilizing Matplotlib for comprehensive data analysis.


## Project Structure: 

data: Contains the two CSV files, mouse_metadata.csv and study_results.csv.
pymaceuticals_Analysis.ipynb: The Jupyter Notebook where the analysis is performed. The figures generated during the analysis will be shown directly in this notebook.
README.md: A markdown file explaining the project, instructions, and any other relevant information, directly located in the main directory.
This structure should provide a clear and straightforward view when someone navigates to the matplotlib_challenge directory.

## Conclusion:

In undertaking this comprehensive analysis of Pymaceuticals' animal study, which involved 249 mice subjected to diverse drug regimens, profound insights have been gleaned to elucidate the effectiveness of anti-cancer medications, with a particular focus on Capomulin. The 45-day study, meticulously measuring tumor development, aimed to provide a holistic understanding of treatment outcomes.

## Data Preparation:

The initial step involved merging the mouse_metadata and study_results DataFrames, resulting in a consolidated dataset of 248 unique mice after addressing duplicate entries. This meticulous data cleaning laid the foundation for robust analyses.

## Summary Statistics: 

Calculated summary statistics, including mean, median, variance, standard deviation, and SEM of tumor volume for each drug regimen, revealed compelling insights. Notably, Capomulin and Ramicane exhibited lower mean tumor volumes, signifying potential efficacy compared to other regimens.

## Data Distribution:

Visual representations, such as bar charts displaying timepoints and pie charts illustrating the gender distribution among mice, provided a comprehensive view of the dataset. Capomulin and Ramicane emerged as standout regimens with the highest timepoint observations.

Treatment Regimens

Analyzing the final tumor volume for mice under specific treatment regimens (Capomulin, Ramicane, Infubinol, and Ceftamin) showcased the potential efficacy of Capomulin and Ramicane, reflected in lower median tumor volumes compared to Infubinol and Ceftamin.

Mouse Weight vs. Tumor Volume

The positive correlation between mouse weight and average tumor volume in the Capomulin regimen was evident, suggesting a potential influence of weight on treatment outcomes. This correlation, with a coefficient of 0.84, underscores the importance of considering weight factors in assessing treatment efficacy.

Outliers and Box Plot

Identification of potential outliers and the creation of a box plot further reinforced the efficacy of Capomulin and Ramicane, with a visibly lower distribution of tumor volumes and minimal outliers compared to other regimens.

Line Plot and Scatter Plot

Individual mouse analysis using line plots showcased the dynamic evolution of tumor volume over time under Capomulin treatment. Additionally, the scatter plot correlating mouse weight and average tumor volume accentuated the positive correlation observed earlier.

Correlation and Regression

The strong positive correlation coefficient of 0.84 and the linear regression model between mouse weight and average tumor volume for the Capomulin regimen provided quantitative support to the visual correlations observed in the scatter plot.

For the pie chart, the code used is from Matplotlib Pie Chart Features: https://matplotlib.org/stable/gallery/pie_and_polar_charts/pie_features.html

For the box plot, the code used is from Matplotlib Box Plot vs. Violin Plot: https://matplotlib.org/stable/gallery/statistics/boxplot_vs_violin.html

For reference on figure customization, Matplotlib Figure : https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.figure.html

References:

Data generated by Mockaroo, LLC (2022). Realistic Data Generator: Mockaroo https://mockaroo.com/
