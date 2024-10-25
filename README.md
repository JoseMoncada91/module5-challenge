# Pymaceuticals Inc. Analysis
**Author:** Jose Moncada

## Project Overview
This project involves an analysis of the effects of various drug treatments on tumor sizes in mice.
The goal is to identify effective treatments, understand demographic influences (age and sex), and explore relationships between mouse weight and tumor growth.
Insights from this analysis may inform future research and treatment strategies.

## Analysis Summary

### Effectiveness of Treatments on Tumor Size
The analysis indicates that different drug regimens result in varying tumor sizes among the mice.
By examining how each treatment affects tumor volume, we can identify the most effective therapies, providing valuable information for future research.

### Impact of Age and Sex on Treatment Response
Observations reveal interesting patterns related to age and sex. Younger mice may exhibit different responses to treatments compared to older ones.
Recognizing these differences can lead to more tailored treatments and improved outcomes based on demographic factors.

### Link Between Weight and Tumor Growth
A potential relationship has been noted between the weight of the mice and their tumor volume.
If heavier mice tend to have larger tumors, this could indicate that weight is a significant factor in tumor development or treatment efficacy. This insight is crucial for designing future experiments and understanding cancer dynamics.

## Dependencies and Setup
To run the analysis, the following Python libraries are required:
- `matplotlib`
- `pandas`
- `scipy`

Data Files
The study data consists of two CSV files:

Mouse_metadata.csv: Contains metadata for the mice used in the study.
Study_results.csv: Contains the study results, including tumor measurements

Data Overview
The combined dataset includes the following columns:

Mouse ID
Timepoint
Tumor Volume (mm3)
Metastatic Sites
Drug Regimen
Sex
Age_months
Weight (g)
Data Cleaning
To ensure the integrity of the data:

Check for duplicate entries by Mouse ID and Timepoint.
Remove any duplicates.

Conclusion
This analysis provides insights into the effectiveness of various drug treatments on tumor size, while also considering demographic factors such as age and sex, and their influence on treatment outcomes. Future research can build upon these findings to optimize treatment strategies in similar studies.
