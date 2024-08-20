# The-Sparks-Foundation-Data-Science-and-Business-Analytics-Internship
# Exploratory Data Analysis - Retail (Task 3)

### Dashboard Link : https://app.powerbi.com/groups/me/reports/8ea1d6e7-c185-40ce-bdf6-486fd0d90474?ctid=bd03a735-2aa3-4cca-9722-2ae4929ab3ec&pbi_source=linkShare

## Problem Statement

The primary goal of this project, completed as part of my Data Science and Business Analytics internship at The Sparks Foundation, is to conduct an Exploratory Data Analysis (EDA) on the 'SampleSuperstore' dataset to identify weak areas in the business that could be optimized to increase profits.


As a business manager, understanding these areas will allow for better decision-making and strategy formulation. The analysis will involve identifying key business problems by exploring sales, profit, and other relevant metrics across different product categories, customer segments, and geographic locations.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, connected to the Superstore dataset (csv file).
- Step 2 : Open power query editor & check "column distribution", "column quality" & "column profile" options.
- Step 3 : Select "column profiling based on entire dataset".
- Step 4 : Verified data quality and handled any missing or erroneous values.
- Step 5 : Created a custom theme with a clean layout and visually appealing color scheme.
- Step 6 : Incorporated the Superstore branding (logo, colors) for consistency.
- Step 7 : Used card visuals to prominently display key performance indicators (KPIs) like Total Sales (2.3M), Total Profit (286.4K), Quantity Sold (37.9K), and Average Discount (15.6%).
- Step 8 : Created a clustered column chart visualizes sales and profit across categories (Technology, Furniture, Office Supplies) and ship modes, highlighting performance variations.
- Step 9 : Added a detailed table provides a breakdown of sales and profit for each sub-category, enabling deeper analysis of product performance.
- Step 10 : Included a pie chart showcases the distribution of sales and profit across customer segments (Consumer, Corporate, Home Office), revealing segment contributions.
- Step 11 : Added a map visual highlights "Top Sales by City" using circles, indicating sales concentration in major U.S. cities.
- Step 12 : Implemented slicers for "Category," "Region," "Ship Mode," and "Segment" enable users to filter the dashboard and focus on specific areas of interest.
- Step 13 : Ensured a clean and intuitive layout for easy navigation and interpretation of data.
- Step 14 : Published the report to Power BI Service, allowing stakeholders to access and interact with the dashboard for real-time insights and data-driven decision-making.


 
 # DAX Expressions Used

- **Total Sales**: 
  ```DAX
  Total Sales = SUM(SampleSuperstore[Sales])
  ```
  ![Total Sales](https://github.com/user-attachments/assets/fcb777d8-33b8-4025-afd0-689d94b94a8a)
- **Total Profit**: 
  ```DAX
  Total Profit = SUM(SampleSuperstore[Profit])
  ```
  ![Total Profit](https://github.com/user-attachments/assets/8247026a-9c9a-4991-ab04-76cea9d1e445)
- **Average Discount**: 
  ```DAX
  Average Discount = AVERAGE(SampleSuperstore[Discount])
  ```
  ![Avg Discount](https://github.com/user-attachments/assets/26615e1a-d434-4860-8985-9b893edfbf7d)



# Insights

### Total Revenue and Profit

- The company has generated a total revenue of 2.3M with a total profit of 286.4K, resulting in a profit margin of 12.45%. This indicates a moderate financial performance with potential for improvement in profitability.

### Sales and Profit Analysis

- By Category & Ship Mode: The "Technology" category leads in both sales and profit, demonstrating its popularity and high-profit margins. However, the "Furniture" category shows lower profit margins, indicating a need for optimization in pricing or cost management.
- By Sub-Category: A deeper analysis reveals that while "Phones" in the "Technology" category have high sales, their profit margins are lower than expected. Similarly, certain sub-categories within "Furniture" and "Office Supplies" are underperforming, with some even showing negative profits, signaling the need for corrective actions.
- By Segment: The "Consumer" segment emerges as the primary revenue driver, highlighting the importance of catering to this customer group. However, there's room for growth in the "Corporate" and "Home Office" segments, which present untapped potential.

### Geographic Analysis

- The map visual highlights major U.S. cities like New York, Los Angeles, and Seattle as key markets, suggesting potential for expansion in other regions or targeted marketing efforts in these high-performing areas.


### Strategic Recommendations

- Focus on improving the profitability of the "Furniture" category: This could involve adjusting pricing strategies, optimizing supply chain costs, or exploring higher-margin product offerings within this category.
- Address underperforming sub-categories: Identify the root causes of low or negative profits in specific sub-categories and take corrective actions such as product discontinuation, repricing, or targeted marketing efforts.
- Expand into the "Corporate" and "Home Office" segments: Develop tailored marketing campaigns and product offerings to attract customers in these segments, leveraging their growth potential.
- Consider geographic expansion: While focusing on existing high-performing markets, explore opportunities for expansion into other regions based on market research and demand analysis.

Overall, the dashboard reveals a mixed performance picture for the company. While the "Technology" category and the "Consumer" segment show promising results, there are areas for improvement in terms of profitability and market penetration. By addressing the identified challenges and capitalizing on growth opportunities, the company can enhance its overall financial performance and achieve sustainable success.

### Snapshot of the Dashboard

![Sales Dashboard](https://github.com/user-attachments/assets/1945040d-24b4-4663-b103-2b2c0fa8dc04)
