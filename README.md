Air Pollution Data Cleaning and Analysis (UK, 2019–2024)
This project focuses on data cleaning and exploratory data analysis (EDA) of UK air pollution datasets retrieved from the OpenAQ API. The goal is to transform raw environmental data into clean, structured datasets ready for analysis, using advanced preprocessing techniques and insightful visualizations.

Key Features
Data Sourcing
Retrieved 90,000 records from the OpenAQ API using authenticated requests.

Collected data on six key pollutants: PM2.5, PM10, NO2, CO, SO2, O3.

Saved raw and cleaned datasets in JSON format for reproducibility.

Data Cleaning & Preparation
Removed duplicates and handled missing or null values.

Extracted and standardized city names using regex and string operations.

Parsed timestamps into separate date and hour fields using datetime parsing.

Reordered columns for consistency and readability.

Feature Engineering
Categorized pollution levels based on pollutant thresholds.

Classified records by time of day (morning, afternoon, evening, night).

Mapped geographic coordinates into UK regions (e.g., SE, SW, WM, NW, etc.).

Visualization & Insights
Generated visual summaries using Matplotlib to identify patterns in pollution levels, regional differences, and time-based trends.

Highlighted average pollutant levels per region and pollution category distributions.

Let me know if you want this in Markdown format or want me to include example plots and dataset summaries!










