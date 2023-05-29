# Birth-Trend-Analysis

This project aims to analyze birth data and create an interactive dashboard for visualizing various insights. The dataset was cleaned by removing unwanted rows and columns. Additionally, new columns were created to extract relevant information such as month, current year, age, and age class. The visualization focuses on the number of births by age class distribution, countries and their number of births, the trend of births throughout the years, and the number of births by month.

## Steps Taken

1. Data Cleaning: The initial dataset underwent cleaning to remove any irrelevant or unnecessary rows and columns that were not relevant to the analysis. Furthermore, any misspellings were addressed and corrected.

2. Extracting Month: A new column was created to extract the month from the date column. This step provides granularity for analyzing the number of births by month.

3. Current Year Calculation: Using the datetime.localnow() function in Power Query, a new column was created to capture the current year. This column serves as a reference point for calculating the age of individuals in the dataset.

4. Age Calculation: The age of individuals was determined by subtracting the year from the current year. This calculation provides insights into the age distribution of parents at the time of birth.

5. Age Class Creation: To categorize individuals into age classes, a new column called "Age Class" was created. This column used the IF function to assign age ranges to each individual based on their calculated age. This step enables analysis based on different age groups.

## Visualization Questions

The birth analysis dashboard focuses on answering the following questions through visualizations:

1. Number of Births by Age Class Distribution: Visualize the distribution of births across different age classes using pie chart. This analysis provides insights into the composition of births among different age groups.

2. Countries and Their Number of Births: Use stacked bar chart to display the number of births in each country. This visualization enables the comparison of birth rates across different countries.

3. Trend of Births Throughout the Years: Create line chart to showcase the trend of births over multiple years. This visualization helps identify patterns, spikes, or declining birth rates over time.

4. Number of Births by Month: Display the number of births by month using bar chart. This visualization allows for the identification of seasonal or monthly variations in birth rates.


