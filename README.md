# Utqiagvik_Surface_Hydrology_Report
## introduction

In this final project for the Surface Hydrology course, I aim to investigate how rising temperatures in Utqiagvik, formerly known as Barrow, Alaska, affect the amount of precipitation and the frequency of extreme weather events. Utqiagvik is known for its extreme weather due to its location above the Arctic Circle, with dark and frigid winters, brief and cold springs, cool and foggy summers, and rapidly cooling falls. The city experiences extreme seasonal changes in daylight: continuous daylight during the polar day from late May to early August, with around 83 days of sunlight, and polar night from late November to mid-January, resulting in approximately 67 days of darkness. These harsh conditions are characterized by extreme cold, low precipitation, and significant seasonal changes in daylight.

Global warming, a well-known phenomenon, impacts various aspects of the Earth's environment, including melting icebergs, the death of algae, changes in precipitation patterns, and more. In Israel, we also feel the effects of rising temperatures, such as shifts in seasonality, fewer rainy days, and an increase in extreme weather events, leading to larger and more destructive floods that damage fields and infrastructure.
Based on the findings from "Temperature and Precipitation of Alaska 50 Year Trend Analysis" and "Coastal-Inland Distributions of Summer Air Temperature and Precipitation in Northern Alaska", both of which emphasize the rise in temperature and precipitation across Alaska, it is evident that the region has experienced significant warming and increased precipitation over the past 50 years. This is because warmer air holds more water vapor, leading to more intense and frequent precipitation events.
Therefore, my hypothesis is that with rising temperatures in Utqiagvik, there will be an overall increase in precipitation, with more rain and less snow. Additionally, I anticipate a higher frequency of extreme weather events, such as heavy rainfall occurring over shorter periods leading to larger and more destructive floods.
This project will explore the relationship between rising temperatures and changes in precipitation patterns in Utqiagvik, Alaska, using data from NOAA4, National Centers of Environmental Information.

