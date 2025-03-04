This was my sixth project in the TripleTen Business Intelligence Analytics Program which focused on applying my Power BI skills. The purpose of this project is to analyze data from publicly available Shopify websites to explore the app landscape and identify key factors that contribute to the Shopify app’s success.

*** The Description:

- This is a three page presentation dashboard made on Power BI.
- Contains KPI cards, charts, and data analysis.

*** The Process: 

Part 1: App Landscape
- Created a Power BI page named App Landscape.
- Added a KPI Card showing the total number of unique apps.
- Created a Line Chart of total reviews over time.
- Made a Scatterplot comparing review count and average rating, with a text box for interpretation.

Part 2: Reviews
- Created a Power BI page named "Reviews".
- Added a DAX column 
- Displayed the average helpful_reviews in a Card.
- Added ANOTHER DAX column (developer_answered = IF(ISBLANK(developer_reply), 0, 1)).
- Created a Scatterplot comparing average rating to developer responses.

Part 3: App Reviews
- Created a Power BI page named App Reviews.
- Established a many-to-one relationship between app_id (Reviews) and id (Apps).
Created Bar Charts:
    - Developer vs. Total rating.
    - Developer vs. Average helpful_review (for more accurate insights).
    - Developer vs. Responsiveness, filtered for apps with over 500 reviews.

*** The Data:

- "apps": Details of the apps on Shopify apps marketplace
- "apps_categories": Join tables to connect apps with categories
- "categories": Categories of the apps. Each app has multiple categories
- "reviews": Each review (row) contains information on user opinion about the related app (rating and comment). Also, it contains the response from the developer if present.

Initial Assumptions:
- The data showed in the shopify.xlxs file is clean and concise with minimal mistakes.
- The names of columns and data types accurately describe relevent information.
- The data extracted from the Shopify website is accurate to the App Landscape.

Findings: 

- New apps are more likely to receive ratings shortly after launch.
  
- Most app ratings are positive overall.
  
- Reviews tend to be higher when developers respond to them.
  
- Reviews marked as helpful have an average rating of 5.48.
  
- The developer Elfsight has the highest total combined ratings, with 135.10 stars.
  
- The developer Pictorem holds the highest average of helpful reviews, with 50.
  
- The developer FireaApps has responded to the most reviews, with 6,008 responses.
