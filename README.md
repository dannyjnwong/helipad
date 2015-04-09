# helipad
Analysing helipad data at KCH using R and QGIS.

##Data Analysis Plan and To Dos:

1. [ ] Clean the data 
  * [ ] Remove empty rows with empty Grid References
  * [ ] Format dates and time into R-compatible date-time object
  * [ ] 
  
2. [ ] Map the data
  * [x] Convert OS Grid References into latitude and longitude (WSG84 CRF)
  * [x] Points overlayed over a basemap to see general distribution
  * [ ] Choropleth/Graduated circle map to show the relative frequencies of cases from individual counties
  * [ ] Distance analysis to show the median, mean and range of distances from which KSS HEMS patients originate
  * [ ] 
  
3. [ ] Time analysis
  * [ ] Days of the week (do we have a busiest day for HEMS cases coming to KCH?)
  * [ ] Time course and workload over time: pre- and post- George's and KCH Helipad construction
  * [ ] 
  
4. [ ] Patient characteristics
  * [ ] Descriptive statistics of injury severity (we may need ICNARC data)
  * [ ] Descriptive statistics of outcomes
  * [ ] 