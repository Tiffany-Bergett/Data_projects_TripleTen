# File Title: transaction_log_business_analysis

This was my third project that I worked on in the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase what I have learned for Business Analytics.

Loom Video Overview can be found <a href='https://www.loom.com/share/a85a12db468543058a842abde0cf4656?sid=c79bd1df-304f-4356-b21f-b9ac1f630909' target=_blank><u>here</u>.</a>
Google Speadsheet can be found <a href='https://docs.google.com/spreadsheets/d/1vkoLxZqsaqfEHdvRRf5ifXiv42zfPA01v6DPhiN9O_k/edit?usp=sharing' target=_blank><u>here</u>.</a>

### Data
- The data was one Google spreadsheet file provided by TripleTen
- `'Business Analyst Project.csv'`: raw transaction logs
    - `'raw_user_activity'`: Each row represents an activity, or event, by a user on the company’s website
        - `'user_id'`: unique customer IDs
        - `'event_type'`: the type of activity by the user
        - `'category_code'`: category of the product being viewed or purchased
        - `'brand'`: company that makes the product
        - `'price'`: price of the product, in USD
        - `'event_date'`: date of the user activity, in YYYY-MM-DD format
    - `'Table of Contents'`: Preformated yet empty table of contents sheet
    - `'Executive Summary`: Preformated yet empty executive summary sheet

### Description:
- 8 page spreadsheet
- Includes raw data (Hidden), processed data, data analysis, and pivot tables.
- Purpose was to analyze the companys' raw transaction logs and turn the event logs into business metrics.

### Assumptions:
- The "raw_user_activity" sheet accurately reflects all website activity for the relevant timeframe.
- Missing values or inconsistencies in the data are minimal and can be ignored.
- The provided data format (columns, data types) is correct and consistent.


### Process:
I first explored, filtered, and cleaned the data.
Then I created built a conversion funnel.
I prepared data for cohort analysis.
Calculated retention rates.
Lastly I finalized formatting and documentation for the client's readability.

### Findings:
| Results | Synopsis |
| :-----------: | ----------- |
| Conversion Funnel | The total conversion rate from view to purchase was 10%. While the view-to-shopping cart conversion rate was 29% | 
| Retention Rates | Retention rates for the 2020-09 cohort group after the first month were only 13%; by the 4th month, it was down to 3% | 
