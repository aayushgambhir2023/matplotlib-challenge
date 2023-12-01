# matplotlib-challenge
 I started by running the necessary package dependencies and importing the required data. Afterward, I merged the "mouse_metadata" and "study_results" DataFrames into a consolidated DataFrame. To ensure data quality, I displayed the count of unique mouse IDs and identified any instances of duplicated time points associated with mouse IDs. For those cases, I showcased the relevant data and created a new DataFrame excluding the duplicate entries. This refined DataFrame was utilized for subsequent analyses.

Next, I generated a summary statistics DataFrame, focusing on drug regimens and key tumor volume metrics like mean, median, variance, standard deviation, and SEM. The chosen method for calculation mattered less than obtaining accurate results.

Following that, I created identical bar charts displaying the total number of rows for each drug regimen using both the Pandas DataFrame.plot() method and Matplotlib's pyplot methods. Similarly, I constructed two pie charts depicting the distribution of female versus male mice in the study, utilizing both Pandas and Matplotlib.

Moving on, I calculated the final tumor volume for mice treated with four promising regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Subsequently, I determined potential outliers, if any, by computing quartiles and IQR. A box plot was then generated using Matplotlib, highlighting potential outliers with distinct colors and styles.

For a more individualized perspective, I selected a single mouse treated with Capomulin and created a line plot illustrating the mouse's tumor volume over time. Additionally, I generated a scatter plot correlating mouse weight with the average observed tumor volume for the entire Capomulin treatment regimen.

Lastly, I calculated the correlation coefficient and established a linear regression model between mouse weight and average observed tumor volume for the entire Capomulin regimen. This model was superimposed onto the existing scatter plot for a comprehensive visual representation of the relationship.
