🌦️ Weather Forecast Dashboard using Power BI & WeatherAPI
📌 Project Overview

This project is an interactive weather forecast dashboard built using Power BI and real-time data from WeatherAPI.
The dashboard provides weather insights such as temperature trends, air quality metrics, and forecast conditions for multiple cities.

The report includes Light Mode and Dark Mode views, interactive slicers, and dynamic visual elements designed for clear storytelling and usability.

🎯 Objectives

Connect Power BI to a REST API

Transform nested JSON data using Power Query

Apply data modeling best practices

Use DAX for calculations and conditional formatting

Design a clean and interactive dashboard

Implement Light/Dark mode navigation

📊 Features

🌍 City-based weather forecasting

📅 Daily forecast visualization

🌡️ Temperature metrics (min, max, average)

🌬️ Air Quality Index (PM10, PM2.5, NO₂, O₃)

🎨 Conditional color formatting for AQI levels

🔄 Interactive slicers for city and date selection

🌗 Light Mode & Dark Mode pages with navigation buttons

🛠️ Tools & Technologies

Power BI Desktop

WeatherAPI

Power Query (M Language)

DAX (Data Analysis Expressions)

🔗 Data Source

Weather data is fetched from the WeatherAPI Forecast endpoint, which provides:

Location details

Daily forecast data

Weather conditions

Air quality metrics

Astronomy data (sunrise, sunset, moon phase)

The API response is received in JSON format and transformed into a tabular structure for analysis.

🔄 Data Transformation

Key transformation steps include:

Expanding nested JSON records and lists

Creating one row per city per forecast day

Converting text fields to numeric data types

Renaming columns for clarity

Creating date-based fields for sorting and filtering

🧮 DAX Highlights

AQI-based color measures for conditional formatting

Weekday sorting using numeric weekday columns

Measures to handle dynamic filtering and context

🎨 Dashboard Design

Two separate pages for Light Mode and Dark Mode

Identical layout across both pages for consistency

Circular navigation buttons for mode switching

Synced slicers across pages

Clean presentation optimized for screen recording

🎥 Demo

A live screen recording of the dashboard is used for demonstration and sharing (e.g., LinkedIn).
Recording is done in Full Screen mode to ensure a clean, distraction-free UI.