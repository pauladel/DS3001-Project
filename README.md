# DS3001-Project
https://www.kaggle.com/datasets/headsortails/us-natural-disaster-declarations 
https://www.kaggle.com/datasets/justin2028/unemployment-in-america-per-us-state 
https://www.kaggle.com/datasets/davidbroberts/us-gdp-by-state-19972020 
https://www.kaggle.com/datasets/thedevastator/uncovering-trends-in-health-outcomes-and-socioec 


Research Question: Are counties with lower educational attainment and higher poverty rates more vulnerable to long term health impacts from natural disasters?

1. What is in the data?
The datasets contain a mix of socioeconomic, health, and disaster-related data at the state or county level.

gdp_by_state_1997_2020.csv: This file contains data on the gross domestic product (GDP) by state, spanning from 1997 to 2020. This could help assess the economic resilience and wealth of states before and after disasters.

health_socio_avg_household_size.csv: This file contains data about the average household size, which can indicate social structure and density, affecting disaster recovery.

health_socio_cancer_reg.csv: This provides cancer incidence or registration data, offering insights into long-term health impacts in certain regions.

unemployment_per_state.csv: This dataset provides unemployment rates per state, potentially highlighting economic vulnerability related to poverty.

us_disaster_declarations.csv: This includes data about declared natural disasters in the U.S., indicating which areas have been affected by disasters over time.


These datasets offer a combination of economic, health, and disaster data that are crucial for examining vulnerabilities in counties with lower educational attainment and higher poverty rates. Our data still needs to be combined/cleaned and we have a plan for how to do it Here's how the datasets could align with the research question:

Poverty and Socioeconomic Factors: Data on GDP, unemployment rates, and household size can be used to infer economic conditions and social vulnerability in various counties. Higher poverty levels may correlate with limited resources for disaster preparedness and recovery.

Health Impacts: Health-related datasets (like cancer registry and household size) will provide insights into long-term health impacts post-disaster. For instance, areas with already compromised health might face greater difficulties in disaster recovery.

Disaster Vulnerability: The disaster-related datasets will help identify counties that have experienced significant disasters. By correlating these with poverty and educational data, you can determine which areas are more vulnerable to long-term health impacts post-disaster.

**Potential Challenges:
**Data Merging and Standardization: The datasets appear to come from different sources and likely have different formats (e.g., different timeframes, geographical levels of data—state vs. county). Merging these datasets on a common variable, like state or county, might require cleaning and alignment of formats, especially if some data is available at the state level while your analysis focuses on counties.

Missing or Incomplete Data: It’s common in large datasets, especially disaster and health-related data, to encounter missing or incomplete entries. This could lead to potential biases in analysis if certain counties or states lack sufficient data.

Geographical Aggregation: Since some datasets appear to be at the state level (e.g., GDP by state), while you may need county-level data, this could require additional transformations or external data sources to disaggregate the data to a finer geographical scale.

Temporal Alignment: Some datasets span different time periods (like GDP from 1997 to 2020), and it might be challenging to align them if other datasets cover only specific years or are incomplete for certain years.

Analysis: By combining disaster data with socio-economic variables, we can track how counties with lower education levels and higher poverty rates recover from natural disasters in terms of health outcomes (e.g., cancer death rates).
