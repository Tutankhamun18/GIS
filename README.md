# GIS
notes and projects on GIS
## Chapter 1
Input data, analyze it -find geographic features, measure distance, compare pattern- and create output -maps-
Uses of GIS
*count,group, reclassify, isolate, quanity features and their patterns on a landscape
*measure lengths, widths, distances, heights and volumes of features
*overlay two maps to compare features and make a new map
*track movements and changes in patterns, predict and exploit pattern change
*visualize, interpolate, slice, cross section and generalize surfaces
**interpolate = predict missing values
*find shortest, fastest or most beautiful route, ID potential customers, and locate businesses
###Data
Primary Data:collected firsthand by you. Collected with goal in mind
Secondary Data: collected by others, not collected specifically for this project
GIS is
> a geographic analysis tool, a display and a representation tool.
>spatial patterns.
Data that you input into GIS needs: dimensionality and descriptions.
Types of Data:
*Points: Zero-dimensional features. Use points to represent geographic features on a map
*Lines: One-dimensional features or features that have length. Many line features also have width, but GIS assumes they don't.
*Polygons: Areas. Two dimensional areas can be used to measure perimeter, area, shape, longest and shortest axis.
**length
**width
*Surfaces: Three dimensional features.
**length
**width
**third dimension determined by the characteristics of a surface
Description types of data:
*Nominal: names only. Like place names.
*Ordinal: geographic features you can compare by rank. For example short, medium and tall trees, dirt roads, paved roads, highways and superhighways
*IntervaL: geographic features that have detailed increments that you can measure.
*Ratio: gepgraphic data with measurable units that allow you to make ratio comparisons.The key point is that ratio data have an absolute zero.
*Scalar: you can make your own scale that applies only to your data. For example, if you are ranking the beauty of a landscape from 1 to 10. First you must decide what each means.
##Chapter 2
Choosing the right symbol to presents a feature such as a town depends on the map's scale. A town could be both a point or an area feature.
*Datum: the baseline for measuring the Earth
>Your GIS software needs to know what datum youre using for each set of map data that you put into your database. 
>Attaching your coordinates to the wrong datum can result in location and measurement errors.