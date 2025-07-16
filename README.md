# Air Pollution Data Cleaning and Analysis (UK, 2019–2024)

A data cleaning and exploratory data analysis (EDA) project on UK air pollution data sourced from the OpenAQ API. The project focuses on transforming raw environmental data into structured, analyzable formats and visualizing key patterns across time, location, and pollutant type.

## 📊 Project Overview  
- **Data Source:** OpenAQ API (2019–2024)  
- **Records Collected:** 90,000+  
- **Pollutants Tracked:** PM2.5, PM10, NO2, CO, SO2, O3  

---

## ⚙️ Features  

### 🗂️ Data Sourcing  
- API requests made using `requests` with authenticated headers.  
- Custom query parameters for date range, pollutants, and location (UK).  
- Data saved in JSON format for reproducibility.  

### 🧹 Data Cleaning & Preparation  
- Removal of duplicates and handling of missing values.  
- Standardized city names using regex and string manipulation.  
- Parsed date and time into separate `date` and `hour` fields.  
- Cleaned dataset saved in JSON for downstream tasks.  

### 🛠️ Feature Engineering  
- Pollution level categorization (Low, Moderate, High) based on pollutant-specific thresholds.  
- Time of day classification (Morning, Afternoon, Evening, Night).  
- Geographic region mapping based on latitude and longitude coordinates within the UK.  

### 📈 Visualization & Insights  
- Visualized pollution levels by category, region, and time using Matplotlib.  
- Stacked bar charts to show pollution indicators across regions.  
- Scatter and line plots to reveal trends in pollution data.  

---

## Usage  

1. Run the Python scripts to fetch, clean, and process the data.  
2. Visualize the output using provided plotting functions.  

---

## Technologies Used  

- Python  
- Requests  
- Pandas  
- Matplotlib  










