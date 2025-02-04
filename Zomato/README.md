# File Title: Zomato Customer Analysis

This was my Final project for the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase what I have learned throughout the TripleTen Program. The purpose was to complete the Zomato onboarding project to showcase analytical skills to the mock company.

[<img src="https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Images/ZomatoProject.png" alt="First Dashboard">](https://www.loom.com/share/d29a87fb973846829433f6dcf9a91a5b?sid=add8ee32-42ac-48d2-9af6-049f9e8dac77)

Loom Video Overview can be found <a href='https://www.loom.com/share/d29a87fb973846829433f6dcf9a91a5b?sid=add8ee32-42ac-48d2-9af6-049f9e8dac77' target=_blank><u>here</u>. </a>

### Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Raw Data for CSA](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/Zomato/Raw%20Data%20for%20CSA) | Folder containing 2 .xlxs files, one for each table used in the analysis. |
| 2 | [Final Project Report.pdf](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Zomato/Final%20Project%20Report.pdf) | A .pdf file with the written report for this project. |
| 2 | [Final.pdf](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Zomato/Final.pdf) | A .pdf file with the written report for this project. |
| 3 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 4 | [Requirements.txt](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Zomato/Requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen. |
| 5 | [Zomato.TB.pbix](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Zomato/Zomato.TB.pbix) | Power BI save file for easy access to specific DAX, calculations, and measures. |

### Table of Contents for README
| Section Title | Description |
| ----------- |----------- |
| [Description](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/Zomato#description) | Describes the final product's purpose, software, format, and included visuals. |
| [Process](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/Zomato#process) | Describes the process, including tools or tech used. |
| [Data](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/Zomato#data) | Describes the data source, including files, tables, and fields. |
| [Assumptions](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/Zomato#assumptions) | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| [Findings](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/Zomato#findings) | Insights learned from the data analysis. |

#### Description:
- This was a Customer Segmentation Analysis.
- 2 pages in Power BI.
- Includes KPI cards, Pie charts, bar charts, and RFM analysis.

#### Process:
I first learned of the problem presented in its entirety and its requirements for approval.
Then, I chose software and created my first submission, the "Decomposition Plan".
After, I analyzed the data and created visualizations and dashboards for a second submission.
Lastly, I presented my findings in a report as my 3rd and final submission piece.

#### Data
TripleTen provided an archived file of 5 separate Excel files from the mock company Zomato. I used 2 for this project.
- `'Zomato data.zip'`: Compressed Excel files provided by team lead
    - `'orders'`: All orders made from the menu by all customers at all restaurants between Oct. 4th, 2017, and June 26th, 2020.
    - `'users'`: All customers who completed orders during the designated time frame and their demographic information.
- `'Measures Table'`: Created table for analysis and to maintain the integrity of original files. Housing all used measures.
- `'Calendar'`: Created table for analysis and to maintain the integrity of original files. Housing all date information for potential calculations.
- `'Segmentations'`: Created table for analysis and to maintain the integrity of original files. Housing all segments and RFM scores needed for inclusion.
- `'RFM Table'`: Created table for analysis and to maintain the integrity of original files. Housing all RFM calculations.

#### Assumptions:
- The provided test datasets are accurate, complete, and consistent.
- Missing values or inconsistencies are minimal and will not significantly impact the analysis.
- The column descriptions accurately reflect the content of each table.
- The provided tables (orders and users) contain all the necessary information for the chosen analysis.
- Zomato's business context and industry trends are considered while interpreting the data.

#### Findings:
1. Customers mostly consist of 23-year-old unmarried men.
2. There is a natural distribution for age however the range is small at 18-34.
3. Women are close behind, but there are significantly more customers who are single than married.
4. Zomato’s customers usually have small family sizes (2-3), educated, but unemployed.
5. Employed customers tend to be below middle class ($50,000/yr).

