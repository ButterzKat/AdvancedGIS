

# Predicting COVID19 Outbreaks in Ukraine Post-Invasion 

 Jonathan Reisher
 Carnegie Mellon University
                                              

**The Problem**

The World Health Organization (WHO) assess that COVID19 will continue to spread and add to the already high death toll that is a result of the February 24th Russian invasion of Ukraine.  Furthermore, Ukraine’s population is only 34% vaccinated and surround countries like Moldova is just over 24% vaccinated while Poland is around 60%.  The rapid movement of civilians, soldiers, and refugees will only exacerbate not only the effect of COVID19 on Ukraine but also the region. Understanding how COVID19 is spreading in the context of the evolving conflict is paramount to decreasing the impact and providing lifesaving aid. 

**Background: Assessing Disease in Cuba during the Spanish American War**

A 1999, geospatial study conducted by the Royal Geography Society, studied the propagation of three infectious diseases (enteric fever, smallpox, and yellow fever) from 1895 to 1898 in Cuba during the Spanish American War.  Compared to peacetime, the Cuban insurrection against Spanish rule and the subsequent American invasion not only shifted the epicenters of disease but rapidly accelerated transmission.  Conservative estimates place civilian deaths at 218,000 from 1895-1898.  The American Army lost 6,207 soldiers in Cuba, 5,509 of which died from disease. Spain fared far worse loosing 62,853 soldiers, 53,440 of which perished due to disease.  Death in war due to disease is an ancient phenomenon however researchers are just recently using geospatial analysis to ascertain how sickness spreads and kills in conflict zones. 

**Methodology: Centroids and Hotspot Analysis**

This study on COVID19 in Ukraine post-2022 Russian invasion sought to provide humanitarian organizations and Ukrainian policy makers information on the location and magnitude of COVID19 outbreaks during active combat operations. To create the pre and post invasion hotspot maps in Figure 1, were created by taking the top 30 locations (centroids) in each time period that were weighted by various factors. The pre-invasion centroids were weighted using WHO COVID19 infection rates and multiplied by the populations of the 30 most populated Ukrainian cities from 2021.  This approach assumes that infection rate was constant over the past 23 months of data, incorporating seasonality of both the calendar year and virus variations. The post-invasion hot spot map used the top 30 locations of human activity, modeled after the Spanish American War Geospatial study, using Institute for the Study of War and New York Times estimates of locations of major fighting and refugee locations.  Furthermore, assumptions were made about the war time population of major city centers. The civilian population was estimated to be 40% of their pre-war population and military population was based on whether ISW maps suggested to the author the if the conflict was a division (20,000 total), brigade (10,000 total), or multiple battalion sized fight (5,000 total). These numbers are intended to be an estimate and should be updated as the conflict evolves.

 
   _Figure 1: Estimate of pre & post 2022 Russian Invasion COVID19 Hotspots_
  ![COVID Hotspots](/Pictures/COVID.jpg)
    
**Findings: COVID19 Clusters and Optimal Humanitarian Locations**

A lack of disaggregated data precluded the use of advanced geospatial prediction methods such as Forest-Based Classification and Regression to determine areas of future COVID19 outbreak in Ukraine. However, the data from the hotspot analysis supported the use of a density cluster-based analysis filters out the noise and provides clarity on the severity of future outbreaks. (See figure 2). The density clusters of COVID19 outbreak in Ukrainian held territory will occur around Kyiv, Kharkiv, Dnipro, Odessa, Zakarpattia Oblast and Vinnytsia Oblast. 

_Figure 2: Density Cluster Analysis of Worse Future COIVD19 Outbreaks in Ukraine_
![Density Clusters](/Pictures/Clusters.jpg)

The Optimal COVID19 Humanitarian Map (Figure 3) was made by using a combined road and railroad raster and then overlaying 25 km buffers over COVID19 clusters. The blue buffers on the map were further divided into buffers in Ukrainian and Russian control and filtered out if a recent major attack occurred within the buffer as determined by ACLED data.  The purpose is to provide humanitarian organizations an idea of where they could establish aid locations that are near major transportation, likely COVID19 outbreaks, and have not been targeted by recent Russian attacks. 

_Figure 3: Optimal COVID19 Aid Locations are Denoted in Blue_
![HA Locations](/Pictures/HA.jpg)

**Recommendations**
	
Based on the geospatial analysis presented in this paper the following recommendations are made for Ukrainian Government officials organizing COVID19 response and associated humanitarian locations:

•	Coordinate for COVID19 related humanitarian aid to areas near potential areas of high-density outbreak.
•	Implement COVID19 testing to track both soldiers and civilian transmission of the disease as the war evolves and human movement patterns changes.


Location of Map Packages are publicly available On Esri Online
Location of Original Research and Process Log is available [here](https://drive.google.com/drive/folders/1X3u7OzEkXFfGoG8fMCrUOGu44GkBk0YG?usp=sharing). 




    
 
