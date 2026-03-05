**INTRODUCTION**

The COVID-19 pandemic significantly impacted global health systems and patient outcomes. Analyzing patient-level data is essential to understand the factors influencing recovery and mortality.
This project examines a large COVID-19 dataset to identify how demographics, comorbidities, vaccination status, severity, and treatments affect recovery time and survival rates. The goal is to derive meaningful insights that support better healthcare decision-making.

**PROJECT OBJECTIVE**

To clean and pre-process the “COVID-19 Recovery Dataset” by dealing with inconsistency, missing values and null values.                              
To build data modelling if there are more tables created using either MS Excel or Power BI.                                  
To create Report using visualizations using Power BI.                                                    
To create an interactive dashboard using slicers and filters.                                            

**PROBLEM STATEMENT**

This COVID-19 Recovery csv dataset consists of 28 columns and 70,000 rows.              
Missing values in vaccination status, comorbidities, symptoms, and treatments.            
Logical errors in recovery and death indicators.            
Date columns stored in incorrect numeric format.              
Unrealistic distribution of recovery vs death rates.              
Outcome dates not aligned with status flags.                          
Inconsistent geographic and categorical data entries.                    

**Data Cleaning Steps In Excel using Power Query Editor**

Removed duplicates and handled missing values.
Corrected logical inconsistencies in recovery and death data.
Converted and Formatted Date fields properly.
Standardized categorical variables (severity, treatment, variant).
Removed non-informative or irrelevant columns.
Added new custom column like “Date_Of_Discharge” , ”Patient_Status” and “SL_NO”.
Result: Clean and structured dataset ready for accurate analysis.

**Data Modelling**

Used a single-table data model for analysis.                                            
Performed transformations and calculations within the same table.                                                  
Avoided complex relationships due to structured dataset design.                                                          
Applied measures and calculated columns in Power BI.                                                                      
Calculated measures – “Total Patients”, “Total Recovered”, “Total Death”, “Active Cases”, “Recovery Rate %”, “Death Rate %” and “Average Recovery Days”.                
Calculated Columns – “Age Group” ,”Age Group Sort”.                            
Ensured clean structure before visualization.                              

**Dashboard Overview**

KPI Cards ( Total Cases, Recovery Rate %, Death Rate %, Active Cases, Average Recovery Days).
Line Chart – Cases Over Time (Alpha, Delta, Omicron).
Filled Map Visualization – Cases By Region.
Stacked Column Chart – Cases By Severity and Age Group.
Donut Chart – Cases By Vaccination Details.
Clustered Bar Chart –Country wise Recovery, Death Rate.
Scatter Chart – Age wise Vaccination and Days To Recovery.
Slicers – Date, Region/State, Variant, Severity.
Filter –Based on Year and Month - Applied on all pages.

**Insights**

Majority of cases fall under mild severity, but critical cases show higher mortality risk.
Older age groups demonstrate increased ICU admissions and death rates.
Certain variants show higher severity and mortality impact compared to others.
Vaccinated individuals display relatively better recovery trends.
Severe cases significantly contribute to active case burden and healthcare load.

Demographics, severity level, variant type, and vaccination status are major factors influencing recovery and mortality outcomes.

**Suggestions**

Prioritize care for high-risk age groups.
Strengthen monitoring and early treatment for severe and critical and Omicron cases.
Encourage vaccination campaigns to improve recovery outcomes.
Improve data accuracy and consistency.
Standardize data collection formats to avoid missing values and logical errors.
Use dashboards for real-time monitoring and planning.

**Conclusion**

This analysis demonstrates how data-driven insights can help understand critical factors affecting COVID-19 recovery and mortality.
By applying proper data cleaning, modeling, and visualization techniques, we transformed raw data into meaningful insights that support informed healthcare decisions.




