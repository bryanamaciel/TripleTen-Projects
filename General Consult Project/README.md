This was my fourth project in the TripleTen Business Intelligence Analytics Program. It was a solo project aimed at demonstrating my Tableau visualization skills. My goal was to act as a consultant for the company, analyzing the store’s operations to help boost profitability and prevent bankruptcy.

![image](https://github.com/user-attachments/assets/c7c1df2f-3361-4a87-885b-248bda1c595f)

*** Description: 
This project involved analyzing Superstore's operational data to identify key profit and loss drivers, assess advertising opportunities, and evaluate product return rates. Using data visualization techniques on Tableau, I highlighted profitable product categories, recommended strategic advertising by state and month, and identified high-return products and customers. The final analysis provided actionable insights to improve profitability and support data-driven decision-making for the struggling superstore.

*** The Process:

1.) Data Preparation: Import the Superstore.xls dataset into Tableau. Perform a LEFT JOIN between the Orders and Returns tables to align sales data with return information.
- Profit & Loss Analysis: Create visualizations comparing different product categories, regions, and sales dimensions to identify top
  profit centers and loss-making areas. Use bar charts, heat maps, and pivot tables to visualize profitability by product and region.
  
2.) Advertising Strategy: Analyze sales trends by state and month to find the best times and places to advertise. Use line charts to visualize average profit per unit sold over time and calculate potential ad spend based on return on ad spend (ROAS) metrics.

3.) Return Rate Assessment: Create a calculated field to convert "Yes" and "null" values in the Returned column to 1and 0, respectively. Visualize return rates by product and customer using scatter plots or bubble charts to identify trends in high-return items or customers.

4.) Final Presentation: Compile the insights into a dashboard with key visualizations and a clear narrative to support your recommendations. Publish the dashboard on Tableau Public and provide a link in your README.md file for easy access.

*** The Data:
The Superstore.xls file includes two primary sheets:

  - 'orders': Contains detailed information for each product sold, with each row representing an individual ordered item.
  - 
  - 'returns': Includes data on returned products, providing all relevant fields for returned items.

*** Initial Assumptions:

- The superstore's current sales strategy is contributing to negative overall profits.
  
- High return rates are likely impacting profitability and may indicate quality or satisfaction issues.
  
- Operational inefficiencies, such as product selection or shipping methods, may be driving losses.
  
- The advertising department requires targeted insights to improve the return on ad spend.

*** Findings: 
- The top profit-generating subcategories are Copiers, Phones, and Accessories, while Tables, Bookcases, and Supplies lead to losses.
- The West Region shows strong profits in Office Supplies and Technology, whereas the Central Region struggles with losses in Office Supplies and Furniture.
- Certain products contribute significantly to losses, with some exceeding $20k in negative profits.
- Advertising should focus on Indiana in October, Vermont in November, and Washington in March.
- High return rates are a major issue, with some products and customers reaching 100% returns, highlighting the need to reassess product offerings.

*** Business Recommendations:

• Optimize Product Offerings: Discontinue underperforming products, especially those contributing to high losses (e.g., Tables, Bookcases, Supplies). Shift focus to top profit-generating subcategories like Copiers, Phones, and Accessories.

• Regional Strategy: Increase sales efforts and promotions in the West Region, emphasizing Office Supplies and Technology. Reevaluate strategies in the Central Region, particularly for Office Supplies and Furniture, to reduce losses.

• Targeted Advertising: Implement advertising campaigns in Indiana (October), Vermont (November), and Washington (March) to maximize seasonal profit opportunities. Set a clear budget aligned with the return on ad spend ratio.

• Address Returns: Investigate products and customers with high return rates (up to 100%) to understand root causes. Improve product quality, adjust marketing messages, or set clearer return policies to minimize losses.

• Operational Improvements: Collaborate with the operations department to identify process inefficiencies contributing to negative profits and high return rates. Implement changes to streamline workflows and improve profitability.

