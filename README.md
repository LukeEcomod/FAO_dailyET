# FAO_dailyET
Estimates daily evapotranspiration from meterorological data using FAO 56 "standard"
Reference: Allen et al. 1998 FAO M-56: http://www.fao.org/3/X0490E/x0490e00.htm#Contents

Steps to estimate daily ET from meteorological station data in absense of radiation data:
    1) estimate net radiation balance in absense of direct measurements
    2) compute daily reference ETo
    3) compute actual evaporation as ETa = Kc x ETo

    The crop coefficient Kc should be determined against ET measurements from
    similar ecosystem; it is function of LAI, plant water use traits, albedo, soil moisture etc.

Step 1) can be omitted or modified if met. station provides radiation data or records sunshine hours

Tested part 1) with FAO -reference Example 16

Samuli Launiainen, Natural Resources Institute Finland. Apr 29th 2020