![image](https://github.com/user-attachments/assets/d86c0d9f-94b5-4cae-80af-ca06f874c5b0)

Figure 1 – Map showing Utqiagvik's location. Utqiagvik is situated in northern Alaska, along the shore of the Arctic Ocean.


## Results
### Temperature
To determine if rising temperatures in Utqiagvik have an impact, we first need to establish whether the temperature is indeed increasing.  
![image](https://github.com/user-attachments/assets/29a157ac-300e-4a18-86aa-ab4b25ead21e)

Figure 2 – Yearly average temperature in Utqiagvik, 1925 - 2023, with an overlaid trend line and a 10-year moving average.

From Figure 2, we observe a clear warming trend. The initial value of the trend line is  -13.14°C, while the final value is -10.02°C, representing a 3.12°C rise, which corresponds to a 23.74% rise. This indicates a significant increase in the temperature in Utqiagvik.


![image](https://github.com/user-attachments/assets/01af66e9-14cf-49d4-956a-9b46594e4cdf)

Figure 3 – August minimum, maximum, and average temperatures in Utqiagvik, 1925 - 2023, with the mean temperature and August 1926 marked with a dot.
  
From Figure 3, we observe that the minimum, maximum, and average temperatures in August 1926 are not unique, as they are all close to the mean. None of these values are 
exceptional, as they fall within one standard deviation from the mean.


### Precipitation
![image](https://github.com/user-attachments/assets/c390ae7b-487e-45b6-b58f-0f32394cac98)

Figure 4 – Monthly precipitation in Utqiagvik from 1925 - 2023, with an overlaid trend line and a 10-year moving average.

From Figure 4, we observe a clear increasing trend in precipitation, as indicated by the trend line, showing that precipitation in Utqiagvik has risen over the years. In August 1926, Utqiagvik experienced over 200 mm of precipitation, with more than 50 mm falling in a single day. The initial value of the trend line is 8.41 mm, and the final value is 12.35 mm, representing a 3.94 mm increase, which corresponds to a 46.81% rise. Excluding August 1926, the increase is even more pronounced at 62.29% over the years. This observation underscores the significant upward trend in precipitation, with or without the extreme event in 1926.


![image](https://github.com/user-attachments/assets/481609c8-7d1e-4442-9e42-fef08d33b3fb)

Figure 5 – Seasonality of Precipitation in Utqiagvik, 1921 – 2023.


![image](https://github.com/user-attachments/assets/f0acaa0a-8a92-4f85-becb-bfe7aef70748)

Figure 6 – Seasonality of Precipitation, Seasonality Index, and the Difference from the Mean in Utqiagvik, 1921 – 2023.

In Figure 5, we observe that the maximum monthly precipitation is less than 25 mm, which is relatively low. Most of the precipitation occurs during July and August, indicating a noticeable seasonal variation between these peak months and others.
Figure 6, which shows the Seasonality Index using the Walsh and Lawler (1981) method, indicates a value of 0.6. This suggests a somewhat even distribution of precipitation throughout the year with some seasonal variation. This result seems to somewhat contradict the observation from Figure 4, where a more pronounced seasonality is apparent. This discrepancy may suggest that while summer months receive more precipitation, the overall distribution across the year is more balanced, leading to a moderate Seasonality Index.


![image](https://github.com/user-attachments/assets/1fe70e02-5abd-40ff-8906-166dac3a31a0)

Figure 7 – Yearly Seasonality Index calculated by the Walsh and Lawler (1981) method, 1921–2023.

From Figure 7, we observe a decrease in the seasonality index. The initial value of the trend line is 0.86, and the final value is 0.71, representing a 0.14 decrease, which corresponds to a 16.84% decline. Both values are higher than the 0.6 calculated for the entire period between 1921 and 2023. This discrepancy highlights that while the long-term average seasonality index reflects a general trend, individual years exhibit varying patterns. The decrease in the seasonality index over time indicates that precipitation in Utqiagvik has become more evenly distributed throughout the year, suggesting a reduction in the contrast between wet and dry periods.


### Return Period
![image](https://github.com/user-attachments/assets/3f3f0590-dc5f-48fd-b3d0-4e91d03605b9)

Figure 8 – Log Distribution of Daily Maximum Precipitation at Utqiagvik, 1921 - 2023


![image](https://github.com/user-attachments/assets/70b5395e-082d-4aee-8d85-671517b8193c)

Figure 9 - Probability density function (PDF) and cumulative distribution function (CDF) of the annual daily precipitation maximum.

Figures 8 and 9 reveal that over 85% of the annual daily maximum precipitation values are below 20 mm per day, indicating that precipitation exceeding 20 mm per day constitutes an extreme event.


Table 1 – Return levels of annual maximum daily precipitation in Utqiagvik calculated by Brutsaert (2005) method.
<img width="416" alt="image" src="https://github.com/user-attachments/assets/d90fafa7-8149-4757-b712-f530432004d9">

From Table 1, calculated using the Brutsaert (2005) method, we observe that a daily precipitation of 20 mm is likely to occur approximately once every 11.1 years. A more intense event, with 35 mm of precipitation, is expected once every 106 years, while an extreme event of 53.3 mm—the highest recorded during the observed period—is estimated to occur once every 774 years.


![image](https://github.com/user-attachments/assets/6841acb0-4f01-4dbe-9c82-c2503d0cf8f4)

Figure 10 – Scatter plot of days with more than 20 mm of precipitation in Utqiagvik, 1921 - 2023.

From Figure 10, we can see that August 1926 had 5 days with over 20 mm of precipitation, ranking among the top 4 highest precipitation events recorded. After 1926, there were 3 such days up to 1980 and another 3 from 1980 to the present. The August 1926 event is notable for its significant precipitation. The highest recorded days between 1926 and 1980 are among the lowest, while the days after 1980 show higher precipitation levels compared to the earlier period.


### Potential Evapotranspiration
![image](https://github.com/user-attachments/assets/13ae7b7d-1feb-4205-bf3f-a7c66b14d3bc)

Figure 11 – Potential Evapotranspiration, Temperature, Relative Humidity, Wind Speed, Solar Radiation and Vapor Pressure Deficit in Utqiagvik, 2017 – 2024.

From Figure 11, we observe that potential evapotranspiration, ET, peaks during the summer months, reflecting higher rates due to warmer temperatures and increased solar radiation. Temperature follows a clear seasonal pattern, rising in summer and dropping in winter. Relative humidity shows an inverse relationship with temperature, being lower in summer and higher in winter. Wind speed is variable throughout the year, with occasional peaks, but it does not follow a clear seasonal pattern. Solar radiation peaks in the summer and decreases in the winter, consistent with changes in daylight. Vapor pressure deficit, VPD, is higher during warmer months, indicating drier air conditions in the summer. Overall, these trends highlight the strong seasonal influence on climate variables in Utqiagvik.


## Discussion
### Temperature Increase 
The data analyzed in this project shows a significant increase in temperatures in Utqiagvik, Alaska, over the past century, as shown in Figure 2. The trend line from 1925 to 2023 demonstrates a 3.12°C rise in temperature, representing a 23.74% increase. This warming trend aligns with broader global patterns observed due to climate change, particularly in Arctic regions where warming is amplified by feedback mechanisms such as albedo reduction from melting ice and increased absorption of solar radiation by open water.

### Precipitation Increase 
The rising temperatures in Utqiagvik are correlated with an increase in precipitation, as demonstrated by the trend lines and moving averages in Figure 4. The analysis shows a 46.81% increase in monthly precipitation over the observed period, with even more pronounced changes when excluding 1926 extreme events. This finding supports the hypothesis that warmer air holds more moisture, leading to increased precipitation. However, it is crucial to note that the nature of this precipitation is also likely changing, with more rain and less snow as temperatures rise.

### Decrease in Seasonality Index
An unexpected finding in this study was the decrease in the Seasonality Index, SI, as illustrated in Figures 6 and 7. A declining SI suggests that precipitation is becoming more evenly distributed throughout the year, which might seem counterintuitive to the hypothesis predicting more extreme weather events. This trend implies a reduction in the contrast between wet and dry periods, leading to fewer instances of concentrated, heavy rainfall. While this could be seen as a sign of a more stable climate in terms of precipitation distribution, it also indicates potential shifts in the timing and type of precipitation, which could have significant impacts on the local ecosystem and human activities.

### Return Period
The return period analysis of extreme precipitation events, as shown in Figures 8 and 9, provides insights into the nature of such events in Utqiagvik. The data suggests that extreme precipitation events, defined as those exceeding 20 mm per day, remain relatively rare. Importantly, while the frequency of these events has not increased in recent decades, their intensity has grown, with significantly more millimeters of precipitation occurring on those extreme days. This indicates that although such events are not happening more often, when they do occur, they tend to be more severe. The August 1926 event remains a significant outlier in terms of both frequency and intensity, but the recent trend towards stronger precipitation events could be linked to the overall rise in temperatures, which results in higher moisture content in the atmosphere.

### 1926 Phenomenon
The August 1926 precipitation anomaly remains a focal point of discussion due to its severity. This event stands out as an extreme case, particularly because the temperature in August 1926 was near the mean of all the years studied, indicating that such an extreme precipitation event did not correspond with an unusually high temperature at that time. This suggests that other factors may have contributed to the anomaly. However, long-term trend data suggests that as the climate continues to warm, such anomalies may become more common. Despite this, the fact that similar extreme events have not been recorded with the same magnitude since 1926 indicates that while conditions are changing, they have not yet reached the extremes observed in 1926, though trends suggest they are potentially moving in that direction.

### Potential Evapotranspiration
The potential evapotranspiration, PET, in Utqiagvik reveals distinct seasonal patterns that correspond closely with temperature and solar radiation. PET peaks during the summer months, driven by higher temperatures and increased solar radiation, which together enhance evapotranspiration rates. The inverse relationship between temperature and relative humidity further underscores this trend, as drier conditions prevail during the warmer months. Although wind speed shows variability, it does not follow a distinct seasonal pattern and appears to have a less direct influence on PET compared to temperature and solar radiation. The elevated vapor pressure deficit, VPD, during summer months reflects the drier air, further contributing to higher PET levels. Overall, the data suggests that seasonal temperature and solar radiation are the primary drivers of PET in Utqiagvik, emphasizing the strong seasonal influence on local climate dynamics.

## Conclusions
In summary, the findings of this study underscore the significant impact of climate change on hydrological patterns in Utqiagvik, Alaska. The observed 3.12°C increase in temperature over the past century has been accompanied by a 46.81% rise in monthly precipitation, consistent with the hypothesis that warmer air holds more moisture. However, the analysis also revealed unexpected trends, such as a decrease in the Seasonality Index, indicating that precipitation is becoming more evenly distributed throughout the year, rather than increasingly concentrated in extreme events.
The return period analysis showed that while the frequency of extreme precipitation events has not increased, their intensity has grown, suggesting that the climate is shifting towards more severe precipitation events. The August 1926 precipitation anomaly remains an outlier in the historical record, particularly notable because it occurred during a time when temperatures were near the historical average. This anomaly, along with the increasing intensity of recent extreme precipitation events, suggests that as the climate continues to warm, we may see a rise in similarly severe events, even if their frequency does not increase.
The PET analysis shows that PET peaks during the summer months, primarily driven by higher temperatures and increased solar radiation. The inverse relationship between temperature and relative humidity, along with a higher vapor pressure deficit in summer, further supports these findings. While wind speed is variable, it does not significantly impact PET. Overall, the seasonal patterns observed in PET underscore the importance of temperature and solar radiation as key factors in Utqiagvik’s climate system, which is crucial for understanding local hydrological and environmental processes.
These findings highlight the complex and evolving nature of climate impacts in Arctic regions. The trends observed in Utqiagvik serve as a microcosm for broader changes occurring globally, emphasizing the need for continued monitoring and adaptation strategies to mitigate the effects of climate change on local ecosystems and communities.


## Sources
1.	J. M. Stafford, G. Wendler, and J. Curtis, 2000, "Temperature and Precipitation of Alaska 50 Year Trend Analysis", Theor. Appl. Climatol. 67, 33-44 (2000).
2.	R. K. Haugen and J. Brown, 2018, "Coastal-Inland Distributions of Summer Air Temperature and Precipitation in Northern Alaska", Arctic and Alpine Research, 12:4, 403-412 (2018).
3.	Alaska Climate Research Center website
4.	National Centers of Environmental Information, NOAA
Disclaimer – This work was generated with the help of AI tools to support the analysis, writing, and organization of content.
