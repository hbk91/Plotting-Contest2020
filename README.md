# Submission for "2020 - John Hunter Excellence in Plotting contest"

1. **Research Question:**

    How does the number of Religious Congregations vary with the GDP generated from Science & Tech Industry across US states?

2. Data Sources:

    Religious Congregations Data:
    - http://www.usreligioncensus.org/compare.php
    - Note: Select '2010' in 'Year' and 'List of State Data' in 'List'

    GDP Data:
    - https://apps.bea.gov/regional/histdata/releases/0612gsp/index.cfm
    - Note: Click on 'GDP by State and Industry'
  
3. How the visual addresses the Research Question:

    The visual plots a regression plot between Number of Religious Congregations per million population vs the GDP per capita for US states. The regression line is downward sloping and so are the scatter points. Thus we may infer that Number of Religious Congregations in a state is inversely proportional to the Science-Tech GDP of a state.

    The visual also shows the Pearson's correlation factor and the associated p-Value. The correlation factor is a substantial -0.62, thus further confirming that the relation between Number of Religious Congregations and Science-Tech industry is negative. Also, the correlation factor is significant at 99% confidence level as the p-Value of 1.6*10^(-6) is much smaller than 0.01.

  
4. How the visual adheres to Alberto Cairo's principles of truth, beauty, function, and insight.
       
- **Truthfulness:** The data has been obtained from reputed sources and there has been no manipulation either during the cleaning of data or during the plotting of data. 2010 Census Data has been Plotted against the GDP values of 2010 so that there is no chance of temporal mismatch between the data sets. (2020 Census Data is yet to come). Only the outlier data points outside 3 Standard Deviations have been removed, which is a standard practice. Only District of Columbia was found to be an outlier. This was an expected result as District of Columbia is a Federal District and is not comparable to the other 50 states. Rest other 50 states are represented in the visual.

- **Beauty:** While the visual is drawn mainly from Functional Point of View and is devoid of explicit embellishments, the color combination has been aesthetically used and is easy on the eyes. Instead of choosing multiple bright colors which strain the eyes, different shades of blue have been used which help the viewer easily discern the different elements of the visual.

- **Functionality:** The graph is highly functional with a high data-ink ratio. Dots represent the scatter points; Regression line is shown by the solid blue line and the shaded blue band is the confidence interval around the regression line. The empty right and top edges have been used to plot histograms for the two variables and then kernel density lines have been overlain on the histograms. Further, Pearson's Correlation Coefficient and Corresponding P-Value have been shown in the empty Top-Right Portion. Thus, the visual uses the plot space judiciously to present functional information.

- **Insightfulness:** The visual at a glance shows the inverse relation between Number of Religious Congregations and Tech GDP which is further corroborated by the Correlation Value. This may have the effect of provoking the reader's interest into researching whether these two variables have a causal relationship or are they correlated to a combination of other common factors or whether the correlation is just by randomness.
