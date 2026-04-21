# Exploratory Data Analysis of Melbourne Housing Prices

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on Melbourne housing data to understand property price patterns, key influencing factors and market trends.

The dataset includes **13,581 property records and 21 features** covering location, property characteristics, and sales details.

The main goal is to extract meaningful insights that can help buyers, sellers and investors understand the Melbourne real estate market.

---

##  Objectives

- Understand the structure and quality of the dataset  
- Identify missing values, duplicates, and inconsistencies  
- Analyze relationships between features and property prices  
- Study location-based and time-based price trends  
- Discover key factors influencing housing prices  

---

##  Dataset Information

**Source:** Kaggle – Melbourne Housing Snapshot  
https://www.kaggle.com/datasets/dansbecker/melbourne-housing-snapshot  

**Size:** 13,581 rows × 21 columns  

### Feature Types:
- **Numerical:** Rooms, Price, Distance, Bathroom, Car, Landsize, BuildingArea, etc.  
- **Categorical:** Suburb, Type, Method, SellerG, RegionName  
- **Geographical:** Latitude, Longitude  
- **Date:** Date of sale  
- **Descriptive:** Address, Postcode  

---

##  Data Cleaning & Preprocessing

- Converted `Date` column to datetime format  
- Handled incorrect data types (e.g., Postcode, YearBuilt)  
- Checked and treated missing values  
- Identified and removed duplicate records  
- Detected outliers in Price, Landsize, and YearBuilt  

---

## Key Insights

###  General Trends
- Average property price: **~1,075,962**
- Price range: **85,000 to 9,000,000**
- Most properties fall between **500,000 – 1,300,000**
- Majority of homes are located **6–13 km from CBD**

###  Property Type Analysis
- Houses dominate the market (**~9,439 records**)  
- Units are the most affordable property type  
- Townhouses fall in between houses and units  

###  Location Insights
- Closest properties have highest prices (~1.15M average)  
- Far locations are significantly cheaper (~630K average)  
- Top expensive suburbs: **Kooyong, Canterbury (~2.18M avg)**  
- Most expensive region: **Southern Metropolitan (~1.37M avg)**  

###  Feature Relationships
- Strong correlation: **Rooms ↔ Bedrooms (0.94)**  
- Price increases with:
  - Rooms (0.50)
  - Bedrooms (0.48)
  - Bathrooms (0.47)  
- Distance has a negative effect on price (-0.16)  
- Landsize and Car show weak correlation  

###  Market Trend
- Sales increased from **2016 → 2017**
- Average prices remained stable with slight decrease in 2017  

---

##  Observed Anomalies

- Extremely high prices (up to 9M)  
- Very small and very large land sizes (30–2000 sq.m)  
- YearBuilt inconsistency (e.g. invalid values like 1196)  
- Duplicate property transaction detected  

---

##  Conclusions

- **Location is the strongest factor affecting price**
- Larger homes with more rooms are generally more expensive  
- Distance from CBD reduces property value  
- Property type and region significantly impact pricing  

---

##  Recommendations

- Handle outliers before building predictive models  
- Include sales method for better price estimation  
- Focus on premium suburbs for investment analysis  
- Perform time-series analysis for future price prediction  

---

##  Tools & Libraries Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Google Colab  

---

##  Future Improvements

- Predictive modeling for house prices  
- Geospatial analysis using maps  
- Time series forecasting of market trends  
- Feature engineering for better insights  

---

##  Author

**Sreelakshmi K M**  
Data Analytics Project | 2026  

---

 If you found this project useful, feel free to star the repository.
