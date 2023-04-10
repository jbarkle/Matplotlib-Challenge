# Matplotlib-Challenge
## Pymaceuticals, Inc., Data Analysis

### Created a Jupyter Notebooks script to analyze a clinical study performed on mice identified with a particular type of tumor that received treatment with a range of drug regimens. Analysis included the following:

- Preparing the data

    - Merging multiple data imports into a single DataFrame
    - Check for mouse IDs with duplicate time points, remove duplicate data, and create cleaned DataFrame
    - Display updated number of unique mouse IDs

- Generate Summary Statistics

    - Include a row for each drug regimen contained in the index column
    - Include columns for each of the following statistics: mean, median, variance, standard deviation, and SEM of the tumor volume

- Bar Charts and Pie Charts (one created using Pandas method, one created using pyplot method)

    - A bar chart showing the total number of time points for all mice tested for each drug regimen
    - A pie chart showing the distributions of female versus male mice in the study

- Quartiles, Outliers, and Box Plot

    - Calculated the final tumor volume of each mouse across four of the most promising drug regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Then, canculated the quartiles and IQR, and determined if there are potential outliers across all four treatments
    - Generated a box plot that shows the distribution of final tumor volume for all mice in each treatment group; highlighted any potential outliers

- Line Plot and Scatter Plot

    - Selected a mouse that was treated with Capomulin and generated a line plot of the tumor volume versus the time point for that mouse
    - Generated a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen

- Correlation and Regression

    - Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment
    - Plotted the linear regression model on top of the previous scatter plot

Additionally, a written analysis was included that draws a few conclusions about the calculations, albeit may be a little subjective about the dataset.
