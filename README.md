# avwx
aviation weather

## Basic Idea
Have a central location for metar data, readily available to multiple end points

## Code overview
### avwx\_ore
avwx\_ore will get the metar data, ungiggle it, parse it, and shove it in dynamodb.

#### avwx\_core walk through
1.  Download metar from https://aviationweather.gov/adds/dataserver\_current/current/metars.cache.csv.gz
2.  Uncompress it
3.  Break data out into list or array
4.  Work on it.