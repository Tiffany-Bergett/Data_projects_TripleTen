# File Title: nyc.airbnb.data_v1.3.29_2023.10.21

This was my first project I worked on in the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase what I have learned for Advanced Spreadsheets.

[<img src="https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Images/Project1Pic.png" alt="First Sheet of Project">](https://docs.google.com/spreadsheets/d/1-BA2THPUa9GJlQce1T_tnS487xvcGe3LJv34cnminzI/edit?usp=sharing)


Loom Video Overview can be found <a href='https://www.loom.com/share/ce9c49cdaee940119543cc38f0d34c09?sid=d68d5288-388a-472f-b182-8ce23b8cb7ec' target=_blank><u>here</u>.</a>
Projects Google Speadsheet can be found <a href='https://docs.google.com/spreadsheets/d/1-BA2THPUa9GJlQce1T_tnS487xvcGe3LJv34cnminzI/edit?usp=sharing' target=_blank><u>here</u>.</a>

### Table of Contents
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 2 | [Requirements.txt](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Vacation%20Rental%20Market/Requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen. |
| 3 | [ReviewerGrade1.png](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Vacation%20Rental%20Market/ReviewerGrade1.png) | This is a .png file showing the comments left by my project reviewer. |
| 4 | [nyc_airbnb_data.csv](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Vacation%20Rental%20Market/nyc_airbnb_data.csv) | The original data file provided by TripleTen that was used in this projects analysis. |

| Section Title | Description |
| ----------- |----------- |
| DATA | Describes the source of data, included files, tables, and fields. |
| Description | Describes the final products purpose, software, format, and included visuals. |
| Assumptions | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Process | A general outline of how this project formed from start to finish. |
| Findings | Insights learned from the data analysis. |

### Data
The data was one Google spreadsheet file provided by TripleTen:
- `'nyc_airbnb_data.csv'`: each row corresponds to one listing on AirBnB in September 2022
    - `'data_dictionary'`: summary of field titles seen in file and it's data type
    - `'listings'`: uniquely listings available with all available data
    - `'calendar'`: listings with upcoming availabilities and date type data

### Description:
- 17 page spreadsheet
- Includes raw data (Hidden), processed data, data analysis, pivot tables, and a bar chart.
- Purpose was to determine what types of properties should be targeted for the vacation rental market, in the Manhattan borough of New York City based on available AirBnB data.

### Assumptions:
- Airbnb rentals are equivalent to the general vacation rental statistics.	
- Rental activity is assumed through the number of reviews in the last 12 months.	
- Properties with no reviews in the last 12 months were considered inactive	
- Super luxury listings with prices greater than $1,956.00 were filtered from the analysis, 1% outlier	
- Extremely low-priced listings of less than $82 were filtered from the analysis, 1% outlier	
- Superhosts properties reflect prices of properties the investor will purchase	

### Process:
I first explored, filtered, and cleaned the data.
Then I created aggregations and pivot tables to determine the type of properties that should be targeted.
I performed calculations, pivot tables and charts to determine occupancy and estimated revenue.
I went a step further and chose to do an optional analysis to determine what attributes are important for a vacation rental.
Lastly I finalized formatting for the client's readability.

### Findings:
1. The top 10 attractive neighborhoods for vacation rentals are as follows: Hell's Kitchen, Lower East Side, Harlem, Midtown, Upper West Side, Chelsea, East Village, East Harlem, West Village, Nolita.			
2. The most popular vacation rental size is 1 bedroom overall. Lower East Side has the largest 1 bedroom demand. 2 bedrooms in Hell's Kitchen and Studio’s in Midtown are also desirable.			
3. Saturday's have the highest occupancy rate out of the week.			
4. Estimated revenue for similar properties to recommendations is $79,945.70.			
5. Superhosts can charge higher prices, statistically significant.			
6. Instant bookings do have higher occupancy rates, statistically significant.			
7. Building with doormen get better reviews, statistically significant.			
8. Hosts can charge higher prices for higher review ratings.
