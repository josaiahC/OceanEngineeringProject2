# <div align=center> Meteorology Project </div>

Josaiah Clark<br>
BME 450, Abadi<br>
2/21/20<br>

CODE: https://colab.research.google.com/drive/1dwd26rRM9IhMvH5ezwPlnv7dWUbQ8vSJ

## Introduction <br>
<p>
In this project, wind speed and precipitation data taken from surface buoys off the Oregon coast were examined from April 2018 to April 2019. The two locations under consideration were "Oregon Shelf Surface Mooring" and "Oregon Offshore Surface Mooring," the former being 72 kilometers East and 28 kilometers North of the latter. Annual wind and rain patterns were constructed for both sites in order to identify patterns of windy and rainy, rainy but not windy, windy but not rainy, and neither windy nor rainy conditions. Additionally, monthly plots were constructed for both sites to show which months result in the highest and lowest average precipitation rate and wind speed values for either site.

<h2> Oregon Shelf Surface Mooring </h2>

### Annual Wind and Rain Patterns
<img alt="hello" src=Oregon_Shelf_Surface_Mooring/annualRainWind.png><br>
**Figure 1**

<p> As shown in figure 1, most days it was both windy and rainy at the Oregon Shelf Surface Mooring site. In the Summer from late July to early September, there was a clear pattern of low wind and infrequent rain, which is typical for that time of year. There were scattered time periods of windy but not rainy weather, with the most days occuring in mid-to-late April, November, and May. Less concentrated and most infrequent were days where it was rainy but not windy, spread out evenly over the year but absent in the month of April.
</p>

### Monthly Average Wind Speed
<img alt="hello" src=Oregon_Shelf_Surface_Mooring/monthlyAvgWind.png><br>
**Figure 2**
<p>
From figure 2, it is clear that at the Oregon Shelf Surface Mooring site the month with the highest average wind speed was December (~6.75 m/s). The month with the lowest average wind speed at this site was August (~3 m/s).
</p> 

### Monthly Average Precipitation Rates
<img alt="hello" src=Oregon_Shelf_Surface_Mooring/monthlyAvgRain.png><br>
**Figure 3**
<p>
From figure 3, it is clear that at the Oregon Shelf Surface Mooring the month with the highest average hourly precipitation rate was February (~0.13 mm/hr). The month with the lowest precipitation rate at this site was July (<0.01 mm/hr).
</p>

<h2> Oregon Offshore Surface Mooring </h2>

### Annual Wind and Rain Patterns
<img alt="hello" src=Oregon_Offshore_Surface_Mooring/annualRainWind.png><br>
**Figure 4**
<p>
As shown in figure 4, the Oregon Offshore Surface Mooring site was most often exposed to both windy and rainy conditions during this time period. There was a large frequency of days with rain and no wind from late July to mid September, as well as in the second half of May. Days where it was windy but not rainy almost exclusively happened in the month of October, with other windy but not rainy days scattered between November and early May. Unlike the Oregon Shelf Surface Mooring site's annual wind and rain patterns from figure 1, there was no time of year at the Oregon Offshore Surface Mooring site with extended periods of no rain and no wind. 
</p>

### Monthly Average Wind Speed
<img alt="hello" src=Oregon_Offshore_Surface_Mooring/monthlyAvgWind.png><br>
**Figure 5**
<p>
Figure 5 shows that for the Oregon Offshore Surface Mooring site, December was the month with the highest average wind speed (~6.8 m/s). The month with the lowest average wind speed at this site was August (~3.7 m/s).
</p>


### Monthly Average Precipitation Rates
<img alt="hello" src=Oregon_Offshore_Surface_Mooring/monthlyAvgRain.png><br>
**Figure 6**
<p>
Figure 6 shows that for the Oregon Offshore Surface Mooring site, December was the month with the highest average precipitation rate (~0.12 mm/hr). The month with the lowest precipitation rate at this site was July (~0.02 mm/hr). 
</p>

<h2> Cross-Correlation of Wind Speeds and Precipitation Rates </h2>

<img alt="hello" src=Cross-Correlation/crossCorrWind.png><br>
**Figure 7**

<img alt="hello" src=Cross-Correlation/crossCorrRain.png><br>
**Figure 8**

### Time lag of wind speeds versus time lag of precipitation rates
<p>
  Figure 7 shows that the highest correlation between wind speeds at the Oregon Shelf Surface Mooring site and the Oregon Offshore Surface Mooring site was 0.303, where the Oregon Offshore Surface Mooring wind patterns lagged the Oregon Shelf Surface Mooring wind patterns by 11 days and 8 hours. The data suggests that more often than not, wind patterns travel soutwestward from near the coast and over the Oregon Offshore Surface Mooring buoy. Evidence to support the efficacy of this trend comes from the existence of the North Pacific Gyre, a large circulating ocean vortex that stems from both the coriolis effect and atmospheric wind currents. The data is in agreement with the southwestern wind patterns that travel down North America's West Coast, causing the North Pacific Gyre to continue its clockwise circulation. 
</p>
<p>
  Figure 8 shows that the highest correlation between precipitation rates at the Oregon Shelf Surface Mooring site and the Oregon Offshore Surface Mooring site was 0.241, where the Oregon Offshore Surface Mooring precipitation rates lagged the Oregon Shelf Surface Mooring precipitation rates by 8 days. 
</p>
<p>
  In both cross-correlation calculations (figures 7 and 8), data from the Oregon Shelf Surface Mooring buoy led Oregon Offshore Surface Mooring buoy by about ten days. These close lag values suggest that weather systems pass over the Oregon Shelf Surface Mooring sensor, then move out toward the Pacific where they pass over the Oregon Offshore Surface Mooring sensor. Cloud systems do not appear to move at the exact same rate as wind currents; given that both clouds and wind currents exist in three dimensional space and are affected by other parts of the atmosphere, this is not surprising. Despite this randomness, the fact that both wind speed and precipitation rate lags are relatively close, and that both correlation coefficients are of similar size, suggests that to some degree rain clouds follow the direction of wind currents.
</p>

## Conclusion
In this project, wind speed and precipitation data taken from surface buoys off the Oregon coast were examined from April 2018 to April 2019. Annual wind and rain patterns were constructed for both sites in order to identify patterns of windy and rainy, rainy but not windy, windy but not rainy, and neither windy nor rainy conditions. The data show that closer to the shore, weather is more seasonal, i.e. sunnier and calmer days occur between late June and late September. Further out from the shore, weather is rainier in the Summer and generally rainier than regions closer to shore. Monthly plots were constructed for both sites to show which months result in the highest and lowest average precipitation rate and wind speed values for either site. It was found that at both sites, December was the month with the highest average wind speed and August the one with the lowest average wind speed. Additionally, both sites had minimum average hourly precipitation rates in the month of July. For monthly average wind speeds and monthly average precipitation rates at both sites, values peaked somewhere between late Fall and Winter, declining to minimums between July and August. In conclusion, these two data sets were shown to be significantly correlated with each other, both between buoy locations and between wind speed and precipitation patterns.
