# File Title: E-Commerce_Business_Analysis

This was the third project that I worked on in the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase what I have learned in Business Analytics. The purpose was to analyze the companies' raw transaction logs and turn the event logs into business metrics.

[<img src="https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Images/Project3Pic.png" alt="First Sheet of Project**">](https://docs.google.com/spreadsheets/d/1vkoLxZqsaqfEHdvRRf5ifXiv42zfPA01v6DPhiN9O_k/edit?usp=sharing)

Loom Video Overview can be found <a href='https://www.loom.com/share/2e58fde1699848d2b12a2e3284e7867e?sid=0332f23c-bff4-4451-ab6b-8e20544076bd' target=_blank><u>here</u>.</a>
Google Speadsheet can be found <a href='https://docs.google.com/spreadsheets/d/1vkoLxZqsaqfEHdvRRf5ifXiv42zfPA01v6DPhiN9O_k/edit?usp=sharing' target=_blank><u>here</u>.</a>

### Table of Contents
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Business Analytics Project.csv](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/E-commerce%20Company/Business%20Analytics%20Project.csv) | The original data file provided by TripleTen that was used in the analysis of this project. |
| 2 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 3 | [Requirements.txt](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/E-commerce%20Company/Requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen. |
| 4 | [ReviewerGrade3.png](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/E-commerce%20Company/ReviewerGrade3.png) | This is the comments left by my project reviewer, number corresponds with project number. |

| Section Title | Description |
| ----------- |----------- |
| DATA | Describes the source of data, included files, tables, and fields. |
| Description | Describes the final product's purpose, software, format, and included visuals. |
| Assumptions | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Process | A general outline of how this project formed from start to finish. |
| Findings | Insights learned from the data analysis. |

### Data
The data was one Google spreadsheet file provided by TripleTen
- `'Business Analyst Project.csv'`: raw transaction logs
    - `'raw_user_activity'`: Each row represents an activity, or event, by a user on the company’s website
        - `'user_id'`: unique customer IDs
        - `'event_type'`: the type of activity by the user
        - `'category_code'`: category of the product being viewed or purchased
        - `'brand'`: the company that makes the product
        - `'price'`: price of the product, in USD
        - `'event_date'`: date of the user activity, in YYYY-MM-DD format
    - `'Table of Contents'`: Preformated yet empty table of contents sheet
    - `'Executive Summary`: Preformated yet empty executive summary sheet

### Description:
- 8 page spreadsheet
- Includes raw data (Hidden), processed data, data analysis, and pivot tables.

### Assumptions:
- The "raw_user_activity" sheet accurately reflects all website activity for the relevant timeframe.
- Missing values or inconsistencies in the data are minimal and can be ignored.
- The provided data format (columns, data types) is correct and consistent.

### Process:
I first explored, filtered, and cleaned the data.
Then I created and built a conversion funnel.
I prepared data for cohort analysis.
Calculated retention rates.
Lastly, I finalized formatting and documentation for the client's readability.

### Findings:
| Results | Synopsis |
| :-----------: | ----------- |
| Conversion Funnel | The total conversion rate from view to purchase was 10%. While the view-to-shopping cart conversion rate was 29% | 
| Retention Rates | Retention rates for the 2020-09 cohort group after the first month were only 13%; by the 4th month, it was down to 3% | 
