[<<< Previous](3layer1.md)  | [Next >>>](5attrib.md)  

# Bonus! GIS Glossary

**Attribute**: a characteristic of a feature. Attributes can contain data of different types: strings (text), numerical values, dates, or booleans. Each column in the Attribute Table represents a different attribute.

**Feature**: an element that appears in a layer and typically has attributes. Each row in the Attribute Table represents a different feature. Each feature can be represented on a map by one (or more) vectors, be it points, lines or polygons.

**Georeferencing**: the process of using geographic data to represent features on a GIS.

**Layers**: are "containers" of the data in QGIS. On the map view, layers can be imagined as transparent film sheets that are laid one over another. With the exception of raster layers, each layer contains an Attribute Table, that is, a series of features that in turn have their own attributes. Vector layers can only contain one type of vectors, be it: points, lines or polygons.

**Polygon**: a figure with three or more sides. In GIS, it usually refers to complex areas outlining lakes, city blocks, a set of buildings, or other complex features of the map, that can be outlined using interconnected points. A polygon can have an unlimited amount of points. The more points (or "higher the resolution"), the smoother the polygon will look to the human eye.

**Raster**: images of a specific location that represent visually continuous data such as temperature and elevation at a given resolution. Higher resolutions mean more precision but also larger file size. Raster layers have no Attribute Table; the values are stored within the image and represented as different hues or colors. Raster images can also be used for reference or aesthetic purposes (e.g. satellite photos).

**Vector**: a scalable point, line or polygon that can be easily created, edited, or deleted using GIS. Does not have a specific resolution. In QGIS, vectors are contained in vector layers, that can only contain a single type of vectors. Each vector represents a single feature, although some features may be represented by more than one vector (e.g. the vector of the United States includes the mainland U.S. polygon but also polygons for Alaska and Hawaii).


[<<< Previous](3layer1.md)   
