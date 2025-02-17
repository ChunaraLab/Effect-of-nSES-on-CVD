# Effect-of-nSES-on-CVD

## Overview

This repository stores the codes used to generate results for the paper:

“Effect of Neighborhood Environment on Cardiovascular Disease Incidence and the Mediating Role of Individual Socioeconomic and Behavioral Features: The Multi-Ethnic Study of Atherosclerosis and the Jackson Heart Study.”

## Repository Structure

The repository is organized into the following directories:
* JHS/ – Contains data preprocessing and exploratory analysis scripts for JHS data.
* MESA/ – Contains data preprocessing and exploratory analysis scripts for MESA data.
* combined_analysis/final_reordered_analysis/ – Includes code for the final statistical analysis using data from both studies.

## Data Sources

The study leverages data from the Multi-Ethnic Study of Atherosclerosis (MESA) [1] and the Jackson Heart Study (JHS) [2] to examine the impact of neighborhood environments on cardiovascular disease (CVD) incidence and the mediating role of individual socioeconomic and behavioral factors. 

The variables used for analysis have been described in our manuscript. Specifically,
* Outcome Variable: 10-year CVD incidence
* Exposure Variables: Neighborhood socioeconomic status, Neighborhood favorable food stores, Neighborhood physical activity facilities, Neighborhood racial segregation
* Potential Mediators: Family income, Nutrition, Physical activity, Alcohol consumption, Smoking status
* Covariates: Age, Sex, Diabetes, HDL, SBP, total cholesterol
* Additional covariates for MESA cohort: Data collection site, Race 

## References
[1] The Multi-Ethnic Study of Atherosclerosis (MESA). The Multi-Ethnic Study of Atherosclerosis (MESA) Public Dataset 2000. Accessed: 2024-06-30.

[2] The Jackson Heart Study (JHS). The Jackson Heart Study Public Dataset 2000. Accessed: 2024-06-30.
