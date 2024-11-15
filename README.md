# Data_Preprocessing_Assignment
Data preprocessing approach of the Sustainable Tourism Impact project

## Project Overview
This project examines the relationship between tourism activities and their environmental impacts. The goal is to classify the impact of tourism as either "High" or "Low" based on factors such as CO2 emissions, energy consumption, and tourism activity levels.


## 1. Data Sources
The dataset includes indicators relevant to sustainable tourism, derived from:
- **UNWTO (United Nations World Tourism Organization):** Tourism statistics and sustainability metrics.
- **NASA Earth Observations:** CO2 emissions and energy consumption data.
- **Open Government Data Portals:** Additional environmental data related to sustainability.
- **Research Publications:** Focused on sustainable tourism and environmental assessment.

---

## 2. Data Structure
The dataset consists of the following features:
- **`co2_emissions:`** Represents tourism-related carbon emissions.
- **`energy_consumption:`** Measures energy usage in tourism activities.
- **`tourism_activity:`** Reflects levels of tourism intensity.
- **`impact:`** Target variable, indicating environmental impact as "High" or "Low".

---

## 3. Data Preprocessing
### Current Data Format
The data is in a structured **CSV (Comma Separated Values)** format, suitable for machine learning.

### Key Preprocessing Steps
- Normalized numerical features to ensure comparability.
- Encoded categorical features (if applicable) to numerical values.
- Handled outliers using interquartile range (IQR) methods.
- Conducted exploratory data analysis to assess distributions, correlations, and potential biases.

---

## 4. Exploratory Data Analysis (EDA)
EDA was performed to understand data distributions, detect outliers, and analyze feature correlations:
- Distributions of features revealed slight skewness in CO2 emissions and tourism activity.
- Correlation analysis highlighted a weak relationship between energy consumption and CO2 emissions.
- Outliers were identified and addressed in CO2 emissions and tourism activity.

---

## 5. Hypothesis Testing
### Hypotheses
1. **H1:** Increased tourism activity results in higher environmental impact.
2. **H2:** Higher energy consumption correlates with increased CO2 emissions.

### Key Findings
- **H1:** Negligible influence of tourism activity on environmental impact.  
- **H2:** Weak negative correlation between energy consumption and CO2 emissions.

---

## 6. Data Splitting and Bias Mitigation
The dataset was split into training (70%), validation (15%), and test (15%) sets. Stratified sampling ensured the target variable's class distribution was preserved to prevent data bias.

---

## 7. Feature Importance
Feature importance analysis identified the most influential features:
1. **Energy Consumption:** 51.7%  
2. **CO2 Emissions:** 45.2%  
3. **Tourism Activity:** 3.1%  

---

## 8. Data Storage
The cleaned and processed dataset was saved in **CSV format** for reproducibility and ease of sharing.

---

## Summary
### Completed Steps
1. Data collection from multiple sources.  
2. Preprocessing, including normalization, encoding, and outlier handling.  
3. Exploratory data analysis (EDA) and hypothesis testing.  
4. Data splitting and feature importance analysis.  

### Next Steps
- Expand the dataset with additional features for broader analysis.  
- Develop and evaluate machine learning models for predictive accuracy.  

**** For further inquiries, please email [p.umutoniwa@alustudent.com].  ** 
