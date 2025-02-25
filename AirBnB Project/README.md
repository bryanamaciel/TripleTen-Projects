This was my first TripleTen project, where I analyzed Manhattan's vacation rental market using Airbnb data to identify the most attractive neighborhoods and property sizes for investment and estimated potential revenue for top-performing listings.
![image](https://github.com/user-attachments/assets/b01217b0-7d00-4e96-96e3-f4d3b66def89)

***Description:

This project involved analyzing Manhattan's vacation rental market using Airbnb data to provide investment insights for a client. Neighborhood and property size attractiveness were assessed by evaluating rental frequency through the number of reviews in the last 12 months. Top-earning listings were identified by calculating revenue based on rental availability and adjusted prices. The analysis included data cleaning, pivot tables, and visualizations to offer clear recommendations on the most profitable neighborhoods, optimal property sizes, and potential annual earnings.

***Process:

Cleaned the data by standardizing the "neighborhood" and "bedrooms" columns to remove inconsistencies.
Created pivot tables to identify the most attractive neighborhoods based on the number of reviews in the last 12 months.
Analyzed property sizes by generating pivot tables to determine the most popular listings for vacation rentals, with a focus on neighborhoods like Harlem.
Calculated revenue generation by using the "calendar" data, summing nightly revenue, and estimating annual earnings for top listings.
Visualized findings to provide actionable insights on the best neighborhoods and property types for investment.

***Data: 

The data was one Google spreadsheet file provided by TripleTen:

'nyc_airbnb_data.csv': each row corresponds to one listing on AirBnB in September 2022
'data_dictionary': summary of field titles seen in the file and its data type
'listings': unique listings available with all available data
'calendar': listings with upcoming availabilities and date-type data

***Assumptions:

- Neighborhood Popularity: The number of reviews accurately reflects the popularity of listings, with more reviews indicating higher rental frequency.
- Property Size Preferences: The size of the property (i.e., number of bedrooms) directly correlates with the popularity of vacation rentals in different neighborhoods.
- Revenue Estimation: Adjusted price data is reliable for estimating nightly revenue, and total revenue can be approximated by multiplying the 30-day revenue by 12 for annual estimates.
- Calendar Availability: Listings marked with "f" in the availability column of the calendar data indicate rented properties, and the associated adjusted price should be used for revenue calculation.
- Top Listings Criteria: The most attractive listings are based on the top 10 neighborhoods by reviews and the most popular property size in each neighborhood, which will be used for further revenue analysis.
- Return on Investment: The estimated annual revenue based on the 30-day data will be an accurate reflection of the potential earnings for each top listing in the selected neighborhoods.
- Data Consistency: The data in the listings and calendar sheets is accurate, with consistent formatting and no major discrepancies in listing or availability information.
- Revenue Calculation: Revenue earned is consistent with the adjusted price listed in the calendar data and can be multiplied by 12 to estimate annual earnings.
- Focus on Top Listings: Only listings that meet the top neighborhood and property size criteria will be included in the analysis for revenue estimation.

***Findings:

-- The top 10 popular neighborhoods for vacation rentals are the following in decending order: Lower East Side, Hell's Kitchen, Harlem, Midtown, Upper West Side, Chelsea, East Village, East Harlem, West Village, Nolita.
-- Most Attractive Neighborhoods: The top 10 neighborhoods with the highest number of reviews in the past 12 months are identified as the most attractive for vacation rentals. These neighborhoods reflect the highest rental frequency, indicating strong demand.
-- Most Popular Property Sizes: The most popular property size for vacation rentals across the top 10 neighborhoods is typically one-bedroom units. Midtown, however, stands out with studios being the most popular. Harlem, in particular, prefers 2-bedroom properties.
-- Revenue Generation: The top-earning listings are calculated by aggregating the revenue from rented properties in the top neighborhoods. The highest-earning listing in the analysis generated $29,940 during a 30-day period, with an estimated annual revenue of $358,680.
-- These findings suggest that investing in one-bedroom properties across the top neighborhoods (except for Midtown, where studios are most popular) could yield the highest return on investment. The analysis also recommends focusing on neighborhoods with high rental frequencies for optimal profitability.

***Reccomendations:

- Focus on High-Demand Neighborhoods: Invest in vacation rental properties located in the top 10 neighborhoods with the highest rental activity, as these areas show the greatest demand. Properties in these neighborhoods are likely to see higher occupancy rates, maximizing rental income.
- Optimize Property Size Offerings: Since one-bedroom units are the most popular across most of the top neighborhoods, prioritizing the acquisition of one-bedroom properties can increase profitability. For Midtown, where studios are in higher demand, investing in studio units will yield better returns.
- Maximize Revenue Potential: The highest-earning listing generated substantial revenue over a 30-day period, indicating significant financial potential. Property managers should target similar properties in high-demand areas, focusing on those with similar occupancy patterns to maximize rental income.
- Annual Revenue Estimation: With annual revenue projections based on 30-day sample periods, businesses should focus on scaling operations in profitable neighborhoods and prioritize units with consistent high performance, adjusting their marketing and pricing strategies accordingly to maintain competitive advantage.
- Tailored Marketing Strategies: Since certain neighborhoods have higher preferences for specific property sizes, marketing strategies should be tailored to match these preferences. Advertising efforts should highlight the right property type for each neighborhood (e.g., one-bedrooms for most areas, studios for Midtown) to attract potential renters.
