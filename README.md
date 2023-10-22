# COVID-19 Analysis: Understanding Disease Spread and Factors Influencing It Using SAS

## Introduction

The COVID-19 pandemic has affected the global population, leading to significant morbidity and mortality. Using data from Wisconsin, this project aims to delve deeper into various factors that may influence the spread of the virus and provide insights that could aid in effective decision-making.

## Objectives

- Evaluate the distribution of COVID-19 cases and outcomes across different counties.
- Understand the relationship between population demographics and COVID-19 outcomes.
- Assess the impact of socio-economic and technological factors on the spread of the virus.
- Analyze the differences in COVID-19 spread based on the size of the population in different census tracts.
- Employ clustering techniques to group similar regions based on demographic factors and study the disease trends within these clusters.

## Technologies Used

- **Software**: SAS
- **Data**: COVID-19 data for Wisconsin, sourced from the DePaul University database.

## Steps to Reproduce

1. **Set up your environment**:
   - Install SAS software.
   - Download the COVID-19 dataset from the provided URL.
   
2. **Run the SAS script**:
   - Import the dataset into your SAS environment.
   - Execute the data cleaning and transformation steps to derive necessary variables and filter out irrelevant or erroneous records.
   - Perform statistical analyses using various SAS procedures like `proc means`, `proc sgplot`, `proc corr`, `proc cluster`, and `proc reg` to uncover insights.
   - Conduct clustering analyses to group census tracts based on demographic characteristics and compare COVID-19 spread trends across these clusters.
   - Split the dataset into training and test sets to build regression models and evaluate their performance.

## Results

- Identified the top counties in Wisconsin with the highest rates of COVID-19 positive cases, hospitalizations, and deaths.
- Uncovered significant correlations between the percentage of positive cases and various socio-economic factors like limited English proficiency, lack of internet access, and poverty.
- Recognized patterns in COVID-19 spread based on census tract sizes, with certain size classes showing distinct trends.
- Clustered census tracts revealed specific demographics that may be at a higher risk.
- Regression models highlighted significant predictors for COVID-19 outcomes, helping in understanding which factors have the most substantial influence.

## Conclusion

The analysis offers a comprehensive view of the spread of COVID-19 in Wisconsin, shedding light on the regions most affected and the socio-economic factors that might influence the spread. Understanding these factors can guide policymakers and health officials in designing targeted interventions and resource allocation.
