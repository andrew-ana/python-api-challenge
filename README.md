# Weather and Vacation Spots with Python API Calls
Andrew Anastasiades | @andrew-ana


### Interesting findings from Weather Data
1. The maximum temperatures found are actually slightly north of the equator. This is because during May, the northern hemisphere is actually closer to the sun
2. Cloudiness surprisingly isn't impacted by Latitude, I would have thought that it would correlate like temperature
3. Humidity correlates less than I would have expected.

A Literal heatmap with markers for hotels
A heatmap with this scope could probably be improved greatly by interpolation. We assume geo-spatial correlation between datapoints, and we know the temperature outside of colored areas is not absolute 0...

![alt text](https://github.com/andrew-ana/python-api-challenge/blob/main/Heatmap%20With%20Hotels.png)
