### Data_Visualization_Challenge
#Generate Summary Statistics
Summary Statistics contains
* A row for each drug regimen. These regimen names should be contained in the index column.
* A column for each of the following statistics: mean, median, variance, standard deviation, and SEM of the tumour volume.

#Create Bar Charts and Pie Charts
Created Bar Charts and Pie charts based on Matplotlib and Pandas
Both bar charts are identical and shows the total number of time points for all mice tested for each drug regimen throughout the study.
* Created the first bar chart with the Pandas DataFrame.plot() method.
* Created the second bar chart with Matplotlib's pyplot methods.

Both pie charts are identical and show the distribution of female versus male mice in the study.
* Create the first pie chart with the Pandas DataFrame.plot() method.
* Create the second pie chart with Matplotlib's pyplot methods.

#Calculate Quartiles, Find Outliers, and Create a Box Plot
* Calculated the final tumour volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Then, calculate the quartiles and IQR, and determine if there are any potential outliers across all four treatment regimens using for loop.
* Using Matplotlib, generated a box plot that shows the distribution of the final tumour volume for all the mice in each of the 4 treatment group. Highlighted any potential outliers in the plot by changing their color to green.

#Create a Line Plot and a Scatter Plot
* Selected a mouse that was treated with Capomulin, and generateed a line plot of tumour volume versus time point for that mouse.
* Generated a scatter plot of tumour volume versus mouse weight for the Capomulin treatment regimen.

#Calculate Correlation and Regression
* Calculate the correlation coefficient and linear regression model between mouse weight and average tumour volume for the Capomulin treatment.
* Plot the linear regression model on top of the previous scatter plot.
