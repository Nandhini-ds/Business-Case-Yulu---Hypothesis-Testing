# Business-Case-Yulu---Hypothesis-Testing

# About Yulu
Yulu is India’s leading micro-mobility service provider, which offers unique vehicles for the daily commute. Starting off as a mission to eliminate traffic congestion in India, Yulu provides the safest commute solution through a user-friendly mobile app to enable shared, solo and sustainable commuting.

Yulu zones are located at all the appropriate locations (including metro stations, bus stands, office spaces, residential areas, corporate offices, etc) to make those first and last miles smooth, affordable, and convenient!

Yulu has recently suffered considerable dips in its revenues. They have contracted a consulting company to understand the factors on which the demand for these shared electric cycles depends. Specifically, they want to understand the factors affecting the demand for these shared electric cycles in the Indian market.

# How you can help here?
The company wants to know:
Which variables are significant in predicting the demand for shared electric cycles in the Indian market?
How well those variables describe the electric cycle demands

# Objective
The objective of this analysis is to identify and understand how various factors such as seasonality, weather conditions, holidays, working days, and other environmental factors affect the usage and rental patterns of shared electric cycles. This insight will help stakeholders optimize operations, marketing strategies, and resource allocation to better meet consumer needs and increase adoption of shared electric cycles.

# Tools Used
* Python
* Python Libraries and stats module

# Project Type
Basis EDA and Hypothesis testing

# About Data
| Column      | Description                                                                                   |
|------------|-----------------------------------------------------------------------------------------------|
| datetime   | Date and time of the record                                                                    |
| season     | Season (1: spring, 2: summer, 3: fall, 4: winter)                                             |
| holiday    | Whether the day is a holiday or not (from [DCHR holiday schedule](http://dchr.dc.gov/page/holiday-schedule)) |
| workingday | 1 if day is neither weekend nor holiday, otherwise 0                                           |
| weather    | 1: Clear/Few clouds/partly cloudy<br>2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist<br>3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds<br>4: Heavy Rain + Ice Pellets + Thunderstorm + Mist, Snow + Fog |
| temp       | Temperature in Celsius                                                                         |
| atemp      | Feeling temperature in Celsius                                                                 |
| humidity   | Humidity                                                                                       |
| windspeed  | Wind speed                                                                                     |
| casual     | Count of casual users                                                                          |
| registered | Count of registered users                                                                      |
| count      | Total count of rental bikes (casual + registered)   

# Solution Approach
* Data Collection - Source and format of the dataset.
* Data Cleaning & Preprocessing - Handling missing values, data type conversion and formatting.
* Exploratory Data Analysis (EDA) - Visualizations, identifying patterns, and performing hypothesis testing
* Insights -  key take away from the analysis.
# Recommendations
#Season

No of bikes rented durin spring season is low, So yulu can provide price deduction, discount or ofers to increse the count.

The demand for yulu bikes peaks during fall and summer seasons, Therefore they should increase the supply of bikes to meet this rising demand.

Yulu would provide bike equipped with rain covers during raining season.

#Weather

Yulu should stock a higher number of electric cycles during clear weather to meet increased demand.

To boost rentals during misty (light fog) and winter conditions, Yulu can invest in bikes equipped with high-intensity LED lights, reflective stickers and anti-slip tires to improve safety and rider confidence.

#Workingday

Offering flexible rental plans for daily commuters to make motorcycles more accessible.

Partnering with companies to provide motorcycles for employee commutes at discounted rates.

Rent motorcycles with ready-made travel routes for holiday trips. Riders get maps, tips, and scenic ride suggestions for a great experience.

Yulu can bring limitted time discounts and cash back offers during holidays to attrack more users.

#Environmental factors

During days with lower humidity, lower windspeed, and moderate temperature, Yulu should ensure adequate availability of bikes, as these conditions are associated with higher rental demand.

Fewer bikes are rented late at night, so Yulu can offer discounts or special deals during those hours to encourage more people to rent. Yulu can target night shift workers, by offering exclusive late-night deals or discounts to encourage more rentals during those hours.

Yulu can utilize low-demand periods to carry out regular maintenance, servicing, and safety checks on their electric cycles. This ensures that bikes remain in optimal condition during peak demand hours and improves user satisfaction and reliability.
 
