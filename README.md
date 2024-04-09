# Comparative-Analysis-of-Anti-Cancer-Drug-Efficacy-in-Squamous-Cell-Carcinoma-Treatment
A Pymaceuticals, Inc. Study

# Background #
Pymaceuticals, Inc. is an emerging pharmaceutical company specializing in anti-cancer medication. The company has recently initiated a screening process for potential treatments for squamous cell carcinoma (SCC), a common form of skin cancer. As part of this initiative, a study was conducted on 249 mice, each identified with SCC tumors, to observe the effects of various drug regimens over a period of 45 days. The focus of this study was to evaluate the effectiveness of Pymaceuticals’ leading drug, Capomulin, against other treatment regimens.

# Objective #
As a senior data analyst, the task is to analyze the data from the recent animal study and generate all necessary tables and figures for the clinical study's technical report. Additionally, a top-level summary of the study results is required by the executive team.

# Instructions #
- Prepare the Data: Merge the mouse_metadata and study_results DataFrames. Clean the data to remove duplicates and prepare it for analysis.
- Generate Summary Statistics: Create a summary statistics table of tumor volume for each drug regimen.
- Create Visualizations: Generate bar and pie charts to illustrate the study data.
- Quartiles, Outliers, and Box Plots: Identify potential outliers in the tumor volumes for the top treatment regimens.
- Line and Scatter Plots: Visualize the tumor volume over time for a selected mouse and analyze the relationship between mouse weight and average tumor volume.
- Correlation and Regression: Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment.

# Data Preparation #
- Import dependencies and data.
- Merge data into a single DataFrame.
- Clean the data to ensure accuracy.

# Summary Statistics #
- Generate a DataFrame with the following statistics for each drug regimen:
- Mean, Median, Variance, Standard Deviation, and SEM of tumor volume.

# Visualizations #
- Bar Charts: Display the total number of measurements for each drug regimen.
- Pie Charts: Show the distribution of female versus male mice in the study.

# Quartiles, Outliers, and Box Plots #
- Calculate the final tumor volume for each mouse across the top treatment regimens.
- Determine quartiles, IQR, and identify any outliers.
- Generate a box plot displaying the distribution of final tumor volumes.

# Line and Scatter Plots #
- Select a mouse treated with Capomulin and plot tumor volume vs. time point.
- Generate a scatter plot of mouse weight vs. average tumor volume for the Capomulin regimen.

# Correlation and Regression #
Calculate and plot the correlation coefficient and linear regression model for mouse weight and average tumor volume for the Capomulin treatment.
