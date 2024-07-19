# Introduction

Before moving to detailed parts, it would be better that we go through some of the important terms.

## Digital Surveying

According to Marriam-Webster dictionary, there are a couple definitions on what is *surveying*.

-
    - *to examine as to condition, situation, or value : APPRAISE*.
    - *to query (someone) in order to collect data for the analysis of some aspect of a group or area*

- to determine and delineate the form, extent, and position of (such as a tract of land) by taking linear and angular measurements and by applying the principles of geometry and trigonometry.

To merge what we know so far, we can say that the **digital surveying** is the work of using digital technology and tools to survey; accurately determining the virtual points on the surface of the earth, so that measuring the *angles*, *distances* and *elevations* between each other.

## Photogrammetry

Photogrammetry has been defined by the American Society for Photogrammetry and Remote Sensing as the art, science, and technology of obtaining reliable information about physical objects and the environment through processes of recording, measuring, and interpreting photographic images and
patterns of recorded radiant electromagnetic energy and other phenomena. 

The invention of the airplane by the Wright brothers in 1903 provided the great impetus for the emergence of modern aerial photogrammetry. Until that time, almost all photogrammetric work was, for the lack of a practical means of obtaining aerial photos, limited to terrestrial photography. The airplane was first used in 1913 for obtaining photographs for mapping purposes. Aerial photos were used extensively during World War I, primarily in reconnaissance. In the period between World War I and World War II, aerial photogrammetry for topographic mapping progressed to the point of mass
production of maps. Within this period many private firms and government agencies in North America and in Europe became engaged in photogrammetric work. During World War II, photogrammetric techniques were used extensively to meet the great new demand for maps. Air photo interpretation was also employed more widely than ever before in reconnaissance and intelligence. Out of this war-accelerated mapping program came many new developments in instruments and techniques.

![The Ju88D-1](/images/recon.jpg)

The Ju88D-1, German aerial reconnaisance plane.

Advancements in instrumentation and techniques in photogrammetry have continued at a rapid pace through the remainder of the 20th, and into the 21st century. The many advancements have collectively enabled photogrammetry to become the most accurate and efficient method available for compiling maps and generating topographic information. The improvements have affected all aspects of the science, and they incorporate many new developments such as those in optics, electronics, computers and satellite technology.

The two fundamental types of photography used in the science of photogrammetry are *terrestrial* and *aerial*. Company is working with aerial photos as it currently has two active planes, Navajo and Bonanza. With the airborne digital sensors mounted on the planes company obtains and evaluates the aerial photographs in the process of making a map.

## Topography

![topo-1](/images/topo-mesh.jpeg)

