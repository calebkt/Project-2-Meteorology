Caleb Taing

2/21/2020

Project 2 - Meteorology

The goal for this project is outside of simply the scope of coding, but instead the accurate analysis of Bulk Meteorology data in terms of wind speed and rain rate. We are to utilize the M2M method in order to monitor a years worth of data from mooring sites including the Oregon Shelf Surface Mooring (OSSM), and Oregon Offshore Surface Mooring (OOSM). The Bulk Meteorology data specifically analyzes wind speed and rain rate, in parameters of velocity vs precipitation. As well, we use these comparisons in order to plot a cross-correlation between OSSm vs OOSM data in order to understand how different locations compare in terms of similarity. 

Images provided below are considered not rainy if precipitation rate is less then 5mm/hr; not windy if wind speed is less then 2m/s.

**Oregon Shelf Surface Mooring plots for Wind Speed and Rain Rate**
>> ![w_OSSM](https://github.com/calebkt/Project-2-Meteorology/blob/master/P2_Pictures/w_OSSM.PNG)
> ![r_OSSM](https://github.com/calebkt/Project-2-Meteorology/blob/master/P2_Pictures/r_OSSM.PNG)

**Oregon Offshore Surface Mooring plots for Wind Speed and Rain Rate**
>> ![w_OOSM](https://github.com/calebkt/Project-2-Meteorology/blob/master/P2_Pictures/w_OOSM.PNG)
> ![r_OOSM](https://github.com/calebkt/Project-2-Meteorology/blob/master/P2_Pictures/r_OOSM.PNG)

___________________________________________________________________________________________________________

**Plot: Case 1- Wind and Rain (Absent) vs Time** *Left OSSM, Right OOSM*
> ![absent_OSSM](https://github.com/calebkt/Project-2-Meteorology/blob/master/P2_Pictures/absent_OSSM.PNG)
> ![absent_OOSM](https://github.com/calebkt/Project-2-Meteorology/blob/master/P2_Pictures/absent_OOSM.PNG)

**Plot: Case 2- Windy w/o Rain vs Time**
> ![noR_OSSM](https://github.com/calebkt/Project-2-Meteorology/blob/master/P2_Pictures/noR_OSSM.PNG)
> ![noR_OOSM](https://github.com/calebkt/Project-2-Meteorology/blob/master/P2_Pictures/noR_OOSM.PNG)

**Plot: Case 3- Rainy w/o Wind vs Time**
> ![noW_OSSM](https://github.com/calebkt/Project-2-Meteorology/blob/master/P2_Pictures/noW_OSSM.PNG)
> ![noW_OOSM](https://github.com/calebkt/Project-2-Meteorology/blob/master/P2_Pictures/noW_OOSM.PNG)

**Plot: Case 4- Rainy and Windy vs Time**
> ![RvsW_OSSM](https://github.com/calebkt/Project-2-Meteorology/blob/master/P2_Pictures/RvsW_OSSM.PNG)
> ![RvsW_OOSM](https://github.com/calebkt/Project-2-Meteorology/blob/master/P2_Pictures/RvsW_OOSM.PNG)
____________________________________________________________________________________________________________
# Analyzing Average Wind Speeds vs Months
**Monthly Averages for Wind Speed** *OSSM (Top), OOSM (Bottom)*
> ![avgW_OSSM](https://github.com/calebkt/Project-2-Meteorology/blob/master/P2_Pictures/avgW_OSSM.PNG)
> ![avgW_OOSM](https://github.com/calebkt/Project-2-Meteorology/blob/master/P2_Pictures/avgW_OOSM.PNG)

Starting with the lowest mean wind rate, the comparisons are different. For OSSM, the lowest is within June; while for OOMS, the lowest is within October. The highest on the other hand is within July for OSSM, and November for OOMS. 

# Analyzing Average Rain Rates vs Months
**Monthly Averages for Rain Rate** *OSSM (Top), OOSM (Bottom)*
> ![avgR_OSSM](https://github.com/calebkt/Project-2-Meteorology/blob/master/P2_Pictures/avgR_OSSM.PNG)
> ![avgR_OOSM](https://github.com/calebkt/Project-2-Meteorology/blob/master/P2_Pictures/avgR_OOSM.PNG)

Shown here, the lowest mean is within April for OOSM, and May for OSSM. As a range, this translates that lowest average rain rate was between April to May. The highest rain rate was within December for both OOSM and OSSM. Both have the highest rain rate within the Winter, however a low spike is in October which is unique to this time set. A ranking would be Winter, Fall, Spring then Summer for both locations. 

# Cross Correlation
> ![w_CC](https://github.com/calebkt/Project-2-Meteorology/blob/master/P2_Pictures/w_cc.PNG)
> ![r_CC](https://github.com/calebkt/Project-2-Meteorology/blob/master/P2_Pictures/r_cc.PNG)

In plotting cross-correlation for wind speed between both sites, the max correlation is at 0.6314. With this, the lag is zero as the data is highly similar and correlated to one another. 

> ![base_cc](https://github.com/calebkt/Project-2-Meteorology/blob/master/P2_Pictures/base_cc.PNG)
> ![prep_cc](https://github.com/calebkt/Project-2-Meteorology/blob/master/P2_Pictures/prep_cc.PNG)

In plotting the cross correlation for rain rate, max correlation is at 0.3516. With this, the lag is at 341; equal to 124 days.

This data expresses that OSSM and OOSM share similar wind speeds throughout the year. Rain rates however differ slightly with a vastly larger time lag then wind speed. In this case, correlation between wind speed and rain rate in terms of time lag based within regard towards rain rate has a lower correlation. 
