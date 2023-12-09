# File Title: The Zuber Database

This was my second project I worked on in the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase what I have learned in SQL.

Loom Video Screencast can be found <a href='https://www.loom.com/share/c52200c4a60f4bb89bee18ccfaee4c34?sid=f7aa58e5-1c9b-489b-a4c3-4ce111b59b9d' target=_blank><u>here</u>.</a>

### Data
- A database with info on taxi rides in Chicago provided by TripleTen.
- `'neighborhoods'` table: data on city neighborhoods
    - `'name'`: name of the neighborhood
    - `'neighborhood_id'`: neighborhood code
- `'cabs'` table: data on taxis
    - `'cab_id'`: vehicle code
    - `'vehicle_id'`: the vehicle's technical ID
    - `'company_name'`: the company that owns the vehicle
- `'trips'` table: data on rides
    - `'trip_id'`: ride code
    - `'cab_id'`: code of the vehicle operating the ride
    - `'start_ts'`: date and time of the beginning of the ride (time rounded to the hour)
    - `'end_ts'`: date and time of the end of the ride (time rounded to the hour)
    - `'duration_seconds'`: ride duration in seconds
    - `'distance_miles'`: ride distance in miles
    - `'pickup_location_id'`: pickup neighborhood code
    - `'dropoff_location_id'`: dropoff neighborhood code
- `'weather_records'` table: data on weather
    - `'record_id'`: weather record code
    - `'ts'`: record date and time (time rounded to the hour)
    - `'temperature'`: temperature when the record was taken
    - `'description'`: brief description of weather conditions, e.g. "light rain" or "scattered clouds"

### Description:
- 6 Step SQL query.
- Exploratory data analysis and investigation whether the duration of rides from the Loop to O'Hare International Airport changes on rainy Saturdays.
- Purpose was to find patterns in the available information from competitors to understand passenger preferences and the impact of external factors on rides.

### Assumptions:
- There isn't a direct connection between the trips table and weather_records table in the database.
- neighborhood_id is the Primary Key for the neighborhoods table.
- cab_id is the Primary Key for the cabs table.
- trip_id is the Primary Key for the trips table.
- record_id is the Primary Key for the weather_records table.

### Process:
Analyzed taxi rides by company for specific dates, sorting by trip count.
Analyzed rides for companies containing specific keywords, grouping by company name.
Retrieved neighborhood IDs for O'Hare and Loop.
Categorized weather conditions by hour.
Retrieved Saturday rides from Loop to O'Hare, including weather and duration.
Sorted the results.
