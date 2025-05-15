# QGIS 2025 - Working with Point Cloud Data in QGIS
Home page for the workshop

### Description
This workshop will teach you how to work with point cloud data in QGIS. You will learn how to visualize point clouds in both 2D and 3D, style them to highlight important features, and process and edit them to extract meaningful information. The workshop will cover topics such as:

* Loading and displaying point clouds in QGIS.
* Navigating and interacting with point clouds in 2D and 3D.
* Creating profiles and cross sections.
* Styling point clouds using different attributes and color palettes.
* Filtering and clipping point clouds to focus on specific areas of interest.
* Performing basic point cloud processing tasks, such as calculating point density and creating digital elevation models.
* Editing point clouds to remove noise or correct errors.

By the end of this workshop, you will be able to use QGIS to effectively visualize, analyze, and process point cloud data.

#### Software
To participate in this workshop, you will need a minimum of QGIS 3.42 Münster. This is the latest stable release of QGIS and importantly includes some of the new point 
cloud editing features. However, ideally install the QGIS Nightly release (3.43.x). This release will be important for the Editing section. You can download it from 
the [official QGIS website](https://qgis.org/) or by using the OSGeo4W installer. For MacOS users, try to download and install the DMG file from this pull request. For Debian based users, 
you can use QGIS Flatpack or change the repo. During the workshop you can use your own point cloud data or the open data that we will provide.
We will provide the data for the workshop.

### Instructors
This workshop has been developed by Kurt Menke and Saber Razmjooei for the QGIS User Conference 2025, in Norrköping, Sweden from 2-3 June 2025.

**Kurt Menke** - In early 2021, Kurt moved from the USA to Denmark and now works for [Septima P/S](https://septima.dk/) in Copenhagen, Denmark. He earned a Master in Geography from the 
University of New Mexico in 2000. He has a broad skillset. He is a spatial analyst, cartographer, trainer/teacher and author. He has published many QGIS books, the most recent being: 
[Discover QGIS 3.x - Second Edition](https://locatepress.com/book/dq32), [QGIS for Hydrological Applications - Second Edition](https://locatepress.com/book/hyd2), and 
[Field Data Collection with QGIS and Mergin Maps](https://locatepress.com/book/mergin-maps) all with [Locate Press](https://locatepress.com/). He was elected as an OsGeo Charter Member 
in 2015. He is also a fellow of the [Rewilding Institute](https://rewilding.org/) and a board member of [Wild Arizona](https://www.wildarizona.org/).

**Saber Razmjooei** - Saber is a one of the [Lutra Consulting](https://www.lutraconsulting.co.uk/) co-founders. Lutra is an active member of QGIS development community.

### Introduction - What is a point cloud?
Point cloud datasets consist of a collection of points in 3D space (up to billions, even trillions), collected using laser scanning (LiDAR) or photogrammetry. LIDAR is an acronym for 
*"light detection and ranging"*. It is remote sensing technology that uses lasers to measure distances to reflective surfaces. The density of points can vary, 
providing detailed information about the scanned area. Additionally, point clouds have attributes including X, Y and Z coordinates, a classification and intensity. 

Point clouds can be used to visualize the landscape including built features and vegetation. Attributes can be used to style the points in different colors. By using the variety of 
QGIS point cloud rendering settings you can highlight many different aspects of the terrain. Point clouds can be viewed in both the 2D Map Canvas and the 3D viewer. They can also 
be used with Elevation Profiles to show the cross section of a point cloud where measurements can be made between points. One can also interact with point cloud data using the Identify 
features tool. This tool works in the 2D Map Canvas, within Elevation profile plots and 3D views. 

#### Point Cloud Supported Formats
QGIS supports the industry standard file formats *.las and the compressed *.laz. QGIS also provides support for reading Cloud Optimized Point Clouds (COPC) from local and remote data sources. 
Support for point cloud data was added at QGIS version 3.18 in the spring of 2021. New point cloud functionality has been added at nearly each release since, including the most recent 
QGIS 3.42 Münster. The most recent functionality introduced, is the ability to edit point cloud datasets. The main editing functionality was introduced at QGIS v 3.42 and there will be additional 
editing features added at QGIS 3.44. You will learn how to edit point clouds at the end of the workshop. 

### Workshop Data
Download this [zip file](https://drive.google.com/file/d/1q5q0uSJii9htEKU8r99o9R6i51P3MSkS/view?usp=sharing). Extract the zip archive in a dedicated folder on your hard drive.

### Tutorial
The tutorial can be accessed via this [link](https://docs.google.com/document/d/1hWMghUmzSkYkUm4cvnHn2DKLEzGdnxf6dnSMIHNWNfM/edit?usp=sharing)

### Outline

##### 1 - Loading and Styling Point Clouds in 2D
##### 2 - Viewing Point Clouds in 3D
##### 3 - Creating and Using Virtual Point Clouds (VPCs)
##### 4 - Using Point Cloud Processing Tools
##### 5 - Editing Point Clouds
##### 6 - Using PDAL Wrench
