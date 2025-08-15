**World Bank Data Visualization Project**

**Overview**

This project explores and visualizes data from the World Bank.
The dataset contains global development indicators for multiple countries, spanning several decades.
The focus of this project is on exploratory data analysis and visual storytelling using Python.

**Dataset**
Source: World Bank Open Data

Format: Excel

Key Columns:

Country Name – Name of the country

Country Code – ISO country code

Indicator Name – Name of the development indicator

Indicator Code – Unique indicator code

Years (1960–2024) – Numeric values for each year


**Tools & Libraries**

Python – Main programming language

pandas – Data loading and manipulation

matplotlib – Data visualization

numpy – Numerical computations

**Visualizations**

1️Histogram
Purpose: To show the frequency distribution of a selected year’s indicator values across countries.

Insight: Helps identify the spread, distribution shape, and common value ranges for the indicator in a given year.

plt.hist(data_for_year, bins=20, edgecolor='black')
plt.title(f'Histogram of Values in {year_to_plot}')
plt.xlabel('Value')
plt.ylabel('Frequency')
plt.show()

2️Bar Chart
Purpose: To visualize Nigeria’s trend for a selected indicator over the years.

Insight: Shows patterns, growth, or decline over time.

plt.figure(figsize=(12, 6))
plt.bar(nigeria_long["Year"], nigeria_long["Value"], color="skyblue")
plt.title("Nigeria - Indicator Trend Over Time")
plt.xlabel("Year")
plt.ylabel("Value")
plt.show()

**License**

This project is for educational purposes and uses World Bank Open Data.
