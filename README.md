# <div align=center> Meteorology Project </div>

Josaiah Clark<br>
BME 450, Abadi<br>
2/21/20<br>

CODE: https://colab.research.google.com/drive/1dwd26rRM9IhMvH5ezwPlnv7dWUbQ8vSJ

## Introduction <br>
<p>
In this project, wind speed and precipitation rate data taken from surface buoys off the Oregon coast were examined from April 2018 to April 2019. The two locations under examination were "Oregon Shelf Surface Mooring" and "Oregon Offshore Surface Mooring," the former being 72 kilometers East and 28 kilometers North of the latter. 

<h2> Oregon Shelf Surface Mooring </h2>

### Annual Wind and Rain Patterns
<img alt="hello" src=Oregon_Shelf_Surface_Mooring/annualRainWind.png><br>
**Figure 1**

<p> As shown in figure 1, it is most often both windy and rainy at the Oregon Shelf Surface Mooring site. In the Summer from late July to early September, there is a clear pattern of low wind and infrequent rain, which is typical for this time of year. There are scattered regions of windy but not rainy weather, with the most days occuring in mid-to-late April, November, and May. Less concentrated and most infrequent are days where it is rainy but not windy, spread out evenly over the year but absent in the month of April.
</p>

### Monthly Average Wind Speed
<img alt="hello" src=Oregon_Shelf_Surface_Mooring/monthlyAvgWind.png><br>
**Figure 2**
<p>
From figure 2, it is clear that at the Oregon Shelf Surface Mooring the month with the highest average wind speed was December (~6.75 m/s).
</p> 

### Monthly Average Precipitation Rates
<img alt="hello" src=Oregon_Shelf_Surface_Mooring/monthlyAvgRain.png><br>
**Figure 3**
<p>
From figure 3, it is clear that at the Oregon Shelf Surface Mooring the month with the highest average hourly precipitation rate was February (~0.13 mm/hr).
</p>

<h2> Oregon Offshore Surface Mooring </h2>

### Annual Wind and Rain Patterns
<img alt="hello" src=Oregon_Offshore_Surface_Mooring/annualRainWind.png><br>
**Figure 4**
<p>
As shown in figure 4, the Oregon Offshore Surface Mooring site is most often exposed to both windy and rainy conditions. There is a large frequency of days with rain and no wind from late July to mid September, 
</p>

### Monthly Average Wind Speed
<img alt="hello" src=Oregon_Offshore_Surface_Mooring/monthlyAvgWind.png><br>
**Figure 5**

### Monthly Average Precipitation Rates
<img alt="hello" src=Oregon_Offshore_Surface_Mooring/monthlyAvgRain.png><br>
**Figure 6**

<h2> Cross-Correlation of Wind Speeds and Precipitation Rates </h2>

<img alt="hello" src=Cross-Correlation/crossCorrWind.png><br>
**Figure 7**
<p>
Figure 7 shows that the highest correlation between wind speeds at the Oregon Shelf Surface Mooring site and the Oregon Offshore Surface Mooring was 0.303, where the Oregon Offshore Surface Mooring wind patterns lagged the Oregon Shelf Surface Mooring wind patterns by 11 days and 8 hours. The data suggests that more often than not, wind patterns travel soutwestward from near the coast and over the Oregon Offshore Surface Mooring buoy. Evidence to support the efficacy of this trend comes from the existence of the North Pacific Gyre, a large circulating ocean vortex that stems from both the coriolis effect and atmospheric wind currents. The data is in agreement with the southwestern wind patterns that travel down North America's West Coast, causing the North Pacific Gyre to circulate clockwise. 
</p>

<img alt="hello" src=Cross-Correlation/crossCorrRain.png><br>
**Figure 8**
<p>
</p>

In both cross-correlation calculations (figures 7 and 8), data from Oregon Shelf Surface Mooring led Oregon Offshore Surface Mooring by about ten days. These close lag values suggest that weather systems pass over the Oregon Shelf Surface Mooring sensor, then move out toward the Pacific where they pass over the Oregon Offshore Surface Mooring sensor.8
## Conclusion
