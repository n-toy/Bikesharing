# NYC Citi Bike Analysis

# Resources
Software: Tableau
Data: NYC Citi Bike Dataset, New York McDonalds Dataset, Des Moines McDonalds Dataset

## Project overview
  The goal is to convince investors that a bike-sharing program in Des Moines to be a successful or unsuccessful venture. Through storytelling in Tableau it is found that setting up a bike share program in Des Moines will most likely not be successful. 
  
## Bike sharing Story
  * Link to the Bike sharing Tableau Story: https://public.tableau.com/profile/nathan.toy#!/vizhome/BikeSharing_15976417364420/CitiBike?publish=yes
  
### Analysis of Citi Bike in New York. How Valuable would Citi Bike be in Des Moines? 
  * This is an overview slide showing the boroughs of New York. The NY Citi Bike data covers the boroughs: 
    * Brooklyn
    * Manhattan
    * Queens
    * Unknown
    * Null
  * The boroughs are not originally in the NYC Citi Bike dataset, and is joined on from a flat file that maps zip code to borough

### NYC Citi Bike Data Breakdown
  * This is a slide that begins the breakdown of the data available from number of trips to a visual overlay of actual trips in NYC
  * On this sheet are:
    * A graph showing that younger riders have the most frequent trips. There is an outlier for those born on 1969 with over 280,000 trips. 
    * A Gender split pie chart showing that 65% of riders are male
    * A map overlay of trips in the dataset showing that Manhattan has extreme trip density. This also forces our perspective of the type of location that is Manhattan versus the type of location that is Des Moines.
 
### How does Des Moines and New York compare? 
  * This slide begins a breakdown of how Des Moines and New York are radically different cities. 
    * Using the US Census data we can tell the gender split differences between both cities. Des Moines shows to have a slightly higher percentage of Males in the city. This supports that there would be minor success of a Bike Share in Des Moines since in NYC the percentage of riders is 65% Male. 
    * From the US Census we can also tell the population per Square Mile, and can clearly see that Des Moines is very sparse compared to New York. This alone brings into question the effectiveness of a Bike Share. A Bike Share makes better sense for locations with very high density of buildings/population, but wouldn't if population was spaced out. Riders would opt for different methods of transportation because of longer distances between areas. 
    
### McDonalds Density
  * This slide is to study the effect of McDonalds on Bike Share trips, and whether it corresponds to higher traffic. On this slide is:
    * An overlay of McDonalds in New York
    * An overlay of New York Trip End locations
  * A quick visual analysis of looking between both overlays shows that there doesn't seem to very much correlation between McDonalds and trips in the surrounding area. There is however one hotspot on 31st St and 8th Ave that needs to be unpacked and looked at. 

### Is the reason for activity McDonalds?
  * Lets zoom in on the hotspot activity found by visually analyzing the overlays. 
    * There are 4 McDonalds clustered together tied to some of the most popular trip ending spots
    * It looks like there is a large concentration of trips ending here because of the New York Penn Station, and 34th Street - Penn Station Transportation centers
      * This most likely is the reason for high trip counts!
      * Looking at all other McDonalds in New York there aren't outlier number of trips being done in their area. 
    * Analysis of the ride trip data there is a clear resolve that McDonalds doesn't affect number of trips being done via Citi Bike
    
## Summary
  After visualizing and analyzing the NYC Citi Bike dataset, and stipulating Citi Bike's success in the area there is little data that supports an expansion into Des Moines. This conclusion is reached after looking at US Census data, and McDonalds locations for both areas. The US Census data shows that New York is much denser compared to Des Moines, and is a contributing in NYC Citi Bike being a success. We also see that McDonalds in New York have no effect on Citi Bike Trip Ending locations--in other words Riders are not hopping on Citi Bike to go to McDonalds. 
      
      
  


