# Pymaceuticals Cancer Treatment Study Analysis

## Background

I recently "joined" Pymaceuticals, Inc., a fictional pharmaceutical company specializing in anti-cancer medications. The company conducted an animal study to screen potential treatments for squamous cell carcinoma (SCC), a common form of skin cancer. In this study, 249 mice with SCC tumors received various drug regimens, including Pymaceuticals' drug of interest, Capomulin. The study spanned 45 days to observe and measure tumor development, comparing Capomulin's performance against other treatments.

This assignment comprised several tasks:

1. **Prepare the Data**: Merged the mouse_metadata and study_results DataFrames, checked for duplicates, and cleaned the data.
2. **Generate Summary Statistics**: Created summary statistics for tumor volume across different drug regimens.
3. **Create Bar Charts and Pie Charts**: Visualized the total number of mice for each drug regimen and the distribution of male vs. female mice.
4. **Calculate Quartiles, Find Outliers, and Create a Box Plot**: Identified potential outliers in the final tumor volume for selected treatment regimens.
5. **Create a Line Plot and a Scatter Plot**: Plotted tumor volume versus time point for a single mouse treated with Capomulin, and mouse weight versus average tumor volume for the entire Capomulin regimen.
6. **Calculate Correlation and Regression**: Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin regimen.

## Data Analysis Steps

### Prepare the Data

- Merged mouse_metadata and study_results DataFrames.
- Checked for duplicates and removed any.
- Displayed the number of unique mice IDs before and after cleaning.

### Generate Summary Statistics

- Created a DataFrame with summary statistics for tumor volume across drug regimens.
- Calculated mean, median, variance, standard deviation, and SEM for tumor volume.

### Create Bar Charts and Pie Charts

- Generated bar charts showing the total number of mice for each drug regimen.
- Generated pie charts showing the distribution of female vs. male mice.

### Calculate Quartiles, Find Outliers, and Create a Box Plot

- Calculated the final tumor volume for selected treatment regimens.
- Determined potential outliers using quartiles and IQR.
- Generated a box plot highlighting any outliers.

### Create a Line Plot and a Scatter Plot

- Plotted tumor volume versus time point for a mouse treated with Capomulin.
- Plotted mouse weight versus average tumor volume for the Capomulin regimen.

### Calculate Correlation and Regression

- Calculated the correlation coefficient between mouse weight and average tumor volume.
- Performed linear regression and plotted the regression line on the scatter plot.

## Code Citations

Return index of series where value is True:
(Found in input cell 3 of pymaceuticals_RV.ipynb file)

https://www.skytowner.com/explore/getting_index_of_series_where_value_is_true

Color outliers in a boxplot with matplotlib:
(Found in input cell 15 of pymaceuticals_RV.ipynb file)

https://stackoverflow.com/questions/43342564/flier-colors-in-boxplot-with-matplotlib
