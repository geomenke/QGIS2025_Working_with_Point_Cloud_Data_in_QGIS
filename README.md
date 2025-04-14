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
To participate in this workshop, you will need QGIS 3.42 Münster. This is the latest stable release of QGIS and importantly includes most of the new point cloud processing features. You can download it from the [official QGIS website](https://qgis.org/) or by using the OSGeo4W installer. During the workshop you can use your own point cloud data or the open data that we will provide.


### Instructors
This workshop has been made by Kurt Menke and Saber Razmjooei for the QGIS User Conference 2025, in Norrköping, Sweden from 2-3 June 2025.

**Kurt Menke** - In early 2021, Kurt moved from the USA to Denmark and now works for [Septima P/S](https://septima.dk/) in Copenhagen, Denmark. He earned a Master in Geography from the University of New Mexico in 2000. He has a broad skillset. He is a spatial analyst, cartographer, trainer/teacher and author. He has published many QGIS books, the most recent being: [Discover QGIS 3.x - Second Edition](https://locatepress.com/book/dq32), [QGIS for Hydrological Applications - Second Edition](https://locatepress.com/book/hyd2), and [Field Data Collection with QGIS and Mergin Maps](https://locatepress.com/book/mergin-maps) all with [Locate Press](https://locatepress.com/). He was elected as an OsGeo Charter Member in 2015. He is also a fellow of the [Rewilding Institute](https://rewilding.org/) and a board member of [Wild Arizona](https://www.wildarizona.org/).

**Saber Razmjooei** - Saber is a one of the [Lutra Consulting](https://www.lutraconsulting.co.uk/) co-founders. Lutra is an active member of QGIS development community.

### 1- Loading and Styling Point Clouds in 2D
* Behavior on load the first time
* Layer properties and Information processing algorithm
* Rendering in 2D
* Extent only
* Attribute by ramp
* RGB
* Classification
* Point symbol options
* Render as a surface
* Draw order
* Working with Elevation Profiles

### 2- Viewing Point Clouds in 3D
* Styling settings
* Eye dome lighting | Show shadows | Ambient occlusion
* Navigation
* Exporting still frames for an animation

### 3- Creating and Using Virtual Point Clouds (VPCs)
Point cloud data is often provided in tiles. After downloading the tiles you need to merge them for further analysis. With virtual point clouds, you don't need to physically merge the tiles. You instead create a VPC which is a JSON file with a .vpc extension. It is a similar concept as virtual rasters. The VPC references a set of point cloud files (*.LAZ, *.LAS, *.COPC). This allows you to work with the VPC as if you have merged all the input tiles. This can reduce the amount of disk space needed for intermediate results.

### 4- Using Point Cloud Processing Tools (Clip - Filter - Export to Raster)
* Clip
* Filter
* Export to Raster
* Style DEM
* Calculating point density

### 5 - Editing Point Clouds

### 6 - Using PDAL Wrench