Topography is the study of the forms and features of land surfaces. The topography of an area may refer to the land forms and features themselves, or a description or depiction in maps.<sup>[[1](https://www.wikiwand.com/en/Topography)]</sup>.

![topo-2](/images/abstract-topographic-map.jpg)

Topography is a field of geoscience and planetary science and is concerned with local detail in general, including not only relief, but also natural, artificial, and cultural features such as roads, land boundaries, and buildings. In the United States, topography often means specifically relief, even though the USGS topographic maps record not just elevation contours, but also roads, populated places, structures, land boundaries, and so on (This also counts for the company, using several softwares like Vr One & Microstation).

<!-- company image (belki ldl126) -->

## Cartography

From [Encyclopedia Britannica](https://www.britannica.com/):
<br>
<br>
Cartography, the art and science of graphically representing a geographical area, usually on a flat surface such as a map or chart. It may involve the superimposition of political, cultural, or other nongeographical divisions onto the representation of a geographical area.

![Ottoman Empire](/images/ottoman.jpg)

Above, Turcici Imperii Descriptio, is the early Ottoman Empire's map, made by [Abraham Ortelius](https://www.wikiwand.com/en/Abraham_Ortelius), one of the most renowned cartographers in europe.

## LiDAR

LiDAR is an acronym for Light Detection and Ranging. In LiDAR, laser light is sent from a source (transmitter) and reflected from objects in the scene. The reflected light is detected by the system receiver and the time of flight (TOF) is used to develop a distance map of the objects in the scene.

LiDAR is an optical technology often cited as a key method for distance sensing for autonomous vehicles. Many manufacturers are working to develop cost-effective, compact LiDAR systems. Virtually all producers pursuing autonomous driving consider LiDAR a key enabling technology, and some LiDAR systems are already available for Advanced Driver Assistance Systems (ADAS).

![LiDAR](/images/lidar-montage.jpg)

A LiDAR instrument principally consists of a laser, a scanner, and a specialized GPS receiver. Airplanes and helicopters are the most commonly used platforms for acquiring LiDAR data over broad areas. Two types of LiDAR are topographic and bathymetric. Topographic LIDAR typically uses a near-infrared laser to map the land, while bathymetric lidar uses water-penetrating green light to also measure seafloor and riverbed elevations.

LiDAR systems allow scientists and mapping professionals to examine both natural and manmade environments with accuracy, precision, and flexibility. NOAA scientists are using LIDAR to produce more accurate shoreline maps, make digital elevation models for use in geographic information systems, to assist in emergency response operations, and in many other applications.

![LiDAR](/images/point-lidar.png)

Lidar is used to measure things such as:

- range and altitude
- atmospheric vertical profiles of aerosols and trace - gas densities
- temperature
- cloud cover
- wind velocity
- shape and size of landscape features
- height and density of forests
- sea surface roughness

## Digital Modeling of the Earth

### Digital Terrain Model

Defining what a *digital terrain model* (DTM) is not simple because there is no universal agreement, neither among practitioners nor in the scientific literature. Different terms are used, often interchangeably.

In most cases, we can state that:

- A digital terrain model is a representation of the Earth’s surface. It gives us the
*elevation*, which is the height above / below a certain reference point (a vertical datum). 

However, the “Earth’s surface” is also not a clear concept, since several objects on it can be
present, eg man-made structures like buildings, roads, power lines, and bridges, and other
objects like trees.

From other perspective, this is a term used to describe mathematical representation of a continuous surface of the ground using $X,$ $Y,$ $Z$ coordinates.

In the United States and other countries, a DTM has a slightly different meaning. A DTM is a vector data set composed of regularly spaced points and natural features such as ridges and breaklines. A DTM augments a DEM by including linear features of the bare-earth terrain.

### Digital Surface Model

A digital surface model (DSM) is a three-dimensional representation of the heights of the Earth's surface, including natural or man-made objects located on it. It represents the mean sea level elevations of the reflective surfaces of vegetation, buildings, and other features elevated above the bare earth. It is usually considered as a model of a canopy over the surface of the bare earth. A DSM captures the natural and built features on the Earth’s surface.

Because DSMs depict the bare-earth + all of the earth's above-ground features, they are particularly significant in urban planning. 3D surface models can help in analyzing complex urban scenarios, especially as built-up regions change over time due to urban expansion.


### Digital Elevation Model

DEM, the digital elevation model is simply a 3D representation of a terrain's surface which is usually represented as a raster grid. At each pixel there's a specific information about the elevation (z-value at regularly spaced intervals) at that point. DEM depicts a *bare-earth*.

The word *elevation* emphasizes the measurement of height above a datum and the absolute altitude or elevation of a point in the model. The datum is often elevation-zero. The points are those residing on the surface of the ground.

Therefore digital elevation model (DEM) is a gridded raster data and a three-dimensional representation of a terrain, which filters out and excludes terrain vector features (i.e. streams, breaklines, and ridges) and all ground objects, both built (power lines, buildings, and towers) and natural (trees and other types of vegetation).

To put short,

- **DEM** (**D**igital **E**levation **M**odel). In the literal meaning of the term, it is simply a model of the
elevation. A DEM is either a DSM or a DTM.

- **DTM** (**D**igital **T**errain **M**odel). The surface of the Earth is the bare-earth, that is no man-made
objects or vegetation is present.

- **DSM** (**D**igital **S**urface **M**odel). The surface includes all objects and structures on the terrain.

## Triangular Irregular Networks

A triangulated irregular network (TIN) is a representation of a continuous surface consisting entirely of triangular facets (a triangle mesh), used mainly as Discrete Global Grid in primary elevation modeling.

The vertices of these triangles are created from field recorded spot elevations through a variety of means including surveying through conventional techniques, Global Positioning System Real-Time Kinematic (GPS RTK), photogrammetry, or some other means. Associated with three-dimensional $(x, y, z)$ data and topography, TINs are useful for the description and analysis of general horizontal $(x,y)$ distributions and relationships.

Digital TIN data structures are used in a variety of applications, including geographic information systems (GIS), and computer aided design (CAD) for the visual representation of a topographical surface. A TIN is a vector-based representation of the physical land surface or sea bottom, made up of irregularly distributed nodes and lines with three-dimensional coordinates $(x, y, z)$ that are arranged in a network of non-overlapping triangles.

A TIN used to represent terrain is often called a digital elevation model (DEM), which can be further used to produce digital surface models (DSM) or digital terrain models (DTM). An advantage of using a TIN over a rasterized digital elevation model (DEM) in mapping and analysis is that the points of a TIN are distributed variably based on an algorithm that determines which points are most necessary to create an accurate representation of the terrain. Data input is therefore flexible and fewer points need to be stored than in a raster DEM, with regularly distributed points. While a TIN may be considered less suited than a raster DEM for certain kinds of GIS applications, such as analysis of a surface's slope and aspect, it is often used in CAD to create contour lines. A DTM and DSM can be formed from a DEM. A DEM can be interpolated from a TIN.

![Triangular Irregular Network](/images/digitales_geländemodell.png)

TIN are based on a Delaunay triangulation or constrained Delaunay. Delaunay conforming triangulations are recommended over constrained triangulations. This is because the resulting TINs are likely to contain fewer long, skinny triangles, which are undesirable for surface analysis. Additionally, natural neighbor interpolation and Thiessen (Voronoi) polygon generation can only be performed on Delaunay conforming triangulations. A constrained Delaunay triangulation can be considered when you need to explicitly define certain edges that are guaranteed not to be modified (that is, split into multiple edges) by the triangulator. Constrained Delaunay triangulations are also useful for minimizing the size of a TIN, since they have fewer nodes and triangles where breaklines are not densified.
