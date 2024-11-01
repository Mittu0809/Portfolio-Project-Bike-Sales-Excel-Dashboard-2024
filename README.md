# Portfolio-Project-Bike-Sales-Excel-Dashboard-2024
An Excel dashboard project analyzing bike sales data with pivot tables, interactive filters, and visualizations. Includes data cleaning, demographic insights, and dynamic charts.

Bike Sales Dashboard Project 
This project involves creating a dynamic, interactive dashboard in Excel to analyze bike sales data. The dashboard includes data cleaning, pivot table setup, and visualizations with interactive filters to provide insights on bike purchase trends based on demographic and lifestyle variables.

Project Overview
In this project, we:

- Cleaned and prepared the data for analysis.
- Created a series of pivot tables and charts.
- Designed an interactive dashboard where users can filter data to explore key insights.
- The final dashboard allows users to visualize data on average income, bike purchase trends by commute distance, and age demographics with slicers for focused insights.

Data Overview
The original dataset, bike_buyers, contains the following columns:

- ID: Unique identifier for each bike buyer.
- Marital Status: Buyer’s marital status (Single or Married).
- Gender: Buyer’s gender (Male or Female).
- Income: Buyer’s income in dollars.
- Children: Number of children.
- Education: Buyer’s education level (e.g., Bachelors, High School).
- Occupation: Job role of the buyer (e.g., Management, Clerical).
- Home Owner: Homeownership status (Yes/No).
- Cars: Number of cars owned.
- Commute Distance: Distance buyer commutes (0-1 Mile, 10+ Miles, etc.).
- Region: Region of residence (North America, Europe, Pacific).
- Age: Buyer’s age.
- Purchased Bike: Whether a bike was purchased (Yes/No).
  
Data Cleaning Steps:
1. Duplicates Removal: Removed duplicate entries.
Standardization:
2. Replaced abbreviations (e.g., 'M' to 'Married' in Marital Status).
Ensured Gender column reads as Male or Female.
Maintained Income in currency format for dashboard purposes.
3. Age Brackets Creation: Added an Age Bracket column with categories:
Old: Age >54
Middle Aged: 31 ≤ Age ≤ 54
Adolescent: Age <31
4. Validation: Checked all columns for consistency and ensured no spelling errors or misclassified data.
   
Pivot Tables and Visualizations: 

1. Average Income by Bike Purchase Status and Gender
- Created a pivot table to compare the average income of bike buyers and non-buyers by gender.
- Visualization: Clustered Column Chart showing average income segmented by gender and purchase status.
2. Bike Purchase Count by Commute Distance
- Analyzed bike purchase trends based on commute distance.
- Visualization: Line Chart to observe purchase trends relative to commute distance.
3. Bike Purchase by Age Brackets
- Created a pivot table to analyze bike purchases across different age brackets.
- Visualization: Line Chart with Markers for clear differentiation between age groups.

  
Dashboard Design
The final dashboard integrates the key visualizations and allows filtering through slicers. It includes:

1. Charts:
- Average Income by Gender and Purchase Status.
- Commute Distance and Bike Purchase Trend.
- Bike Purchases by Age Bracket.
  
2. Slicers for filtering data by:
- Marital Status
- Region
- Education

3. Layout and Style:
- Dashboard title "Bike Sales Dashboard" with merged cells and custom font styling.
- Color-coded charts and slicers for clarity and improved readability.

Insights
- Income & Purchase: Higher income is associated with a higher likelihood of bike purchase.
- Commute Distance: Buyers with medium commute distances (2-5 miles) tend to purchase more bikes.
- Age Group Trend: Middle-aged individuals (31-54 years) are the largest group of bike purchasers.

Conclusion: 
This project demonstrates how Excel can be used for data analysis and dashboard creation, showcasing skills in data cleaning, pivot tables, and visualization. The interactive dashboard serves as a powerful tool to explore bike purchase trends by various demographics, providing meaningful insights into the data.

FINAL DASHBOARD: 

<img width="415" alt="image" src="https://github.com/user-attachments/assets/ae6105e1-cd38-4ffc-8818-8bf83c02bc21">
