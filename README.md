# EDS 220 - Assignment 4

This repository contains materials for the third assignment for the course [EDS 220 - Working with Environmental Datasets](https://meds-eds-220.github.io/MEDS-eds-220-course/). This course is part of the [UCSB Masters in Environmental Data Science](https://bren.ucsb.edu/masters-programs/master-environmental-data-science).

## About
In early January 2025, the Eaton Fire and Palisades Fire erupted nearly simultaneously in the foothills and coastal wildland-urban interface zones of Los Angeles County, fueled by powerful Santa Ana winds. Together, they devastated thousands of homes, displaced tens of thousands of residents, and inflicted severe ecological and infrastructural damage.

False color imagery, created using satellite data from instruments like Landsat, is a useful tool for monitoring wildfire impacts. By assigning infrared bands to visible colors, these images highlight vegetation health, burn severity, and the extent of fire scars. This approach helps researchers and land managers assess recovery efforts, identify high-risk areas, and plan restoration strategies.

In this task, we will create a false color image of the Eaton and Palisades Fires using remote sensing data, highlighting the fire scar and exploring how coding and data visualization support environmental monitoring.

## Repository Structure
```
eds220-hwk4
│--  README.md
│--  hwk4-task2-false-color-YOURLASTNAME.ipynb
|--  .gitignore
```

## Data

Due to the large size of data, the data folder is included in .gitignore and is not tracked by version control.


In this assigment, we are using two datasets. The first is a simplified collection of bands (red, green, blue, near-infrared and shortwave infrared) from the Landsat Collection 2 Level-2 atmosperically corrected surface reflectance data, collected by the Landsat 8 satellite.

The data was retrieved from the [Microsof Planetary Computer data catalogue](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2) and clipped to an area surrounding the fire perimeters.

The second dataset is of fire perimeters for the Eaton and Palisades fires, and is retrieved from the [County of Los Angeles Open Data](https://data.lacounty.gov/). The data can be accessed from the [link](https://data.lacounty.gov/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about).

## References

### Course Information
**Course Title:** EDS 223 - Geospatial Analysis & Remote Sensing
**Term:** Fall 2025

#### Teaching Team:
**Instructor:** Dr. Carmen Galaz García
**Co-instructor**: Dr. Annie Adams

Complete description for the homework can be found on the [Assignment-4](https://meds-eds-220.github.io/MEDS-eds-220-course/assignments/assignment4-palisades.html).

**Author:** Aakriti Poudel