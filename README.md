
## ✈️ Flight Data Analysis and Reporting
📌 Project Title
Flight Operations and Revenue Analysis using Relational Database Schema

# 📊 Overview
This project involves analyzing a relational airline database to derive actionable insights related to flight operations, aircraft efficiency, passenger behavior, and revenue performance. It focuses on writing SQL queries on a well-defined schema to extract metrics crucial to airline management and operations.

# 📁 Data Description
The dataset is composed of multiple interrelated tables representing key airline operations. These tables were created and populated using SQL scripts provided in the Airlines_schema_scripts.zip archive.

# Schema Entities:

AIRCRAFTS_DATA: Specifications of aircraft, such as model and range.
AIRPORTS_DATA: Information about airport locations and localized names.
FLIGHTS: Flight schedules, statuses, and links to airports and aircraft.
SEATS: Detailed seat-level information including fare classes.
BOOKINGS & TICKETS: Passenger bookings and individual ticket records.
TICKET_FLIGHTS: Junction table connecting tickets to flights and fares.
BOARDING_PASSES: Boarding order and seat assignment for each passenger.
# 🧹 Data Cleaning & Preparation
The data was loaded using the provided SQL scripts:

airlines_data_tickets.sql
airlines_data_aircrafts.sql
airlines_data_airports.sql
airlines_data_boarding_passes.sql
airlines_data_bookings.sql
airlines_data_flights.sql
airlines_data_seats.sql
airlines_data_ticket_flights.sql
The SQL scripts ensured data consistency and referential integrity. ER diagram visualization was used to understand table relationships and design efficient queries.

# 📈 Analysis Summary
The project covers 14 business-critical SQL analyses, including:

# Task Insight
1	Calculate average delay in departures for delayed flights	Determine average delay duration for late departures
2	List flight frequency by aircraft	Assess aircraft utilization
3	Calculate total revenue per flight	Analyze profitability of each flight
4	Analyze average boarding number per flight	Identify boarding pattern trends
5	Determine occupancy & fare conditions per aircraft	Track seat utilization and fare distribution
6	Identify top 3 revenue-generating flights	Highlight the most profitable flights
7	Average flight duration by aircraft model	Compare efficiency among different aircraft types
8	Flight count per airport	Measure airport activity levels
9	Daily booking trends	Visualize booking frequency and revenue over time
10	Frequent routes analysis	Identify most common origin–destination pairs
11	Passenger boarding summary per flight	Count number of passengers per flight
12	Average boarding number per flight	Analyze passenger boarding strategy
13	Seat occupancy rate per flight	Calculate load factor per flight
14	Total spend per passenger	Aggregate spending behavior of passengers
# 🛠️ Tools & Technologies
MySQL Workbench – Data loading, querying, and visualization
SQL – Data manipulation and analysis
ER Diagrams – Schema understanding
