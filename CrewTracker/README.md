# File Title: Call List Merge Report

This was my Externship project that I worked on after graduating from TripleTen Business Intelligence Analytics Program. It was a team project designed to help a real-world company, CrewTracker Software, modernize its reporting system by migrating over 170 Crystal Reports to interactive Power BI dashboards, improving data visualization and user experience for CrewTracker's clients.

[<img src="https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Images/CrewTracker.png" alt="Interactive Merged Report Using Dummy Server">](https://drive.google.com/file/d/127-o2r_JCsCJwlNCtmzJsxAp8Ti1jIi3/view?usp=drive_link)

Video Overview can be found <a href='https://drive.google.com/file/d/127-o2r_JCsCJwlNCtmzJsxAp8Ti1jIi3/view?usp=drive_link' target=_blank><u>here</u>.</a>

### Table of Contents
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Call List Merge Report.PBIX](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/CrewTracker/Call%20List%20Merge%20Report.pbix) | My final project with the Externship, a merged Power BI Dashboard from 3 Crystal Reports. |
| 2 | [Externship Cert.pdf](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/CrewTracker/Externship%20Cert.pdf) | Certificate of Proof for completion of the externship while meeting or exceeding requirements. |
| 3 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 4 | [Requirements.txt](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/CrewTracker/Requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen and CrewTracker. |

| Section Title | Description |
| ----------- |----------- |
| [Description](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/CrewTracker#description) | Describes the final product's purpose, software, format, and included visuals. |
| [Process](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/CrewTracker#process) | Describes the process, including tools or tech used. |
| [Data](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/CrewTracker#data) | Describes the data source, including files, tables, and fields. |
| [Assumptions](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/CrewTracker#assumptions) | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| [Results](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/CrewTracker#results) | Outcome of the project for the client. |
| [Personal Stats](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/CrewTracker#personal-stats) | List of personal contributions to the team project. |

### Description:
- 172 Crystal Reports requested for conversion.
    - All Crystal reports were cataloged for future Externships/Crewtrackers Analyst Team.
    - 18 Power BI Reports completed including Merge Reports.
- First Responder (5 members): Extract data from Crystal Reports.
- Peer Reviewer - Review and validate Power BI reports.
- Power BI Team - Convert & consolidate reports, and design interactive dashboards with longevity.

### Process:
- First Responder:
     1) Connect to CrewTracker Workstation via Remote Desktop Connection.
	2) Screenshot/grab Crystal Report Expected Layout.
	3) Screenshot/grab Crystal Reports Field Explorer Details.
	4) Save the exported PDF view of Crystal Reports.
	5) Copy SQL Query from Crystal reports.
	6) Copy formula field SQL parts and any linked Sub-Reports.
- Peer Reviewer:
     1️) Make sure you can open the Power BI file and determine that it looks more or less like the original Crystal Report
     2️) Check the SQL Query is there and it looks like the original.  
     3️) Check all formula fields have been converted to calculated fields or measures in PowerBI. 
     4️) Check for completeness and the report is achieving the original purpose.
-Call List Merge Report:
     1) Merge source SQL Queries into one SQL Direct Query.
     2) Build Power BI Dashboard according to Call List Reports layout expectations. Using best judgment for variances between the three reports.
     3) Convert Crystal Report Formula Fields into Power BI DAX as Measures and Calculations, ensuring the formatting allows for various potential future uses.

### Data
CrewTracker Software's Microsoft SQL Database (CREWAI and its Dummy Database SnowTracker) on Azure Cloud (anonymized data).
-Large Database with 97 total tables with high-level relationships.

### Assumptions:
- Reports on the initial list that could not be found on the workstation were no longer needed and listed as "File Not Found"
- If a Crystal Report could not open, it needed to be rerouted to a dummy server for this Externship.
- Each Crystal report needed a 1-1 conversation into a Powwer BI Dashboard. However, as our experience in the conversation process grew this requirement was adjusted for comfort level and we were allowed to create merged reports based on a similarity map.

### Results:
Through my *externship, CrewTracker* was able to move from *Crystal Reports(, a legacy reporting tool that can be cumbersome for complex data analysis. We were able to initiate efforts to convert all report data to (Power BI(. This modern platform allows for more user-friendly and interactive dashboards, facilitating deeper data insights. By providing a more intuitive reporting system, CrewTracker will empower its clients to gain a clearer understanding of their data, ultimately leading to improved decision-making and potentially higher client satisfaction.

### Personal Stats:
- As a First Responder I attempted to Catalog = 91 Crystal Reports
- Successful Cataloged Crystal Reports = 73 (the remaining files were "File Not Found")
- Power BI conversations Peer Reviewed = 9
- Power BI Report Completed = 3 (Merged Report into 1)
