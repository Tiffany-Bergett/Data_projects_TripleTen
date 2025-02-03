# File Title: Manhattan Vacation Rental Market Project

This is VERSION 2 of the first project I worked on in the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase what I have learned about Advanced Spreadsheets. This project is about analyzing Airbnb listings in Manhattan, NYC to help a client decide what type of vacation rental property to invest in.

[<img src="https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Images/Manhatten%20Vacations.png">](https://www.loom.com/share/5dcca9877f544883869566b1e8468505?sid=e6021781-b845-461c-b132-2b099657b656)


Loom Video Overview can be found <a href='https://www.loom.com/share/5dcca9877f544883869566b1e8468505?sid=e6021781-b845-461c-b132-2b099657b656' target=_blank><u>here</u>.</a>
Projects Google Speadsheet can be found <a href='https://docs.google.com/spreadsheets/d/1dNFTH1PFCCO9aLPLjjbvPxlqKe1Hkd2Nenf2dFyWxe0/edit?usp=sharing' target=_blank><u>here</u>.</a>

### Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Manhattan Vacation Rental .pdf](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Manhattan%20Vacation%20Rental%20Market%20Project/Manhattan%20Vacation%20Rental%20Market%20.pdf) | The downloadable pdf file of the actual project. |
| 2 | [Project Rubric V2.pdf](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Manhattan%20Vacation%20Rental%20Market%20Project/Project%20Rubric%20V2.pdf) | A .PDF file with the provided template for grading. |
| 3 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 4 | [Requirements.txt](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Manhattan%20Vacation%20Rental%20Market%20Project/Requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen. |
| 5 | [ReviewerGrade1.png](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Manhattan%20Vacation%20Rental%20Market%20Project/ReviewerGrade1.png) | This is a .png file showing the comments left by my project reviewer. |

### Table of Contents for README
| Section Title | Description |
| ----------- |----------- |
| [Description](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/Manhattan%20Vacation%20Rental%20Market%20Project#description) | Describes the final product's purpose, software, format, and included visuals. |
| [Process](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/Manhattan%20Vacation%20Rental%20Market%20Project#process) | Describes the process, including tools or tech used. |
| [Data](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/Manhattan%20Vacation%20Rental%20Market%20Project#data) | Describes the source of data, including files, tables, and fields. |
| [Assumptions](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/Manhattan%20Vacation%20Rental%20Market%20Project#assumptions) | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| [Findings & Recommendations](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/Manhattan%20Vacation%20Rental%20Market%20Project#findings-and-recommendations) | Insights and suggested considerations learned from the data analysis. |

#### Description:
- 17 page spreadsheet
- Includes organizational tabs, raw data (Hidden), processed data, data analysis, pivot tables, and bar charts.

#### Process:
1) **Data Preparation**: *Filtering* techniques were used to identify and clean inconsistencies within the Airbnb data. Irrelevant columns were hidden to maintain a focused analysis. Key functions such as PROPER, TRIM, IF, ISNUMBER, FIND, ROUND, SUMIF, VLOOKUP, CHOOSE, and WEEKDAY were employed for data tidying.
2) **Neighborhood Analysis**: Identify the top-performing neighborhoods based on review frequency via *Pivot Table*.
3) **Property Size Analysis**: Determine the optimal property sizes for each neighborhoodvia *Pivot Table* showcased with *conditional formatting*.
4) **Revenue Analysis**: Calculate estimated annual revenue for the most attractive listings.
5) **Additional Optional Analysis**: Perform Analysis through *Pivot Tables* for occupancy rates by day, price by super host status, check-in ratings by use of doormen, and price by review ratings.
6) **Data Visualization**: Create clear and informative *visualizations* (charts) to present findings.
7) **Formatting and Organization**: Ensure your analysis is well-formatted for ease of readability.
8) **Documentation**: Create organizational sheets like an executive summary, table of contents, assumptions log, and change log.
 
#### Data
The data was one Google spreadsheet file provided by TripleTen, Copy can be found [HERE](https://docs.google.com/spreadsheets/d/1Z7KNEYs_YtQP57mWXRddPGAI3Sk-tPzLnCsdysCSw_c/edit?usp=sharing):
- `'nyc_airbnb_data.csv'`: each row corresponds to one listing on Airbnb in September 2022
    - `'data_dictionary'`: summary of field titles seen in the file and its data type
    - `'listings'`: uniquely listings available with all available data
    - `'calendar'`: listings with upcoming availabilities and date-type data

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

#### Findings and Recommendations:
1. The top recommended neighborhoods for vacation rentals are as follows: Lower East Side, Hell's Kitchen, Harlem, Midtown, Upper West Side, Chelsea, East Village, East Harlem, West Village, Upper East Side.	
2. The top rental size is 1 bedroom overall. Lower East Side properties should have 1-bedrooms to meet demand. Hell's Kitchen prefers 2 bedrooms and Midtown prefers Studio.	
3. The estimated annual revenue based on top listing characteristics is $69,957.	
4. Fridays have the highest occupancy rate out of the week, average occupancy is 86.4%.	
5. Instant bookings do have higher occupancy rates, statistically significant, average is 52%.	
6. Superhosts can charge higher prices, statistically significant, on average $334.	
7. Building with doormen gets better reviews, statistically significant, by 0.05 stars.	
8. Hosts can charge higher prices for higher review ratings.	

