# Matplotlib-challange-pymaceutical
#Pymaceutical challange
##Pharmaceutical Data Analysis 


Overview
This data analysis project is focused on analyzing data from pharmaceutical company , using Python Matplotlib to visualize data and compare different drugs and make decisions regarding particular drug(Capomilin). 

Background

###A new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.
As a data analyst at the company, I've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals drug of interest, Capomulin, against the other treatment regimens.
Our main aim in this project is generating all of the tables and figures needed for the technical report of the clinical study. They have also asked us for a top-level summary of the study results.

They provided datasets,first data set , Mouse_metadata.csv wich includes mice data .The variables are Mouse ID, Sex, Age_months and Weight (g) . The other dataset is Study_results.csv contains study data and columnsincluded are  Mouse ID,Timepoint,Tumor Volume (mm3), and Metastatic Sites.To analyse, both the datasets are imported, merged,cleaned and  aggregated data  in to Python Pandas dataframes, visualized in Matplotlib, and other libraries used in order to make a stastical analysis.

A new pharmaceutical company specializing in anti-cancer medications initiated a screening for potential treatments for squamous cell carcinoma (SCC). As a data analyst in the company, I have access to complete data from their recent animal study, involving 249 mice with SCC tumors. The study aimed to compare the performance of Pymaceuticals' drug of interest, Capomulin, against other treatment regimens.

### Observable Trends

The analysis has generated various DataFrames that showcase the distribution of mice across drug regimens, gender, and the relationship between mouse weight and tumor volume. The effectiveness of specific treatments is highlighted, with notable findings:

1. **Drug Regimen Analysis:**
   - The distribution of mice across different drug regimens is visually represented, with Capomulin having the highest number of mice (230) and Propriva the lowest (156). After removing duplicates, the total number of unique mice in the dataset is 248.

2. **Gender Distribution:**
   - The dataset exhibits a balanced gender distribution, with 51% male mice and 49% female mice.

3. **Correlation Analysis:**
   - A strong positive correlation (correlation coefficient of 0.84) is observed between mouse weight and average tumor volume. As mouse weight increases, there is a corresponding increase in average tumor volume.

4. **Regression Analysis:**
   - The regression analysis provides insights into predicting changes in average tumor volume based on mouse weight. The R-squared value of 0.70 suggests a reasonably good fit, indicating that 70% of the model explains the variation in the response variable around its mean.

5. **Treatment Effectiveness:**
   - Among the selected treatments, Capomulin and Ramicane emerge as more effective in reducing tumor sizes compared to others.


##Project Structure

pymaceuticals folder containd csv files about mice study .This directory contains the raw data files used in the analysis.
pymaceuticals_starter.ipynb: script about
README.md: The file you are currently reading, providing an overview of the project.

##Table of Contents
### Table of Contents include Tasks
1. Preparing the Data
2. Generate Summary Statistics
3. Created Bar Charts and Pie Charts
4. Calculate Quartiles, Find Outliers, and Create a Boxplot
5. A Line Plot and a Scatter Plot
6. Calculated Correlation and Regression
7. Results


##Prerequisites
 To produce this analysis, we will need the following tools and libraries:

 Python
 Pandas
 NumPy
 Jupyter Notebook
 Matplotlib


The project involves several tasks:

## Project Tasks Summary

### 1. Data Preparation
- In this step, we run the provided package dependency and import data. Then, we merge the `mouse_metadata` and `study_results` DataFrames into a single DataFrame. Display the number of unique mouse IDs in the data and check for any mouse ID with duplicate time points. Display the data associated with that mouse ID and create a new DataFrame where this data is stored. Use this cleaned DataFrame for the remaining steps, and print the updated number of unique mouse IDs, which is 249.

### 2.Summary Statistics
-We Created a DataFrame of summary statistics called drug_stat_data_df. The summary statistics should include a row for each drug regimen. These regimen names are contained in the index column. In this step, find out the mean, median, variance, standard deviation, and SEM of the tumor volume.

### 3.  Bar Charts and Pie Charts
- Create the first bar chart with the Pandas DataFrame.plot() method.
- Create the second bar chart with Matplotlib's pyplot method.

### 4.  Quartiles, Outliers, and Created a Boxplot

### 5. Created a Line Plot and a Scatter Plot

### 6. Correlation and Regression
- perform correlation and  regression analysis using Matplotlib in Jupyter Notebook. The result is that the regression analysis helps predict the change in average tumor volume based on mouse weight. The R-squared value of 0.70 suggests that 70% of the model fits the data, indicating a reasonably good fit. Higher R-squared values indicate a better fit of the model to the data.


Results
The analysis results in various DataFrames , showcasing the distribution of mice across drug regimens, gender, and the relationship between mouse weight and tumor volume. The effectiveness of specific treatments is also highlighted.Among the selected treatments, Capomulin and Ramicane stand out as more effective in reducing tumor sizes.


About
-These projects were completed as part of Data Analysis Bootcamp.

Contact
If there are any questions or concerns, I can be reached at:

github: svuth23
[email: swapna.vuthpala@gmail.com]
