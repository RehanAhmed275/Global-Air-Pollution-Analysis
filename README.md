
#Global Air Pollution Analysis

##Project Overview:
This project analyzed global air pollution data to uncover critical variability and patterns in air quality across different countries and cities. Utilizing statistical strategies and visualizations, we identified key pollutants affecting AQI values and highlighted regions with critical air quality issues. Our findings support data-driven policy interventions and awareness efforts to mitigate air pollution globally.

##Dataset:
The dataset used for this analysis is sourced from Kaggle: Global Air Pollution.

##Summary of Dataset:
Total Rows: 23,463
Total Columns: 12

##Columns Description:
Country: Name of the country

City: Name of the city

AQI Value: Overall AQI value of the city

AQI Category: Overall AQI category of the city

CO AQI Value: AQI value of Carbon Monoxide of the city

CO AQI Category: AQI category of Carbon Monoxide of the city

Ozone AQI Value: AQI value of Ozone of the city

Ozone AQI Category: AQI category of Ozone of the city

NO2 AQI Value: AQI value of Nitrogen Dioxide of the city

NO2 AQI Category: AQI category of Nitrogen Dioxide of the city

PM2.5 AQI Value: AQI value of Particulate Matter with a diameter of 2.5 micrometers or less of the city

PM2.5 AQI Category: AQI category of Particulate Matter with a diameter of 2.5 micrometers or less of the city

##Data Cleanup & Preprocessing

###Duplicate Detection and Removal:
Checked for duplicate records and removed them to ensure unique observations.

###Data Type Conversion:
Converted AQI values to floating-point numbers for precise calculations.

###Missing Values Handling:
Filled missing 'City' values with 'Unknown' and removed rows with missing 'Country' values.

###Outlier Detection and Removal:
Used boxplots and Z-scores to identify and remove outliers.

###Descriptive Statistics:
Summarized data using descriptive statistics to understand the central tendency and spread.

##Data Exploration

###Distribution of AQI Values:
Visualized AQI values distribution using histograms.

###Distribution of AQI Categories:
Showed the frequency of AQI categories using count plots.

###AQI Values Across Top Countries and Cities:
Identified and compared top countries and cities with the highest average AQI values using box plots and bar plots.

###Correlation Analysis:
Generated scatter plots and correlation matrices to understand the relationships between pollutants and AQI values.

###Interactive Visualizations:
Created interactive scatter plots, pie charts, and geo-maps to enhance data exploration.

##Hypothesis Testing

###Two-Sample T-Test:
Compared AQI values between India and China to determine significant differences.

###ANOVA Test:
Compared AQI values across multiple countries to identify significant differences.

###Chi-Square Test:
Analyzed the association between countries and AQI categories.

###Confidence Intervals:
Calculated 95% confidence intervals for mean AQI values of selected countries to understand air quality variations.

##Linear Regression and Correlation Analysis

###Correlation Analysis:
Identified strong correlations between AQI components, especially PM2.5.

###Linear Regression:
Built a model to predict AQI values based on pollutant levels, achieving a high R-squared value indicating an excellent fit.

##Key Findings

###Hypothesis Testing: 
Significant differences in air quality among various countries were identified.

###Confidence Intervals: 
Highlighted variations in AQI values across different countries.

###Correlation and Regression Analysis: 
PM2.5 was found to be the most influential pollutant on AQI.

##Conclusion

This analysis provides a comprehensive understanding of global air pollution trends and key factors affecting air quality. The insights gained can help in making informed decisions for policy-making and further research to combat air pollution.

##Author:
Rehan Ahmed, Data Science and Machine Learning Expert.

##License:
This project is licensed under the MIT License.

##Acknowledgements:
Kaggle for providing the dataset.
Open-source libraries like pandas, numpy, matplotlib, seaborn, and scikit-learn for data analysis and visualization tools.
