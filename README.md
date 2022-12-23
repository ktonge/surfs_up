# Surfs Up
## Overview
For this week's lesson in our bootcamp, we were tasked with helping an hypothetical investor gather information about opening a surf and ice cream shop in Oahu, Hawaii.  Our goal was to determine if a shop would have appropriate weather to be open year-round.  

## Results
In our analysis we took sqlite weather data information and manipulated it to focus on June and December as our representatives for summer and winter months.  
### Summer
The maximum temperature we saw in the data was 85 degrees, with the mean temperature being 74.9 degrees and a standard deviation of 3.2 degrees.  This is a good sign for a surf shop.  
[photo]

### Winter
The information for December was very similar.  The mean temperature was 71 degrees, with a standard deviation of 3.7.  This does show that there is potentially more variance in weather in the winter months.  The minimum temperature being 56 degrees, however its important to take into account that generally the minimum temperature for the day happens at nighttime.
[photo]

### Comparing the Seasons
Overall,  there being consistently comfortable weather in both June and December would be beneficial to a combination ice-cream shop and surf shop.  
- The largest difference between June and December was the difference between minimum temperatures, with June having a minimum temperature of 64 degrees and December being 56 degrees.  
- The mean temperature for June is within one standard deviation of the mean temperature for December.  The mean temperature for december is greater than one standard deviation below the mean temperature for June.  
- The maximum temperature for June was 85 degrees, and the maximum temperature for December was 82 degrees.  

## Summary
Overall, the weather data we looked at had positive results for the business proposal, however I would say the queries were extremely limited.  

### Additional Queries
With the data given to us,  I additionally looked into parcipitation information.  From what I understand winter in tropical climated like Hawaii typically doesn't look as cold as say, the weather in my local New England, but it can look more like a wet season and dry season. This was at least somewhat supported by the data
[photos]
There were significantly more differences between precipitation in June and December than there were between temperature.  The mean was almost twice as high in December (.21, versus .13 in June).  The maximum precipitation was 6.42 in December, versus 4.43 in June.  

### Further Research
While average temperatures didn't show a dramatic change over the year,  it would be interested to see the temperatures specifically during the day, perhaps at noon and 5 (or whenever surfing and ice cream are most popular).  

While precipitation is one way to look at the weather I would be interested in seeing more information about the wind and surfing conditions.  

Joining this database with a database of information about tourism and population might also provide additional insight.  
