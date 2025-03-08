# Spokane Public Library Attendance and Weather Correlation Using Statistical Analysis
[![License](https://img.shields.io/badge/License-CC0-lightgray.svg?style=flat-square)](https://creativecommons.org/publicdomain/zero/1.0/) 

## Motivation
The Spokane Public Library is a vital resource for the community, providing free access to knowledge, technology, and cultural enrichment. It serves as a hub for lifelong learning, offering books, research materials, educational programs, and digital resources for people of all ages. The library also fosters community engagement through events, workshops, and meeting spaces, ensuring that everyone—regardless of background—has opportunities to grow, connect, and succeed. Whether supporting students, job seekers, or casual readers, the Spokane Public Library plays a crucial role in enhancing education, literacy, and accessibility in the region.

## Importance Of Malloy 
Malloy played a pivotal role in transforming our raw data into actionable insights. By cleaning up information and standardizing formatting, it significantly improved data quality and consistency. The tool enabled us to join previously isolated queries, creating a unified data model that revealed relationships across different datasets.
Malloy's ability to output CSV files streamlined our workflow, allowing for seamless integration with other analytical tools. Most importantly, the structured data Malloy produced enabled us to conduct comprehensive regression analysis, which formed the foundation of our key findings and recommendations.
Through these capabilities, Malloy transformed what would have been a fragmented analysis into a cohesive, statistically sound investigation that yielded meaningful results.RetryClaude can make mistakes. Please double-check responses.

## Summary of Findings
### 1 - Liberty Park Correlation Analysis
### Overview
This is a correlation matrix for data collected at Liberty Park, with a sample size of 347. It examines relationships between location visits, weather conditions, and changes in visits and temperature. Yellow highlights indicate statistically significant correlations at p < .01 (correlation coefficients with absolute values ≥ .138), while lighter highlights indicate significance at p < .05 (correlation coefficients with absolute values ≥ .105).

### Key Findings
Strong correlation between visits and visit change (.699): Consistent with the other locations, there's a highly significant positive correlation between overall visits (All_Locations_Visits) and Visit_Change, indicating that more popular locations at Liberty Park continue to see greater increases in visitation.
Significant positive correlation between temperature and visits: Liberty Park shows the strongest temperature-visitation relationship of all locations analyzed, with statistically significant positive correlations between visits and temperature metrics (AvgMaxTemperature: .162, AvgMinTemperature: .136, AvgTemp: .153). This suggests that warmer temperatures are associated with higher visitation at Liberty Park.
Temperature variables maintain expected intercorrelations: As with all previous locations, the temperature variables show strong correlations with each other and expected negative relationships with snow metrics.

### Conclusion
Liberty Park shows the clearest temperature-visitation relationship among all the locations analyzed, suggesting that visitors to this park are more influenced by temperature than visitors to the other parks. The strong correlation between visits and visit change remains consistent with other locations. For Liberty Park management, this indicates that temperature is a more important factor in visitor behavior than at other parks, which could inform seasonal planning and programming. The park might consider enhancing warm-weather amenities or activities to capitalize on the increased visitation during warmer periods, while developing specific strategies to attract visitors during cooler weather.

<img width="775" alt="Image" src="https://github.com/user-attachments/assets/88477d5a-f024-4435-b225-84a645f40091" />

### Liberty Park - Final Statement 
Visitors come more often when it's warmer - this park shows the clearest connection between temperature and visitor numbers compared to other parks.

### 2 - South Hill Correlation Analysis
### Overview
This is a correlation matrix for data collected at South Hill, with a sample size of 353. Like the previous matrices, it examines relationships between location visits, weather conditions, and changes in visits and temperature. Yellow highlights indicate statistically significant correlations at p < .01 (correlation coefficients with absolute values ≥ .137), while lighter highlights indicate significance at p < .05 (correlation coefficients with absolute values ≥ .104).

### Key Findings
Strong correlation between visits and visit change (.671): Consistent with all other locations analyzed, there's a highly significant positive correlation between overall visits (All_Locations_Visits) and Visit_Change, indicating that more popular locations at South Hill continue to see greater increases in visitation.
Strong positive correlation between temperature and visits: South Hill shows the strongest temperature-visitation relationship of all locations analyzed, with highly significant positive correlations between visits and all temperature metrics (AvgMaxTemperature: .172, AvgMinTemperature: .152, AvgTemp: .166). This indicates that warmer temperatures are strongly associated with higher visitation at South Hill.
Weak negative correlation with snowfall: South Hill shows a weak but statistically significant negative correlation (-.111) between visits and AvgSnowfall, complementing the positive temperature-visitation relationship and suggesting that snowy conditions slightly reduce visitation.

### Conclusion
South Hill demonstrates the strongest weather-visitation relationship among all locations analyzed. The data clearly shows that visitors to South Hill are more influenced by temperature (positively) and snowfall (negatively) than visitors to most other parks. The strong relationship between visits and visit change remains consistent. For South Hill management, these findings clearly indicate that weather conditions play a meaningful role in visitor behavior. This suggests opportunities for seasonal adaptations in programming and amenities, potentially focusing on unique cold-weather offerings to counteract the natural decline in visitation during cooler or snowier periods, while maximizing the park's appeal during warmer seasons.

<img width="759" alt="Image" src="https://github.com/user-attachments/assets/f277e48c-48a6-4589-b232-174a896c3d32" />

### South Hill - Final Statement
Weather has the biggest impact here - warmer days bring more visitors and snowy days keep people away more than at any other park.
 
### 3 - Central Spokane Correlation Analysis
### Overview
This is a correlation matrix for data collected in Central Spokane, with a sample size of 361. The matrix shows relationships between various factors including location visits, weather conditions (snowfall, temperatures, snow depth), and changes in visits and temperature. The yellow highlights indicate statistically significant correlations at p < .01 (correlation coefficients with absolute values ≥ .135), while lighter highlights indicate significance at p < .05 (correlation coefficients with absolute values ≥ .103).

### Key Findings
Strong correlation between visits and visit change (.685): There's a highly significant positive correlation between overall visits (All_Locations_Visits) and Visit_Change, suggesting that locations with higher visitor numbers are also experiencing greater increases in visitation.
Temperature variables are highly intercorrelated: AvgMaxTemperature, AvgMinTemperature, and AvgTemp show very strong positive correlations with each other (between .942 and .991), indicating they move together as expected. These temperature variables show moderate negative correlations with AvgSnowfall and AvgSnowDepth, which is also logical (more snow when temperatures are lower).
Minimal weather impact on visitation: Interestingly, weather conditions (temperatures, snowfall, snow depth) show very weak correlations with All_Locations_Visits, with coefficients near zero (ranging from -.103 to .012). This suggests that weather factors have minimal influence on overall visitation patterns in Central Spokane.

### Conclusion
The data indicates that visitation to locations in Central Spokane is largely independent of weather conditions, which is somewhat surprising for a region that experiences significant seasonal weather variations. The strongest relationship exists between total visits and visit change, suggesting that popular locations continue to gain in popularity. Temperature variables behave as expected, showing strong internal correlations and expected negative relationships with snow metrics. For decision-makers in Central Spokane, this analysis suggests that weather-based planning for visitor services may be less important than focusing on trends in visitation growth at already-popular locations.
<img width="762" alt="Image" src="https://github.com/user-attachments/assets/3bfd5d31-4cf1-447d-9a19-ffe11337deb0" />

### Central Spokane - Final Statement
Weather doesn't really affect visitor numbers - people come regardless of whether it's warm or snowy.

### 4 - Shadle Park Correlation Analysis 
### Overview
This is a correlation matrix for data collected at Shadle Park, with a sample size of 353. Similar to the Central Spokane matrix, it shows relationships between location visits, weather conditions, and changes in visits and temperature. Yellow highlights indicate statistically significant correlations at p < .01 (correlation coefficients with absolute values ≥ .137), while lighter highlights indicate significance at p < .05 (correlation coefficients with absolute values ≥ .104).

### Key Findings
Strong correlation between visits and visit change (.680): There's a highly significant positive correlation between overall visits (All_Locations_Visits) and Visit_Change, very similar to what was observed in Central Spokane, suggesting that more popular locations continue to see greater increases in visitation.
Temperature variables remain highly intercorrelated: As with Central Spokane, AvgMaxTemperature, AvgMinTemperature, and AvgTemp show very strong positive correlations with each other (between .943 and .991), and expected negative correlations with snow metrics.
Weather has minimal impact on visitation: Similar to Central Spokane, weather conditions show very weak correlations with All_Locations_Visits (ranging from -.093 to -.013), indicating that weather has little influence on overall visitation patterns at Shadle Park.

### Conclusion
The Shadle Park data shows remarkably similar patterns to the Central Spokane analysis. Visitation appears largely independent of weather conditions, while the strongest relationship remains between total visits and visit change. The consistency between these two locations suggests a regional pattern where visitor behavior in Spokane is minimally affected by weather variables, despite seasonal weather variations. For Shadle Park management, this suggests that other factors beyond weather (such as programming, amenities, or existing popularity) are likely more important drivers of visitation patterns.
<img width="763" alt="Image" src="https://github.com/user-attachments/assets/3d03513a-5b3c-4d01-941c-fc58bafa90c1" />

### Shadle Park - Final Statement
Similar to Central Spokane, visitors come regardless of the weather, suggesting other factors like activities or facilities matter more.

### 5 - Indian Trail Correlation Analysis
### Overview
This is a correlation matrix for data collected at Indian Trail, with a sample size of 352. Like the previous matrices, it examines relationships between location visits, weather conditions, and changes in visits and temperature. Yellow highlights indicate statistically significant correlations at p < .01 (correlation coefficients with absolute values ≥ .137), while lighter highlights indicate significance at p < .05 (correlation coefficients with absolute values ≥ .105).

### Key Findings
Strong correlation between visits and visit change (.636): There's a highly significant positive correlation between overall visits (All_Locations_Visits) and Visit_Change, consistent with the pattern observed in both Central Spokane and Shadle Park, though slightly weaker in magnitude.
Weak positive correlation between temperature and visits: Unlike the previous locations, Indian Trail shows a small but statistically significant positive correlation (.121-.125) between visits and temperature metrics (AvgMaxTemperature, AvgMinTemperature, and AvgTemp). This suggests that, at Indian Trail, warmer temperatures are associated with slightly higher visitation.
Temperature variables maintain strong intercorrelations: As with the other locations, temperature variables show expected strong correlations with each other (.942-.991) and negative correlations with snow metrics.

### Conclusion
While the Indian Trail data shows many similarities to the other locations (particularly the strong visits-visit change relationship and the temperature intercorrelations), it differs in showing a modest positive relationship between temperatures and visitation. This suggests that Indian Trail visitors may be somewhat more influenced by temperature than visitors to Central Spokane or Shadle Park. This could be due to the specific amenities, location characteristics, or user demographics of Indian Trail. Park managers might consider this temperature sensitivity when planning seasonal activities or improvements at this specific location, though the correlation remains relatively modest.
<img width="737" alt="Image" src="https://github.com/user-attachments/assets/032a74bf-d8b2-44f9-a74d-2bb9cc625473" />

### Indian Trail - Final Statement
Slightly more visitors on warmer days, but the effect is modest - temperature matters a bit more here than at Central Spokane or Shadle Park.

## Directions on How to Run it Yourself

 1. **Click** on this link [here](https://github.com/LukasNichols/SpokaneLibraryWeather)
 2. **Click** on the file that ends with '.malloyNB'.
 3. **Type** the period key (" . "). 
 4. **Click** the Run All button on the top of the page.
 5. All information will be loaded and you may look at the whole analysis. 

## Code

This repository contains one Malloy code file:
- [`SLA.malloy`](SLA.malloy), short for 'Spokane Library Attendance', this file performs the analysis on the data provided by the Spokane Library.

This repository contains three CSV files:
- [`gates_full(gates_full).csv`](gates_full(gates_full).csv), provides data on the attendance of the libraries.
- [`circ_dataSPL.csv`](circ_dataSPL.csv), provides the data of what servies were performed at library.
- [`spokane-temp-1.csv`](spokane-temp-1.csv), provides the weather data of the Greater Spokane Area.

## Contributors
This repository contains data obtained by [Professor Timothy Olsen](https://www.gonzaga.edu/academics/faculty-listing/detail/timothy-olsen-phd-8e1036cc), through the [Spokane Public Library](https://www.spokanelibrary.org/which-library-system-is-which/?gad_source=1&gclid=Cj0KCQiA8fW9BhC8ARIsACwHqYp6iJs5v-hdK6ftJrQgo2nl564GV1f8VD5-BoWqPfnMpIiMxn9qi1EaAil6EALw_wcB), provided to Gonzaga University, and analyzed by MSBA 622 students.

## Licensing
The data files provided directly from the Spokane Public Library are, as government documents, in the public domain. All other data files have been generated by Lukas Nichols, Brandon DuBois, and Griffin Linn for Gonzaga University Graduate School of Business as part of the MSBA-622-01 Data Science for Business (Spring 2025) course. These files are available under the terms of the Creative Commons’ [CC BY-SA 4.0 license terms](https://creativecommons.org/licenses/by-sa/4.0/). This repository’s code is available under the [MIT License terms](https://opensource.org/license/mit/).
