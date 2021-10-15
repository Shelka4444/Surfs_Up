# Surfs Up Analysis 

## Overview of the analysis: Explain the purpose of this analysis.
  A business plan is in the works to open a surf and ice-cream shop on the beautiful island of Oahu. After looking over the prepared analysis, a potential investor will pitch the proposal to fellow shareholders. Using Jupyter Notebook and SQLAlchemy, this analysis provides detailed climate reports which will help determine whether or not the location of the surf ice-cream shop on Oahu will be a good investment. If the shop is a success, there is potential to open a chain of stores across the islands of Hawaii pending more analysis for each island.

## Results: Provide a bulleted list with three major points from the two analysis deliverables. Use images as support where needed.
<p align="center">
<img src="https://github.com/Shelka4444/Surfs_Up/blob/main/Resources/Jun_Dec_Temp.png" alt="June December Temperature Comparison" width=500>
</p>  

- The chart above compares temperatures for June and December on the island of Oahu. It is evident that the average temperature in June (74.9°F) is almost 4°F warmer than the average temperature in December (71.0°F).
- However, there is also more spread in the temperature ranges in December compared to June. In December, the range between the minimum (56.0°F) and maximum (83.0°F) is 27°F, while the range in June between the minimum (65.0°F) and maximum (85.0°F) is a 20°F difference.
- The standard deviation in December (σ = 3.75°F) is also greater than June (σ = 3.28°F) which reflects the greater difference in temperature fluctuations for the winter month.

## Summary: Provide a high-level summary of the results and two additional queries that you would perform to gather more weather data for June and December.

  Overall, the temperature on Oahu appears to range from cool in December (minimum 56.0°F) to hot in June (maximum 85.0°F) which suggest that surfing and ice-cream enthusiasts are likely to visit the proposed shop for the majority of days in the year. Even though the temperature analysis looks promising for this business venture, it is recommended to look at several other variables which may also influence the success of a shop on the island. </br>

  For instance, precipitation (as seen in the following table) can also influence how many people venture outside and pass by the shop. Though the precipitation levels on Oahu are unusually low for tropical islands, it is plausable that rainfall is much more substantial in other regions of Hawaii which can affect sales if the business expands to new locations in the future.
<p align="center">
<img src="https://github.com/Shelka4444/Surfs_Up/blob/main/Resources/June_Dec_Prcp.png" alt="June December Precipitation Comparison" width=500>
</p> </br>

  Another consideration for the pending operation is the variability of the average temperatures for June and December per each station on the island (see table below). The variability from station to station is notable. The average temperature in June ranges from 71.9°F (station USC00516128) up to 77.6°F (station USC00519397). The December average temperature also varies from 69.3°F (station USC00516128) to 73.2°F (station USC00514830). It is possible that there is an ideal temperature range to consider when picking the perfect business location on the island. 
<p align="center">
<img src="https://github.com/Shelka4444/Surfs_Up/blob/main/Resources/Station_Temp.png" alt="Station Avg Temp Comparison" width=500>
</p> </br>

  Other climate factors besides temperature and precipitation may also be worthwhile variables to consider. Humidity, ocean temperatures, ocean swells, and beach condition can have an affect on surfing ability. In a similar vein, knowledge of accesibility to the shop, town proximity and size, general surfing and ice-cream trends on the island, and competitor success and failure rates would be good to investigate further in order to develop a fully comprensive business plan before launching the proposed shop.
