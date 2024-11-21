# Economic-Insights-Mapping-U.S-Story
Data Visualization Project


# Economic Insights Dashboard

This project visualizes key economic indicators across U.S. states, including **unemployment rates**, **educational attainment**, **debt trends**, and **cost of living**. The goal is to provide insights into the relationships between these indicators and inform decision-making for policymakers, educators, and the general public.

## Aim of the Project

The aim of this project is to create an interactive **dashboard** that:
- Visualizes **economic indicators** (e.g., unemployment rate, household debt, education level) across U.S. states.
- Highlights correlations between **education** and **economic outcomes** such as **unemployment rates** and **earnings**.
- Allows users to explore trends over time using animated visualizations and dropdown filters.
- Identifies regions in need of targeted interventions based on economic data, particularly in terms of **educational attainment**, **employment opportunities**, and **household debt**.

## Data Sources

This project utilizes data from multiple trusted sources to provide insights into the U.S. economy:

1. **U.S. Census Bureau**: Data on educational attainment levels, regional demographics, and median household incomes by state.
2. **Bureau of Labor Statistics (BLS)**: Unemployment rates, employment trends, and earnings distribution by education level across states.
3. **Federal Reserve Board**: Data on Debt Service Ratio (DSR), Financial Obligations Ratio (FOR), and long-term debt trends in the U.S.
4. **World Population Review**: Household debt trends across states over the years.
5. **Federal Bureau of Government**: State-level cost of living index and other economic growth indicators to correlate with education and employment outcomes.

These datasets are harmonized and cleaned for consistency and accuracy, enabling the generation of meaningful visualizations.

## Tools and Technologies

- **Tableau**: For creating interactive visualizations, dashboards, and applying dynamic filters and animations.
- **Tableau Prep Builder**: Used for data cleaning and transformation before visualization.
- **Excel**: For initial data processing and organizing datasets before importing them into Tableau.
- **GitHub**: For version control and sharing the project.
  
## Installation and Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/AkshataSalunkhe/Economic-Insights-Mapping-U.S-Story.git
    ```

2. Open the Tableau workbook (.twb or .twbx) in **Tableau Desktop**.

3. Connect the data sources in Tableau (if not embedded in the workbook), and ensure that the data loads correctly.

4. Customize the filters, visualizations, and parameter controls according to the needs of the project.

5. Publish the dashboard to **Tableau Public** or **Tableau Server** for interactive sharing.

## Features

- **Interactive Map**: Displays economic indicators for each state with options to filter by **education**, **unemployment rates**, **household debt**, and more.
- **Animated Trends**: Visualizes trends over time for each economic indicator (e.g., Debt Service Ratio, Cost of Living Index) with animation controls to explore year-over-year changes.
- **Dropdown Filters**: Users can select specific economic indicators to display on the map using an interactive dropdown menu.
- **Global Filter**: A single filter that applies to all visualizations in the dashboard, enabling consistent data exploration across multiple views.
- **Forecasting**: Uses historical data to predict future trends in household debt, employment, and educational attainment (optional).

## How to Use the Dashboard

1. **Select an Economic Indicator**: Use the **dropdown filter** to choose between different indicators like **unemployment rate**, **household debt**, or **education level**.
2. **Explore the Map**: The map will display the selected indicator for each state, allowing for geographical comparisons. Hover over a state for detailed information.
3. **Animate Trends**: Use the **Play** button to animate changes in economic indicators over time. The map and charts will update dynamically to show how indicators have evolved.
4. **Apply Global Filters**: Use the global filter to adjust the data across all sheets in the dashboard. This filter will apply universally to all visualizations on the dashboard.

## Dashboards

### 1. **Cost of Living Insights Dashboard**
- **Category-wise Distribution of Cost of Living Expense**: A pie chart visualizing the percentage distribution of key cost-of-living categories (Housing, Utilities, Health, Transportation, etc.).
- **Statewise Distribution of Cost of Living Index**: A bar chart comparing the cost of living index across states, highlighting the top and bottom 5 states.
- **Statewise Breakdown of Expenses by Category**: A grouped bar chart showing the distribution of expenses across different cost categories for each state.

![Cost of Living Dashboard](![WhatsApp Image 2024-11-21 at 18 35 09_42467988](https://github.com/user-attachments/assets/3efdc126-07d7-4782-9e16-b62f34c9e90a))

### 2. **Debt Analysis Dashboard**
- **Statewise Average Household Debt**: A bar chart visualizing the average household debt index across U.S. states.
- **U.S. Debt Service Ratio (DSR) and Financial Obligations Ratio (FOR)**: A line chart showing trends in debt service and financial obligations relative to disposable income.
- **Comparison of High and Low Index Values Across States**: A bar chart comparing high and low index values for each state, highlighting economic disparities.

![Debt Analysis Dashboard](![WhatsApp Image 2024-11-21 at 18 35 29_863ffcba](https://github.com/user-attachments/assets/188ff088-a199-48f5-b362-86df758523df))

### 3. **Education and Employment Dashboard**
- **Unemployment Rates by States: Below and Above 4%**: A bar chart showing states with unemployment rates above or below 4%.
- **Correlation Between Education Levels and Unemployment Rates**: A scatter plot visualizing the correlation between the percentage of bachelor’s degree holders and unemployment rates by state.
- **Earnings and Unemployment Rates by Education Attainment**: A bar chart comparing earnings and unemployment rates by education level.
- **Educational Attainment Across States: Bachelor's vs. High School Graduation Rates**: A dual-axis scatter plot comparing bachelor’s degree attainment with high school graduation rates across states.

![Education and Employment Dashboard](![WhatsApp Image 2024-11-21 at 18 35 46_3da76bc0](https://github.com/user-attachments/assets/d0e2e523-60d2-420b-a9a4-7c4131a5af2c))

## Animation

The project includes an **animation** feature that visualizes trends over time for key economic indicators. The animation displays how economic factors like **household debt** have evolved across states over the years.

Here is an example of the animation used in this project:

![Trends in High and Low Index Values Over Time (1998-2024)](https://github.com/AkshataSalunkhe/Economic-Insights-Mapping-U.S-Story/blob/main/GIF.gif)

- The animation dynamically updates the economic indicators over time, helping users visualize changes year by year.


## References

- **U.S. Census Bureau**: [Link](https://www.census.gov)
- **Bureau of Labor Statistics (BLS)**: [Link](https://www.bls.gov)
- **Federal Reserve Board**: [Link](https://www.federalreserve.gov)
- **World Population Review**: [Link](https://worldpopulationreview.com)






