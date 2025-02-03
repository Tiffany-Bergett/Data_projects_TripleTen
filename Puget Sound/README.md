# File Title: Puget Sound Water Quality

This was a Code Jam **Competition** project that I worked on after the TripleTen Business Intelligence Analytics Program. It was a light-hearted team project designed to showcase my Tableau and Collaboration skills. The purpose was to create a visually compelling story from a provided dataset **in 4 days with Tableau and collaboration**.

This project highlights my strengths in:<br>
Data Analysis & Exploration (understanding and manipulating data)<br>
Data Visualization (creating clear and informative visuals)<be>
Tableau Calculations, Parameters, and Sets<br>
Communication & Teamwork (conveying insights and collaborating effectively)

[<img src="https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Images/Puget%20Sound.png">](https://public.tableau.com/views/PugetSound-WaterQuality/Presentation?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

YouTube LIVE recording of the entire competition with host Q&A can be found <a href='https://www.youtube.com/live/DWhX2HIf83Q' target=_blank><u>here</u>.</a>
The Tableau Public page can be found <a href='https://public.tableau.com/views/PugetSound-WaterQuality/Presentation?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link' target=_blank><u>here</u>.</a>.

### Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Join & Initial Filters.png](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Puget%20Sound/Join%20%26%20Initial%20Filters.png) | Table Joining caused row limit constraints; list of initial filters used to reduce file size. |
| 2 | [Puget Sound - Water Quality.zip](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Puget%20Sound/Puget%20Sound%20-%20Water%20Quality.zip) | A downloadable Zip with a PDF copy of the entire Tableau workbook. |
| 3 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 4 | [Requirements.txt](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Puget%20Sound/Requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen. |
| 5 | [WLRD_Sites_20240906.csv](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/blob/main/Puget%20Sound/WLRD_Sites_20240906.csv) | Additional spreadsheet file in CSV format found from the county website to provide GPS coordinates of original data's areas. |

### Table of Contents for README
| Section Title | Description |
| ----------- |----------- |
| [Description](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/Puget%20Sound#description) | Describes the final product's purpose, software, format, and included visuals. |
| [Process](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/Puget%20Sound#process) | Describes the process, including tools or tech used. |
| [Data](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/Puget%20Sound#data) | Describes the data source, including files, tables, and fields. |
| [Assumptions](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/Puget%20Sound#assumptions) | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| [Findings](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/Puget%20Sound#findings) | Insights learned from the data analysis. |
| [Recommendations](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/Puget%20Sound#results) | Recommended direction for the stakeholders based on the final analysis. |
| [Notes](https://github.com/Tiffany-Bergett/Data_projects_TripleTen/tree/main/Puget%20Sound#notes) | Lists any special requests from the reviews or stakeholders unique to this project. |

#### Description:
- 1 Tableau Story made from 4 Dashboards and 11 visuals
- Includes parameters, calculations, sets, and a final presentation of the Tableau Story.

#### Process:
**First**, We held a *Discord* Call to organize our team details and technical details on how to best seamlessly share the work between time zones and workstations.<br>
**Then**, each team member explored, filtered, and cleaned the data for EDA.<br>
**Next**, we used *Google Docs* to create a LIVE Note to create a decomposition. While keeping in constant connection via Discord our research collaboration led to the hypothesis and story plan.<br>
**Lastly**, We presented our assigned portions of the presentation on a *LIVE YouTube* presentation.<br>

#### Data
The data was one .csv file provided by TripleTen, originally sourced from [Kaggle](https://www.kaggle.com/datasets/sukhmandeepsinghbrar/water-quality) and one .csv file joined from Kings County Website:
- `'water-quality-1.csv'`: This dataset contains water quality samples collected from Puget Sound, lakes, and streams in the region. Crossed-out fields were not included in the analysis due to time constraints.
    - `'Sample ID'`: Unique identifier for each sample taken.
    - ~`'Grab ID'`: Identifier for the specific grab instance associated with the sample.~
    - ~`'Profile ID'`: Identifier for the profile associated with the sample.~
    - ~`'Sample Number'`: Sequential number assigned to each sample.~
    - `'Collect DateTime'`: Date and time when the sample was collected.
    - `'Depth (m)'`: Depth at which the sample was collected, measured in meters.
    - `'Site Type'`: The type of site where the sample was collected (e.g., river, lake, well).
    - `'Area'`: Geographic area or region where the sample was collected.
    - ~`'Locator'`: Locator information indicating the precise location of the sample.~
    - ~`'Site'`: Specific site or location where the sample was collected.~
    - `'Parameter'`: The parameter measured or analyzed in the sample (e.g., pH, dissolved oxygen).
    - `'Value'`: Value of the parameter measured in the sample.
    - `'Units'`: Units of measurement for the parameter value.
    - ~`'QualityId'`: Identifier indicating the quality of the data.~
    - ~`'Lab Qualifier'`: A Qualifier assigned by the laboratory indicating any special conditions or characteristics of the sample.~
    - ~`'MDL (Method Detection Limit)'`: Method detection limit for the parameter.~
    - ~`'RDL (Reporting Detection Limit)'`: Reporting detection limit for the parameter.~
    - ~`'Text Value'`: Textual representation of the parameter value.~
    - ~`'Sample Info'`: Additional information related to the sample.~
    - ~`'Steward Note'`: Notes or comments provided by the data steward.~
    - ~`'Replicates'`: Number of replicates taken for the sample.~
    - ~`'Replicate Of'`: Identifier indicating the sample of which this is a replicate.~
    - ~`'Method'`: Method used for analysis or measurement.~
    - `'Date Analyzed'`: The date when the sample was analyzed.
    - ~`'Data Source'`: Source of the data.~
- `'WLRD_Sites_20240906.csv'`: Additional table to provide GPS coordinated for collection areas.

#### Assumptions:
- Rows with vital fields shown as NULL were excluded.
- Different Units can be shown on one visual if the values are not directly compared.
- Similar parameters(field) can be grouped together.

#### Findings:
- Marine Offshores had the highest Densities and Light measurements.
- Large Lakes had the highest Chlorophyll, hardness, and oxygen levels.
- Streams and Rivers had the highest bacteria levels.
- Marine Intertidal zones and Swimming Beaches had their highest levels of bacteria, not as high as streams and rivers.
- Chlorophyll spiked in 2007 but returned to baseline in 2012, suggesting a trend of increase over time.
- Light measurements started spiking and returning to baseline in 2002 several times, suggesting a trend of increase over time.
- **Bacteria had higher levels in the 70's and 80's, suggesting a trend of decrease over time.**
- Time of day plays a role in measurement values, especially with light measurements, *it is recommended to take samples at the same time every day for future samples*.
- Sample integrity is negatively affected by the difference in time of collection and time of analysis, *it is recommended to analyze samples immediately*.
- Turbidity, Dissolved Oxygen, and Salinity samples were most often collected at farther depths than other samples.
- Depth of collection has a positive correlation with Salinity and Nitrogen while having a negative correlation with Light, Oxygen, and Bacteria.
- **The waters around Puget Sound are not Drinkable**.
- Most Bacteria levels decrease throughout the day, the lowest point is when the sun is highest.

#### Results:
**Collaborative Brainstorming**: I effectively worked with a team to identify interesting stories within the provided datasets. <br>
**Data-Driven Storytelling**: I focused on insights supported by data, ensuring clear and ethical use of information.<br>
**Visual Storytelling**: I created unique data visualizations that complemented the narrative and communicated key points effectively.<br>
**Presentation Skills**: I participated in crafting a clear and concise presentation that showcased our project's findings within a limited timeframe.

#### Notes:
Our 3rd member dropped out of the competition after the 2nd day due to work time constraints.
