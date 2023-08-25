# Aviation Safety Analysis 

Author: Deniz Emre, Iriwin Lam, and Kacey Clougher

![index](https://github.com/kaceyclougher/Phase-1-Project/assets/137820049/13a6f23a-59eb-42ad-9d82-36bb8981c2fe)


## Overview

This project the Aviation Accident dataset, which contains data no aircraft incidents and accidents from 1948 to the present. Within this dataset, we uncover patterns in the reported accidents that have resulted in harm to passengers or damage to the aircraft. Our analysis aims to assist a new aviation company in identifying airplanes that are classified as low-risk according to our safety score.

## Business Problem

A new aviation enterprise is in the market for aircraft to kickstart its business endeavor. With the data at our disposal, our aim is to pinpoint the most secure aircraft options and offer suggestions for their initial procurement.

## Data
The dataset provided contains civil aviation accidents from 1962 to 2023. All aircraft types were included in this data. For the purposes of our investigation, we focused on airplane accidents across all reported engine types and manufacturers. It also included key attributes for a descriptive analysis, including the damage's severity, injuries, weather relations, phase of flight, and engine type. 

## Methods
We conducted separate analyses of weather conditions, engine types, and flight phases to uncover prevalent patterns in accident severity, encompassing both damage and injuries. The damage data was categorized into three types: "destroyed," "minor," and "substantial," while injury data was grouped by "total fatalities" and "uninjured." We then devised a safety assessment framework, incorporating the following metrics: the destruction rate, minor damage rate, substantial damage rate, injury rate, fatality rate, and survival rate, to assess the severity of damage and injuries, respectively. The cumulative weighted values of these rates yielded a safety score for each make and model present in the dataset.

## Results

Aircraft accidents were not reported before 1981. Accident rates decrease significantly over the 50-year timespan. This can be attributed to higher safety standards and improvement in aviation engineering. 

![Aviation_Accidents_Over_Years](https://github.com/kaceyclougher/Phase-1-Project/assets/137820049/774bc9d6-b496-4c94-ade2-cfd38c12e64f)

There was a mix of aircraft types including smaller passenger planes primarily used for local or private activities (skydiving, advertising, low-passenger private travel, etc.) and larger passenger jets. 

The top ten safest aircrafts included a mix of both types, however, they were made up of only three manufacturers. 

![Top_10_Models_Safety_Scores](https://github.com/kaceyclougher/Phase-1-Project/assets/137820049/34ca82a2-ac42-43e6-83d6-4cc5a7d68c91)

The manufacturers Cessna and Piper primarily provide reciprocating engine-type aircraft for smaller passenger counts (2-8 people). These planes are best known for recreational flying at low altitudes or short-distance passenger travel. Below are the top five models according to safety score.
![Cessna_Piper_Safety_Scores](https://github.com/kaceyclougher/Phase-1-Project/assets/137820049/f87421eb-affd-417e-8858-763641bd9f42)

The third manufacturer, Boeing, is best known for long-distance passenger travel using turbojet or turboprop engine types. Below are the top Boeing models. 
![Boeing_Safety_Scores](https://github.com/kaceyclougher/Phase-1-Project/assets/137820049/a693d9af-4f0f-4e0f-a5bd-c3983b21740f)

## Conclusions

* More recent aircraft are generally less prone to damage and less likely to cause injuries, thanks to advancements in aviation technology. Therefore, for this venture, it is advisable to acquire aircraft models manufactured within the past 5-10 years to ensure a more sound investment.


* The aircraft deemed safest by our safety scoring system may vary depending on the specific requirements of the company. It's important to note that the top-ranking aircraft in terms of safety may not necessarily align with the company's needs. For recreational and advertising purposes, smaller and more agile planes, such as those manufactured by Cessna and Piper, might be better suited for your business needs, even if they don't top the safety rankings.

* Furthermore, the aircraft that our scoring system identifies as the safest is the Boeing 737-291. This passenger jet boasts an impressive range of over 4,000 miles and has the capacity to accommodate up to 150 passengers. If your new business venture primarily focuses on long-distance travel enterprises, this aircraft stands out as the optimal choice.


## Next Steps

* This safety scoring model can be adapted to new data as it becomes available. Additionally, once a purpose has been identified, deeper analysis can be conducted based on airplane type to provide better recommendations for the new venture.

* Additional data such as the age of the airplane as an additional factor could enhance our assessment for potential purchases since newer aircraft typically experience fewer accidents.

# For More Information

See the full analysis in our [Jupyter Notebook](https://github.com/kaceyclougher/Phase-1-Project/blob/7a647ba3299eb7eec3bc349fe2cb88bd54f5e2c5/Phase%201%20Project%20Final.ipynb) or [dashboard] (https://public.tableau.com/views/AviationAnalysisDashboard_16929112179230/AnalysisDashboard?:language=en-US&:display_count=n&:origin=viz_share_link)
