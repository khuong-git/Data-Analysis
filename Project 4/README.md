You have been hired by XYZAutomotives as a data scientist. Your first task is to analyze the historical data and 
give the company directors insights on how the sales were affected during times of recession. You will provide a 
number of charts/plots to visualize the data and make it easy for the directors to understand your analysis.

The data used in this lab has been artifically created for the purpose of this assignment only. No real data has 
been used.

Data Description
The dataset includes the following variables:
1. Date: The date of the observation.
2. Recession: A binary variable indicating recession perion; 1 means it was recession, 0 means it was normal.
3. Automobile_Sales: The number of vehicles sold during the period.
4. GDP: The per capita GDP value in USD.
5. Unemployment_Rate: The monthly unemployment rate.
6. Consumer_Confidence: A synthetic index representing consumer confidence, which can impact consumer 
spending and automobile purchases.
7. Seasonality_Weight: The weight representing the seasonality effect on automobile sales during the period.
8. Price: The average vehicle price during the period.
9. Advertising_Expenditure: The advertising expenditure of the company.
10. Vehicle_Type: The type of vehicles sold; Supperminicar, Smallfamiliycar, Mediumfamilycar, 
Executivecar, Sports.
11. Competition: The measure of competition in the market, such as the number of competitors or market 
share of major manufacturers.
12. Month: Month of the observation extracted from Date.
13. Year: Year of the observation extracted from Date.

By examining various factors mentioned above from the dataset, you aim to gain insights into how recessions 
impact automobile sales for your company.

This Project will be completed in 2 Parts:
Part 1: Create Visualizations using Matplotlib, Seaborn & Folium
Part 2: Create Dashboard using Plotly and Dash

Part 1: Create visualizations using Matplotib, Seaborn & Folium
TASK 1.1: Develop a Line chart using the functionality of pandas to show how automobile sales fluctuate from 
year to year.
TASK 1.2: Plot different lines for categories of vehicle type and analyse the trend to answer the question “Is 
there a noticeable difference in sales trends between different vehicle types during recession periods?”
TASK 1.3: Use the functionality of Seaborn Library to create a visualization to compare the sales trend per 
vehicle type for a recession period with a non-recession period.
TASK 1.4: Use sub plotting to compare the variations in GDP during recession and non-recession period by 
developing line plots for each period.
TASK 1.5: Develop a Bubble plot for displaying the impact of seasonality on Automobile Sales.
TASK 1.6: Use the functionality of Matplotlib to develop a scatter plot to identify the correlation between 
average vehicle price relate to the sales volume during recessions.
TASK 1.7: Create a pie chart to display the portion of advertising expenditure of XYZAutomotives during 
recession and non-recession periods.
TASK 1.8: Develop a pie chart to display the total Advertisement expenditure for each vehicle type during 
recession period.
TASK 1.9: Develop a lineplot to analyse the effect of the unemployment rate on vehicle type and sales during 
the Recession Period.

Part 2: Create Dashboard using Plotly and Dash
TASK 2.1: Create a Dash application and give it a meaningful title.
TASK 2.2:Add drop-down menus to your dashboard with appropriate titles and options. 
Task 2.3: Add a division for output display with appropriate id and classname property
TASK 2.4: Creating Callbacks; Define the callback function to update the input container based on the selected 
statistics and the output container.
TASK 2.5: Create and display graphs for Recession Report Statistics. 
TASK 2.6: Create and display graphs for Yearly Report Statistics.
