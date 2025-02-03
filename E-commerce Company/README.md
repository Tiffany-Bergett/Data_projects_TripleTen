# File Title: E-Commerce_Business_Analysis

This was the third project that I worked on in the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase what I have learned in Business Analytics. The purpose was to analyze the companies' raw transaction logs and turn the event logs into business metrics.

[<img src="https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Images/E-Commerce.png" alt="First Sheet of Project**">](https://www.loom.com/share/2e58fde1699848d2b12a2e3284e7867e?sid=42667402-82d2-4f31-82a0-baf41ac16ce7)

Loom Video Overview can be found <a href='https://www.loom.com/share/2e58fde1699848d2b12a2e3284e7867e?sid=0999d9f0-df9f-4a30-9665-ffb61487a7da' target=_blank><u>HERE</u>.</a>
Google Speadsheet can be found <a href='https://docs.google.com/spreadsheets/d/1vkoLxZqsaqfEHdvRRf5ifXiv42zfPA01v6DPhiN9O_k/edit?usp=sharing' target=_blank><u>here</u>.</a>
Raw Data Google Speadsheet can be found <a href='https://docs.google.com/spreadsheets/d/1qWRY5svKGkJRyYNv7K4XvEGm9FpcoJhH5G0p4Qbq0V0/edit?usp=sharing' target=_blank><u>here</u>.</a>

### Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [E-Commerce_Business_Analysis .pdf](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/E-commerce%20Company/E-Commerce_Business_Analysis%20.pdf) | The completed project in a downloadable pdf file provided by. |
| 2 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 3 | [Requirements.txt](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/E-commerce%20Company/Requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen. |
| 4 | [ReviewerGrade3.png](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/E-commerce%20Company/ReviewerGrade3.png) | This is the comments left by my project reviewer, number corresponds with project number. |

### Table of Contents for README
| Section Title | Description |
| ----------- |----------- |
| [Description](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/E-commerce%20Company#description) | Describes the final product's purpose, software, format, and included visuals. |
| [Process](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/E-commerce%20Company#process) | A general outline of how this project formed from start to finish. |
| [Data](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/E-commerce%20Company#data) | Describes the source of data, including files, tables, and fields. |
| [Assumptions](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/E-commerce%20Company#assumptions) | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| [Findings](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/E-commerce%20Company#findings) | Insights learned from the data analysis. |
| [Recommendations](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/E-commerce%20Company#recommendations) | Recommended direction for the stakeholders based on the final analysis. |

#### Description:
- 8 page spreadsheet
- Includes raw data (Hidden), processed data, data analysis, and pivot tables.

#### Process:
I first explored, filtered, and cleaned the data.
Then I created and built a conversion funnel.
I prepared data for cohort analysis.
Calculated retention rates.
Lastly, I finalized the formatting and documentation for the client's readability.

#### Data
The data was one Google spreadsheet file provided by TripleTen. Raw Data Google Spreadsheet can be found <a href='https://docs.google.com/spreadsheets/d/1qWRY5svKGkJRyYNv7K4XvEGm9FpcoJhH5G0p4Qbq0V0/edit?usp=sharing' target=_blank><u>here</u>.</a>
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

#### Assumptions:
- The "raw_user_activity" sheet accurately reflects all website activity for the relevant timeframe.
- Missing values or inconsistencies in the data are minimal and can be ignored.
- The provided data format (columns, data types) is correct and consistent.

#### Findings:
| Results | Synopsis |
| :-----------: | ----------- |
| Conversion Funnel | The total conversion rate from view to purchase was 10%. While the view-to-shopping cart conversion rate was 29% | 
| Retention Rates | Retention rates for the 2020-09 cohort group after the first month were only 13%; by the 4th month, it was down to 3% | 

### Recommendations:
- Address Shopping Cart Abandonment and Purchase Conversion. Future projects can focus on the best approach such as product page vs checkout process as a source of funnel deterioration.
- Enhance customer engagement and loyalty. Potential marketing campaigns could be personalized communications, loyalty programs, and looking into customer support.
- Gain customer feedback for a more targeted strategy.
- Continue data-driven insights to follow changes in the cohort analysis.
