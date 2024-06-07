# File Title: 2023.11.19.Project4.TB

This was the fourth project that I worked on in the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase what I have learned about Tableau Visualization. The purpose was to consultant the company by reviewing the store’s operations and increase its profitability to avoid bankruptcy.

[<img src="https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Images/Project4Pic.png" alt="First Visulization Sheet">](https://public.tableau.com/views/2023_11_19_Project4_TB/ProfitLossCenters?:language=en-US&:display_count=n&:origin=viz_share_link)

Loom Video Overview can be found <a href='https://www.loom.com/share/0fcb54b436d44a81af73c64152d5f46e?sid=8aed8f0f-c45b-490a-abc3-d7ebe04214f8' target=_blank><u>here</u>.</a>
Tableau Public Share Link: <a href='https://public.tableau.com/views/2023_11_19_Project4_TB/ProfitLossCenters?:language=en-US&:display_count=n&:origin=viz_share_link' target=_blank><u>here</u>.</a> 

### Table of Contents
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [DataSet - SuperStore.xls](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/SuperStore%20Consult/DataSet%20-%20SuperStore.xls) | The original data file provided by TripleTen that was used in this projects analysis. |
| 2 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 3 | [Requirements.txt](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/SuperStore%20Consult/Requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen. |
| 4 | [Reviewer Grade.png](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/SuperStore%20Consult/Reviewer%20Grade.png) | This is the comments left by my project reviewer. |

| Section Title | Description |
| ----------- |----------- |
| DATA | Describes the source of data, included files, tables, and fields. |
| Description | Describes the final product's purpose, software, format, and included visuals. |
| Assumptions | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Process | A general outline of how this project formed from start to finish. |
| Findings | Insights learned from the data analysis. |
| Notes | Notes sent with the project to the reviewer for more context about presentation choices. |

### Data
The data was one Excel spreadsheet file provided by TripleTen:
- `'Superstore.xls'`: each row corresponds to one product sold; sheets were LEFT JOIN'd
    - `'orders'`: details all fields for each ordered item
    - `'returns'`: details all fields for each returned item

### Description:
- 7-page Tableau Visualization
- Includes data analysis, charts, and dashboard.

### Assumptions:
- Profits from sales are totaling in the negative.	
- There is one or more causes for negative profits directly related to orders and returns.
- The operations department will need to make changes.
- The advertising department needs recommendations.

### Process:
I first joined the sheets.
Then I determined profit and loss centers.
Lastly, I examined the contribution returns had on profits.

### Findings:
1. Specific sub-categories were thriving or failing in different regions.
2. Some products have a negative profit and should be discontinued.
3. There are some sub-categories that are negative profit and should be discontinued.
4. There are some sub-categories that are high-profit and should get more focus.
5. The best advertising regions have different optimal time periods and budgets.
6. There are several products that have a return rate of 100% and should be discontinued.
7. The high returns need to be investigated to prevent future problems.

### Notes left for Reviewer:
	I hid some sheets that I used for my Dashboard titled “Advertising” as I did not want the client to look at them individually. This one dashboard answers the only question in part 2, as it has multiple answers and I felt this was the best way to visualize that.
