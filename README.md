# Airbnb Pricing Analysis in European Cities
## Contributors
Tu Nguyen
Djeno van de Stadt
## Project Overview
This project is a part of the Data Wrangling course at Vrije Universiteit Amsterdam. It explores the key factors influencing Airbnb listing prices across 10 major European cities. We analyze the impact of location-based factors (distance from the city center and metro access), host characteristics (superhost status, business host classification), and guest satisfaction ratings on pricing.
## Dataset
Source: Kaggle - Airbnb Pricing Dataset (adapted from Gyódi & Nawaro, 2021)
Data Scope: 20 CSV files containing listings from 10 cities on both weekdays and weekends
Preprocessing: Cleaning, outlier removal using IQR, and feature engineering for analysis
## Key Analyses & Methods
Exploratory Data Analysis (EDA): KDE & box plots for price distribution, city-wise comparisons
Statistical Tests:
t-tests for superhost & business host price differences
ANOVA to compare guest satisfaction rating impact
Regression Model: Evaluates the combined effects of location, host attributes, and guest satisfaction on pricing
## Key Findings
Metro proximity influences pricing more than city center distance.
Superhosts tend to charge lower prices, likely leveraging higher booking volume.
Guest satisfaction follows a U-shaped trend, with top-rated listings commanding higher prices.
The model explains limited variance (low R²), suggesting additional factors like seasonality and property features impact pricing.
## Limitations & Future Work
Imbalance in city volume (e.g., Amsterdam, London dominate data).
Metro range >3km has too few listings for meaningful analysis.
Future work could explore property-specific factors and seasonal demand trends.
