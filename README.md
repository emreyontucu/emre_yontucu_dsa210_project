# Sabancı University DSA210 - Fall 2024-2025 Term Project

My name is Emre Yontucu (Student ID: 32463). Below you can find my project:

## Motivation:
 The purpose of this project is to analyze the personal data from Ticket Restaurant Card. By examining this data I aim to gain depper insights of by spending habits. So that this project mainly focuses on:
 ####   •Observing my eating behaviours.
 ####   •How my spending habits  change between summer and school period. 
 ####   •Identifying the food categories I spend most on.
 ####   •Tracking how quickly my balance depletes after each top-up.

 ## Hypothesis:
  This project is based on the following hypothesis:
   #### •Seasonal Expenditure Differences: I assume that my spending habits is different compared to the summer period and school period. I assume higher spending in school period.
   #### •Food Category:  I assume I spent almost the whole money on the card for the meal. I think that cafes will be the second popular category.
   #### •Balance Deplation: I assume my limit on the card expires within 2-3 weeks after each top-up during the school term.
   #### •Daily Spending: I assume I have higher spending rates on the weekdays.
   #### •Restaurant: I assume I used this card for small groups of restaurants. I think I usually use the card for the same restaurants.
## The following tools will be used in this project:
  Python:
  #### • Pandas: For data structuring.
  #### • Matplotlib and Seaborn: For visualization.
 #### • Numpy: For mathematical computations.
#### •Jupyter Notebook: For coding and analysis.
#### •Excel: For handling the raw data.

## Data Source:
  The data was retrieved from Ticket Restaurant application and exported in Excel format.
  This Excel table shows the:
  #### •Restaurant name: Name of the restaurantthe transaction took place.
  #### •Transaction date: Date that where the transaction took place.
  #### •Transaction amount: The amount of spending during the transaction.
  #### •Remaining card balance: Balance left after the transaction.

  ## Data Collection Method:
  #### •Transaction Data: The excel formatted data was moved from the Ticket Restaurant application. Approximately 1 year's worth of data can be seen in this excel file.  This dataset forms the basis of almost all analysis.
  ####  •Data Cleaning: Any missing or wrong data will be handled and corrected.
  
 ####  •Classification of Transactions: Transactions will be categorized by looking the restaurant name and the descriptions of transactions. Categories such as "Fast Food", "Cafe" will be assigned.
 
 ####  •Spending Periods: For spending periods, starting and ending dates of the school period will be used. So that it can be compared with the summer and school periods.


## Analysis:
 ####   •Expenditure Trends by Periods: Comparing the spending amount between summer and school periods. Visualizing these patterns with line and bar charts.
 ####   •Food Category: Finding which food category I spent most on with percentages Then displaying them with box plots.
 ####   •Balance Deplation Analysis: I will check in which my balance runs out faster and compare them. Displaying them with scatter plots.
 ####   •Daily Spending Analysis: I will group the data with days and visualize them by using histogram and bar charts. 
 ####   •Highest Spending: I will determine the restaurants with highest spending and ranked them with violin plots.

## Hypothesis:
 ####   •Spending Patterns: Identify whether spending is more frequent or larger on weekdays or weekends. Provides actionable insights for budgeting and financial planning.
 ####   •Statistical Confidence: The p-value quantifies the confidence level in rejecting or accepting the null hypothesis:
 ####   •If p-value < 0.05: There is a significant difference between weekday and weekend spending.
 ####   •Otherwise: Spending behavior does not differ significantly.
 ####   •HCustom Implementation: The t-test is manually implemented using numpy, demonstrating the mathematical process behind hypothesis testing and removing reliance on external libraries.

  
 ## Findings:
 ####    •I used this card more during school period than summer.
 ####    •Almost all the spendings can be seen in restaurants, followed by cafes.
 ####    •On average, by balance dies out about two weeks after the top-up's.
 ####    •The card is used more on weekdays than on weekends.

## Limitations:
 ####   •The analysis is based on personal data. So it can be generalized. Also it has some private data which will not shown here. Personal identifiers such as card number, and location. These are not included in the project.

  
