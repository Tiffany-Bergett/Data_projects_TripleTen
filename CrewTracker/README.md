<!DOCTYPE html>
<html>
<style>
body {
  font-size: 20px;
}
</style>
<body>

<span style='font-size:100px;'>&#128679;</span>

</body>
</html> 
------------------------ReadMe Under Construction -----------------------------



# File Title: Call List Merge Report.PBIX

This was my Externship project that I worked on after graduating from TripleTen Business Intelligence Analytics Program. It was a team project designed help a real world company, CrewTracker Software, to modernize their reporting system by migrating over 170 Crystal Reports to interactive Power BI dashboards, improving data visualization and user experience for CrewTracker's clients.

Loom Video Overview can be found <a href='HERE' target=_blank><u>here</u>.</a>

### Table of Contents
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [File Name](LINKHERE) | Blah blah blah. |
| 2 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 3 | [Requirements.txt](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/CrewTracker/Requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen and CrewTracker. |
| 4 | [File Name](LINKHERE) | Blah blah blah. |

| Section Title | Description |
| ----------- |----------- |
| DATA | Describes the source of data. |
| Description | Describes the goal and end results of the externship. |
| Assumptions | Describes assumptions to include given by TripleTen or CrewTracker. |
| Process | A general outline of how this project formed from start to finish. |
| Results | How CrewTracker benefited from this externship. |
| Personal Stats | My contribution to the externship. |


### Data
CrewTracker Software's Microsoft SQL Database (CREWAI and it's Dummy Database SnowTracker) on Azure Cloud (anonymized data).
-Large Datbase with 97 total tables with high-level relationships.

### Description:
- 172 Crystal Reports requested for conversion.
    - All Crystal reports were cataloged for future Externships/Crewtrackers Analyst Team.
    - 18 Power BI Reports completed including Merge Reports.
      
- First Responder (5 members): Extract data from Crystal Reports.
- Peer Reviewer - Review and validate Power BI reports.
- Power BI Team - Convert & consolidate reports, design interactive dashboards with longevity.

### Assumptions:
- Reports on initial list that could not be found on the workstation were no longer needed and listed as "File Not Found"
- If a Crystal Report could not open, it needed to be rerouted to a dummy server for the purposes of this Externship.
- Each Crystal report needed a 1-1 converstion into a Powwer BI Dashboard. However, as our experience in the converstion process grew this requirment was adjusted for comfort level and we were allowed to create merged reports based on a similarity map.

### Process:
First Responder:
  1) Connect to CrewTracker Workstation via Remote Desktop Connection.
	2) Screenshot/grab Crystal Report Expected Layout.
	3) Screenshot/grab Crystal Reports Field Explorer Details.
	4) Save the exported PDF view of Crystal Reports.
	5) Copy SQL Query from Crystal reports.
	6) Copy formula field SQL parts and any linked Sub-Reports.

Peer Reviewer:
  1️) Make sure you can open the Power BI file and determine that it looks more or less like the original Crystal Report
  2️) Check the SQL Query is there and it looks like the original.  
  3️) Check all formula fields have been converted to calculated fields or measures in PowerBI. 
  4️) Check for completeness and the report is achieving the original purpose.

Call List Merge Report:
  1) Merge source SQL Queries into one SQL Direct Query.
  2) Build Power BI Dashboard according to Call List Reports layout expectations. Using best judgement for variances between the three reports.
  3) Convert Crystal Report Formula Fields into Power BI DAX as Measures and Calculations, ensuring the formatting allows for various potential future uses.

### Results:
Through my externship, CrewTracker was able to move from Crystal Reports, a legacy reporting tool that can be cumbersome for complex data analysis. We were able to initiate efforts to convert all report data to Power BI. This modern platform allows for more user-friendly and interactive dashboards, facilitating deeper data insights. By providing a more intuitive reporting system, CrewTracker will empower its clients to gain a clearer understanding of their data, ultimately leading to improved decision-making and potentially higher client satisfaction.

### Personal Stats:
- As a First Responder I attempted to Catalog = 91 Crystal Reports
- Successful Cataloged Crystal Reports = 73 (the remaining files were "File Not Found")
- Power BI conversations Peer Reviewed = 9
- Power BI Report Completed = 3 (Merged Report into 1)
