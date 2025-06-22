## ✈️ Flight Data Analysis & Reporting – MySQL Project
📌 Project Title
Flight Operations and Revenue Analysis using Relational Database Schema
> 🧠 A Structured SQL Project for Airline Operations Insights  
> 📊 Built using MySQL to analyze aircraft usage, revenue, punctuality, passenger behavior, and booking trends

---

## 📌 Project Overview

This project aims to uncover **operational insights** from a relational airline dataset using **MySQL queries**. It spans across key functions such as flight punctuality, aircraft utilization, revenue analytics, booking behavior, and seating occupancy—providing strategic input for airline operations and revenue teams.

---

## 🎯 Objectives

- ✈️ **Flight Performance** – Delay analysis and punctuality tracking  
- 🛩️ **Aircraft Utilization** – Flights operated, average durations  
- 💸 **Revenue Tracking** – Revenue per flight, per passenger, per booking  
- 🧑‍🤝‍🧑 **Passenger Behavior** – Boarding patterns and segment-based insights  
- 📅 **Temporal Trends** – Booking and revenue variations over time

---

## 🧱 Database Schema Overview

| Table               | Description                                      |
|---------------------|--------------------------------------------------|
| `flights`           | Flight schedules, aircraft, airport references   |
| `aircrafts`         | Aircraft specs (model, code)                     |
| `seats`             | Seat count and fare conditions                   |
| `airports`          | Airport locations and metadata                   |
| `bookings`          | Booking-level records                            |
| `tickets`           | Passenger-level ticket information               |
| `ticket_flights`    | Mapping of tickets to flights with revenue       |
| `boarding_passes`   | Boarding number details by flight                |

---

## 🔍 Key SQL Queries & Insights

| 🔢 Query No. | Insight Generated |
|-------------|-------------------|
| 1 | Average delay for late departures |
| 2 | Aircraft usage frequency & flight durations |
| 3 | Total revenue per flight |
| 4 | Boarding patterns per flight |
| 5 | Occupancy rate per aircraft |
| 6 | Top 3 revenue-generating flights |
| 7 | Avg. flight duration by aircraft model |
| 8 | Flights per departure airport |
| 9 | Flights per arrival airport |
| 10 | Daily booking and revenue trends |
| 11 | Most frequent route pairs |
| 12 | Passenger boarding summary per flight |
| 13 | Avg. boarding number analysis |
| 14 | Seat occupancy rate per flight |
| 15 | Passenger-wise total spend and ticket count |

---

## 🧠 Techniques & Functions Used

- `JOIN`, `GROUP BY`, `ORDER BY`, `LIMIT`
- Aggregates: `AVG`, `COUNT`, `SUM`, `ROUND`
- Date/Time: `TIMESTAMPDIFF`, `DATEDIFF`, `DATE()`
- Aliasing and Subqueries
- Multi-table relational operations

---

## 📁 Folder Structure

```bash
📁 Flight-Data-SQL-Project/
├── 📄 Flight Data Analysis and Reporting.sql        # Main SQL queries
├── 📄 Flight Data Analysis and Reporting_Problem_Statement.pdf  # Task statement
└── 📄 README.md                                     # Project documentation

