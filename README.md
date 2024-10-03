# Traffic Accident Data Analysis (2016-2023)

## Project Overview

This project analyzes traffic accident data from the **US Accident (2016-2023)** dataset to identify patterns related to road conditions, weather, and time of the day. We also visualize accident hotspots and examine contributing factors to provide insights into traffic safety improvements.

## Observations

### 1. Accidents by Hour of the Day
- A noticeable pattern emerges where accidents peak during specific hours of the day. Typically, morning and evening rush hours (e.g., 7-9 AM and 4-6 PM) show higher accident frequencies due to increased traffic volume.

### 2. Accidents and Traffic Control Conditions
- The presence of traffic signals or stop signs seems to have a significant impact on both the frequency and severity of accidents.
- Roads with fewer traffic controls, such as signals or stop signs, may be more prone to accidents, especially at intersections.

### 3. Accidents by Twilight Conditions (Sunrise/Sunset)
- Accidents occurring at night (during "Night" in `Sunrise_Sunset` or `Civil_Twilight`) tend to show higher severity or frequency. Reduced visibility and driver fatigue often contribute to these nighttime accidents.
- Higher accident frequencies during twilight or dark conditions suggest that poor visibility is a major contributing factor.

### 4. Severity Distribution
- Analyzing accident severity (levels 1 to 4, where 4 is the most severe) reveals that specific traffic conditions and times of day are more prone to severe accidents.
- Nighttime and intersections with fewer controls contribute to more severe accidents.

### 5. Geospatial Hotspots
- The heatmap visualization of accident locations indicates that accidents are concentrated geographically, often in urban areas or on busy highways.
- These hotspots highlight areas where targeted interventions can be made to improve road safety.

## Knowledge Gained

### 1. Time and Accident Patterns
- **Rush Hours:** The data reveals that accidents are more frequent during morning and evening rush hours. This aligns with general traffic patterns.
- **Night Accidents:** Accidents that occur at night or during twilight conditions tend to be more severe, likely due to poor lighting, reduced visibility, and driver fatigue.

### 2. Impact of Traffic Controls
- Roads lacking adequate traffic control measures, such as signals or stop signs, have a higher incidence of accidents.
- Traffic calming measures, like roundabouts and proper signage, play a vital role in reducing accident frequency and severity.

### 3. Severe Accidents and Conditions
- Specific weather conditions and times of the day (e.g., nighttime) are associated with more severe accidents. Improving street lighting, adding traffic signals, and enhancing road signage could help reduce both accident frequency and severity.

### 4. Geographical Hotspots
- Mapping accident hotspots reveals critical areas for intervention. Insights from these hotspots can be valuable for traffic authorities, guiding infrastructure improvements such as additional signals, better lighting, and enhanced signage in high-risk areas.

## Conclusion

### Key Insights:
1. **Peak accident times** are during rush hours, with higher traffic volumes leading to more accidents.
2. **Nighttime and twilight conditions** see more frequent and severe accidents, highlighting the need for better visibility and lighting improvements.
3. **Traffic control measures**, such as stop signs and traffic signals, are critical in reducing accidents. Roads with fewer traffic controls often have higher accident rates.
4. **Geospatial analysis** reveals accident hotspots, providing a basis for targeted interventions, such as improving signage, adding roundabouts, or redesigning high-risk intersections.

These findings can be used by policymakers and traffic authorities to enhance road safety through better infrastructure planning, additional traffic controls, and measures to mitigate accidents during high-risk periods and at high-risk locations.

## Future Work
- Further analysis of weather patterns and their contribution to accidents.
- Developing predictive models for real-time accident hotspot detection.
- Exploring the impact of road surface conditions (e.g., wet, icy) on accident severity.
