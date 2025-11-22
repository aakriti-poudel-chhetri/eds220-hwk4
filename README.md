# EDS 220 - Assignment 4

This repository contains materials for the fourth assignment for the course [EDS 220 - Working with Environmental Datasets](https://meds-eds-220.github.io/MEDS-eds-220-course/). This course is part of the [UCSB Masters in Environmental Data Science](https://bren.ucsb.edu/masters-programs/master-environmental-data-science).

## Background

In early January 2025, the Eaton Fire and Palisades Fire ignited almost simultaneously in the foothills and coastal wildland–urban interface zones of Los Angeles County, driven by intense Santa Ana winds. Together, the two fires destroyed thousands of homes, displaced tens of thousands of residents, and caused extensive ecological and infrastructural damage.

False color imagery generated using satellite data from instruments such as Landsat—is a valuable tool for assessing wildfire impacts. By assigning infrared spectral bands to visible colors, these images reveal vegetation health, burn severity and the spatial extent of fire scars. This technique enables researchers and land managers to evaluate ecosystem recovery, identify high-risk zones, and inform restoration and mitigation strategies.

In this task, we will produce a false-color image of the Eaton and Palisades Fires using remote sensing data, highlighting the burn scar and demonstrating how coding and data visualization support environmental monitoring.

![](https://freeseandgoss.com/wp-content/uploads/2025/01/palisades-and-eaton-fires--scaled.jpeg)

## Repository Structure
```
eds220-hwk4
│--  README.md
│--  hwk4-task2-false-color-YOURLASTNAME.ipynb
|--  .gitignore
```

## Data

Due to the large size of data, the data folder is included in .gitignore and is not tracked by version control.

In this assignment, we will be using the following datasets.

- **Simplified collection of bands from the Landsat Collection 2 Level-2**
The first dataset is a simplified collection of bands (red, green, blue, near-infrared and shortwave infrared) from the Landsat Collection 2 Level-2 atmosperically corrected surface reflectance data, collected by the Landsat 8 satellite.

The data was retrieved from the [Microsof Planetary Computer data catalogue](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2) and clipped to an area surrounding the fire perimeters.

- **Fire perimeters for the Eaton and Palisades fires**
The second dataset is of fire perimeters for the Eaton and Palisades fires, and is retrieved from the [County of Los Angeles Open Data](https://data.lacounty.gov/). The data can be accessed from the [link](https://data.lacounty.gov/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about).

## Data Citation
*Landsat Collection 2 Level-2*. Microsoft Planetary Computer. Retrieved 15 Nov, 2025. https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2.

*Palisades and Eaton Dissolved Fire Perimeters*. (2025) County of Los Angeles Open Data. https://data.lacounty.gov/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about.

*Why Is That Forest Red and That Cloud Blue?*. (2014, March 4). NASA Earth Observatory. https://earthobservatory.nasa.gov/features/FalseColor.

*What Are the Band Designations for the Landsat Satellites?*.(2025, July 11). U.S. Geological Survey. https://www.usgs.gov/faqs/what-are-band-designations-landsat-satellites.

*Common Landsat Band Combinations*. (2021, November 12). U.S. Geological Survey. https://www.usgs.gov/media/images/common-landsat-band-combinations

## References

### Course Information
 - **Course Title:** EDS 223 - Geospatial Analysis & Remote Sensing
- **Term:** Fall 2025

#### Teaching Team:
- **Instructor:** Dr. Carmen Galaz García

- **Co-instructor**: Dr. Annie Adams

Complete description for the homework can be found on the [Assignment-4](https://meds-eds-220.github.io/MEDS-eds-220-course/assignments/assignment4-palisades.html).

**Author:** Aakriti Poudel