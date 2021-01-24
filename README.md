# Matplotlib-Challenge
The Power of Plots

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. 
In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. 
Over the course of 45 days, tumor development was observed and measured. 
The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 
You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. 
The executive team also has asked for a top-level summary of the study results.

Observation:
1. By removing duplicates the total number of mice tested is 248. The total count of mice by gender also showed that 51% of tested population is Male and 49% is female mice.
2. The bar graph showed the Drug Regimen Capomulin has the maximum mice number and Zoniferol has the smaller mice number.
3. The correlation between mouse weight, and average tumor volume is 0.84. It is a strong positive correlation, when the mouse weight increases the average tumor volume also increases.
4. From the selected treatments Capomulin reduces the size of tumors better.

#Instructions:


Before beginning the analysis, check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.

Use the cleaned data for the remaining steps.

Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

Generate a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the total number of measurements taken for each treatment regimen throughout the course of the study.

Generate a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.

Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.