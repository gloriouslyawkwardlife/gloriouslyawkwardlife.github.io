---
title: Hurricane Milton
date: 2024-10-08
layout: page
author: Steven Buehler
---

**Update 9 Oct 2024 @ 8:30 PM:** <https://twitch.tv/gloriouslyawkwardlife> is currently streaming the balcony cam with weather radar for as long as there is power and connectivity.

<h2>Detailed Graphic</h2>

<p align="center">
    <image src="https://www.wolframcloud.com/obj/queuegulper0j/milton.png" />
</p>

This image is generated from KML files provided by the <a href="https://www.nhc.noaa.gov">National Hurricane Center</a> every six hours, shortly after 5:00 and 11:00 AM and
5:00 and 11:00 PM Eastern Daylight Time (0300, 0900, 1500, and 2100 UTC). If the image is old you may need to clear your browser's cache and reload.

This image is generated using [WolframScript](https://www.wolfram.com/wolframscript/) and the [Wolfram Language](https://www.wolfram.com/language/).

## How to read this
 - There is a faint blue shaded **cone of uncertainty** around the track line. *You should not focus on the track line itself,
   as the center of the storm can go anywhere within the cone.*

 - The colored areas around each point are the anticipated wind fields for each quadrant of the storm at that point in the forecast. The colors
   represent sustained winds of at least **34 knots** (39 mph or 63 km/hr) in yellow, **50 knots** (58 mph or 94 km/hr) in red, and **64 knots** (74 mph or 119 km/hr) in dark red. These are *sustained* wind speeds; wind *gusts* can be signficantly higher.
   
 - The blue marker in the middle of the state is my location about 12 miles/19.31 km south of Clermont, Florida.

## Meteograph

<p align="center"><img src="https://forecast.weather.gov/meteograms/Plotter.php?lat=28.3563&lon=-81.6823&wfo=MLB&zcode=FLZ144&gset=18&gdiff=3&unit=0&tinfo=EY5&ahour=0&pcmd=11101111110000000000000000000000000000000000000000000000000&lg=en&indu=1!1!1!&dd=&bw=&hrspan=48&pqpfhr=6&psnwhr=6"></p>

Above is a *meteograph*, which shows a detailed forecast over the next 48 hours at my location. This is generated in real-time by the [National Weather Service](https://www.weather.gov). 

## Wind scales

| Type | knots | mph | km/hr |
|------|:-------:|:-------:|:-----:|
| Tropical Depression | &le;33 | &le;38 | &le;61 |
| Tropical Storm* | 34&ndash;63 | 39&ndash;73 | 63&ndash;118 |
| Category 1 Hurricane | 64&ndash;82 | 74&ndash;95 | 119&ndash;153 |
| Category 2 Hurricane | 83&ndash;95 | 96&ndash;110 | 154&ndash;177 |
| Category 3 Hurricane | 96&ndash;112 | 111&ndash;129 | 178&ndash;208 |
| Category 4 Hurricane | 113&ndash;136 | 130&ndash;156 | 209&ndash;251 |
| Category 5 Hurricane | &ge;137 | &ge;157 | &ge;252 |

\* The storm is given a name at this point. Tropical Depressions are numbered.

Categories 3 and higher are considered _major_ hurricanes.

## Terminology

Many of the forecasts indicate wind speed in *knots* and distance in *nautical* rather than *statute* miles (statute miles are what we're used to).

A *nautical mile* is defined as one minute (one 60<sup>th</sup> of a degree) of latitude at the equator. This has been standardized to 1,852 meters, or 1.151 statute miles per nautical mile.

A *knot* is defined as one nautical mile per hour, standardized to 1.852 km/hr or about 1.15078 miles per hour.