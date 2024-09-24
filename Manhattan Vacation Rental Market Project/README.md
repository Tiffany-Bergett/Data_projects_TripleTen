:warning: :construction: PROJECT PAGE UNDER CONSTRUCTION :construction: :warning:

# File Title: Manhattan Vacation Rental Market Project

This is VERSION 2 of the first project I worked on in the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase what I have learned about Advanced Spreadsheets. This project is about analyzing Airbnb listings in Manhattan, NYC to help a client decide what type of vacation rental property to invest in.

[<img src="https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Images/Manhattan%20Project.png">](https://docs.google.com/spreadsheets/d/1dNFTH1PFCCO9aLPLjjbvPxlqKe1Hkd2Nenf2dFyWxe0/edit?usp=sharing)


Loom Video Overview can be found <a href='NEW LINK STILL NEEDED' target=_blank><u>here</u>.</a>
Projects Google Speadsheet can be found <a href='https://docs.google.com/spreadsheets/d/1dNFTH1PFCCO9aLPLjjbvPxlqKe1Hkd2Nenf2dFyWxe0/edit?usp=sharing' target=_blank><u>here</u>.</a>

### Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Manhattan Vacation Rental Market Project.xlsx](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Manhattan%20Vacation%20Rental%20Market%20Project/Manhattan%20Vacation%20Rental%20Market%20Project.xlsx) | The downloadable excel workbook file of the actual project. |
| 2 | [Project Rubric V2.pdf](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Manhattan%20Vacation%20Rental%20Market%20Project/Project%20Rubric%20V2.pdf) | A .PDF file with the provided template for grading. |
| 3 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 4 | [Requirements.txt](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Manhattan%20Vacation%20Rental%20Market%20Project/Requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen. |
| 5 | [ReviewerGrade1.png](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Manhattan%20Vacation%20Rental%20Market%20Project/ReviewerGrade1.png) | This is a .png file showing the comments left by my project reviewer. |
| 6 | [nyc_airbnb_data.csv](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Manhattan%20Vacation%20Rental%20Market%20Project/nyc_airbnb_data.csv) | The original data file provided by TripleTen that was used in the analysis of this project. |

### Table of Contents for README
| Section Title | Description |
| ----------- |----------- |
| DATA | Describes the source of data, included files, tables, and fields. |
| Description | Describes the final product's purpose, software, format, and included visuals. |
| Assumptions | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Process | A general outline of how this project formed from start to finish. |
| Findings | Insights learned from the data analysis. |

#### Data
The data was one Google spreadsheet file provided by TripleTen:
- `'nyc_airbnb_data.csv'`: each row corresponds to one listing on AirBnB in September 2022
    - `'data_dictionary'`: summary of field titles seen in the file and its data type
    - `'listings'`: uniquely listings available with all available data
    - `'calendar'`: listings with upcoming availabilities and date-type data

#### Description:
- 17 page spreadsheet
- Includes organizational tabs, raw data (Hidden), processed data, data analysis, pivot tables, and bar charts.

#### Assumptions:
-Airbnb rentals are equivalent to the general short-term vacation rental market.
-Only properties with a Minimum night requirement of 7 days or less were considered. 
-Properties with no reviews in the last 12 months were considered inactive.
-Reviews reflect rental frequency, we used "number_of_reviews_ltm" to measure a listing's attractiveness.
-Super luxury listings with prices greater than $1,321.21 were filtered from the analysis, 1% outlier.
-Extremely low-priced listings of less than $85.28 were filtered from the analysis, 1% outlier.
-Estimated Annual Revenue can be calculated by comparing averages for top listings.
-"Building staff" equates to a Doorman
-A listing of 9k can be excluded when examining price/review due to it being an extreme outlier.

#### Process:
I first explored, filtered, and cleaned the data.
Then I created aggregations and pivot tables to determine the type of properties that should be targeted.
I performed calculations, pivot tables, and charts to determine occupancy and estimated revenue.
I went a step further and chose to do an optional analysis to determine what attributes are important for a vacation rental.
Lastly, I finalized the formatting for the client's readability.

#### Findings:
1. The top 10 attractive neighborhoods for vacation rentals are as follows: Lower East Side, Hell's Kitchen, Harlem, Midtown, Upper West Side, Chelsea, East Village, East Harlem, West Village, Upper East Side.	
2. The most popular vacation rental size is 1 bedroom overall. Lower East Side has the largest 1-bedroom demand. Hell's Kitchen prefers 2 bedrooms and Midtown prefers Studio.	
3. The estimated annual revenue based on top listing characteristics is $69,957.	
4. Fridays have the highest occupancy rate out of the week, average occupancy is 86.4%.	
5. Instant bookings do have higher occupancy rates, statistically significant, average is 52%.	
6. Superhosts can charge higher prices, statistically significant, on average $334.	
7. Building with doormen gets better reviews, statistically significant, by 0.05 stars.	
8. Hosts can charge higher prices for higher review ratings.	

