# Overview
This repository contains data from a laboratory rat study examining treatments for malignant tumors. There are multiple rats of multiple genders examined as varying drug regimens are administered for varying time periods. The python notebook contains functionality for the .csv data to present visuals for which conclusions can be drawn regarding the level of success in reducing tumor volume for each drug regimen.

## Functionality

* Check the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.

* Use the cleaned data for the remaining steps.

* Generate a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generate a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows  the number of total mice for each treatment regimen throughout the course of the study.

![](images/Capture.png)

* Generate a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

![](images/Capture1.png)

* Calculate the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

* Using Matplotlib, generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

![](images/Capture2.png)

* Select a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

![](images/Capture3.png)

* Generate a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

![](images/Capture4.png)

* Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

* Look across all previously generated figures and tables and write at least three observations or inferences that can be made from the data. Include these observations at the top of notebook.
