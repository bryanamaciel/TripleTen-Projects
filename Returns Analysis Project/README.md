This was the fifth project I completed in the TripleTen Business Intelligence Analytics Program. It was a solo project aimed at demonstrating my skills in building Tableau dashboards and effective data storytelling. The goal was to provide the Superstore CEO with insights into the reasons behind customer returns and offer strategies to reduce them.

DASHBOARD:

This dashboard brings together various visuals to analyze the causes of returns at Superstore, with filtering options by category.

-- Top Customer Returns: Highlights customers with the highest return rates, excluding those with only one purchase. Some customers have a 100% return rate.

-- Top Product Returns: Identifies products with the highest return rates, also excluding single-purchase items. Certain products show a 100% return rate.

-- Returns by State: Displays return rates by state, revealing Utah as the state with the highest return rate.

-- Orders Composite: Compares the number of orders sold to return rates by month to detect seasonal patterns. The top five most returned products are among the least purchased, and returns spike during peak purchasing periods, particularly in August/September and December.

![image](https://github.com/user-attachments/assets/704a5fa4-ebb6-4182-96e1-abcf7ef0bda0)

*** Description:

This project contains 6 Visuals and the reasons behind high return rates at Superstore using a Tableau dashboard with visualizations filtered by category. Key insights included identifying top customers and products with high return rates, mapping returns by state, and uncovering seasonal return trends. The goal was to provide the CEO with a clear understanding of return patterns and actionable strategies to reduce them.

*** Process:

To complete this project, I first analyzed the Superstore data by joining the Returns and Orders tables and creating visuals like scatterplots, bar charts, maps, and time-based charts to identify return patterns. Then, I designed a Tableau dashboard to showcase these insights, starting with mock-ups and adding clear labels and filters. Finally, I presented my findings in a 3-5 minute presentation, explaining the key takeaways and how the dashboard could help reduce returns.

*** Data:

The data was one Excel spreadsheet file provided by TripleTen:

- 'Superstore.xls': each row corresponds to one product sold; sheets were LEFT JOIN'd
 
- 'orders': details all fields for each ordered item
  
- 'returns': details all fields for each returned item

*** Assumptions: 

- Sales profits are currently negative.
  
- One or more issues related to orders and returns are contributing to the negative profits.
  
- The operations department will need to implement changes to address this.

*** Findings: 

- Some customers have exceptionally high return rates, with several having a 100% return rate.

- A number of products also show unusually high return rates, with some having a 100% return rate.
  
- The location of the order delivery is a factor, with Utah showing particular issues.
  
- Returns spike significantly in August, with September following closely, correlating with higher purchase volumes.

*** Reccomendations:

- Provide additional training for employees in the technology department to help customers select the right products.
Contact customers with a 100% return rate to understand the reasons behind their returns and make necessary adjustments to the website or shipping partners.

- Temporarily stop selling problematic products as a short-term solution.
  
- Focus on updating product information, improving size guides, and boosting customer reviews through social media partnerships.
  
- Consider implementing stricter return policies or charging a return fee for purchases from high-return states.
  
- Revise promotional strategies, such as offering gift cards during peak holiday times and shifting from discounts to value-added options like free shipping.
