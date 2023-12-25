# File Title: ShopifyPBI

This was my 6th project that I worked on in the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase what I have learned for Power BI.

Loom Video Overview can be found <a href='https://www.loom.com/share/ce9c49cdaee940119543cc38f0d34c09?sid=d68d5288-388a-472f-b182-8ce23b8cb7ec' target=_blank><u>here</u>.</a>

### Data
- The excel file provided by TripleTenwas was public data scraped from the Shopify App Store. It includes 7 tables: 
    - ` apps`: Details of the apps on Shopify apps marketplace
    - `apps_categories`: Join tables to connect apps with categories
    - `categories`: Categories of the apps. Each app has multiple categories
    - `reviews`: Each review (row) contains information on user opinion about the related app (rating and comment). Also, it contains the response from the developer if present.

### Description:
- 3 page Power BI Dashboard
- Includes data analysis, KPI cards and Charts
- Purpose was to review the landscape of apps on the Shopify platform, using data scraped from publicly available Shopify websites, and to figure out what key factors play into the success of a Shopify app.

### Assumptions:
- The scraped data from Shopify websites is accurate and representative of the actual app landscape.
- The data in the shopify.xlsx file is complete and consistent, with minimal missing values or inconsistencies.
- The provided column names and data types in the tables accurately reflect their content.

### Process:
I first assessed the app store landscape using KPI cards and charts.
Then I cataloged review data with cards and charts.
Lastly I analyzed app developers across review types.

### Findings:
1. New Apps are more likely to be rated early in their deployment.
2. Most apps are rated favorably.
3. Reviews are higher for an app if a developer answered the review.
4. Reviews that have been voted as helpful have a weighted average of 5.48.
5. The app developer "Elfsight" has the highest combined ratings at 135.10 stars.
6. The app developer "Pictorem" has the highest average helpful reviews at 50.
7. The app developer "FireaApps" has responded to the highest amount of reviews at at 6,008 responses.
