# 01-Otodom-Polish-Housing-Market-Project

This project involves conducting web scraping on the Otodom website to extract detailed property information. This includes location, price, and property features. 
The scraped data was then formatted into JSON for standardized handling and compatibility. This semi-structured JSON data was staged in Snowflake’s staging area, where further data manipulation processes took place, including flattening hierarchical data to align with Snowflake's tabular schema requirements before loading into a structured table.

Following the data loading, two essential transformations were performed:

The location column, initially captured as geographic coordinates, was transformed into full, readable addresses using reverse geocoding. This enhancement provided more user-friendly location information for analytics and reporting.
The description column, initially in Polish, was translated into English to broaden accessibility and improve usability for an international audience.
This workflow enabled a smooth transition from raw web data to a refined, structured dataset ready for analysis and reporting

