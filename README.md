# Title: Biodiversity Intactness Index change in Phoenix, AZ

### Author: Bailey Jørgensen

**Repository:** https://github.com/jorb1/eds220-BII

![alt text](https://arizona-content.usedirect.com/storage/common/20220301071637.jpg)

## About: 
In 2021, Maricopa County —home to the Phoenix metropolitan area— was identified as the U.S. county with the most significant increase in developed land since 2001. This rapid urban sprawl has profound implications for biodiversity and the health of surrounding natural ecosystems.

Using Python in Jupyter Notebooks,  I will investigate the impacts of urban expansion by analyzing a dataset that captures values for the Biodiversity Intactness Index (BII). Apecifically, I will examine changes in BII in the Phoenix county subdivision area between 2017 and 2020, shedding light on how urban growth affects biodiversity over time.

## Repository Structure   
    
```bash
├── eds220-BII
│   ├── README.md
│   ├── BII_analysis.ipynb
│   └── .gitignore
├── data
│   ├── tl_2022_04_cousub.cpg
│   ├── tl_2022_04_cousub.dbf
│   ├── tl_2022_04_cousub.prj
│   ├── tl_2022_04_cousub.shp
│   ├── tl_2022_04_cousub.shp.ea.iso.xml
│   ├── tl_2022_04_cousub.shp.iso.xml
│   └── tl_2022_04_cousub.shx
```

## Data section. 

The data for this analysis was accessed on 12/2/2024

1. The first data set is is the Biodiversity Intactness Index (BII) Time Series. Access the io-biodiversity collection from the Microsoft Planetary Computer STAC catalog. I will be using the 2017 and 2020 rasters covering the Phoenix subdivision. 

2. The second data set is the Phoenix Subdivision Shapefile Download the Phoenix subdivision polygon from the Census County Subdivision shapefiles for Arizona. All legal boundaries and names are as of January 1, 2024. The 2024 TIGER/Line Shapefiles were released on September 25, 2024. https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2022&layergroup=County+Subdivisions

## Citations:

C. Galaz García, EDS 220 - Working with Environmental Datasets, Course Notes. 2024. [Online]. Available: https://meds-eds-220.github.io/MEDS-eds-220-course/book/preface.html

Microsoft Planetary Computer, STAC Catalog. Biodiversity Intactness ('io-biodiversity'). [Dataset]. https://planetarycomputer.microsoft.com/dataset/io-biodiversity Accessed 2 December 2024.

United States Census Bureau. (2022). Arizona County Subdivision 2022 TIGER/Line Shapefiles. [Data File]. U.S. Census Bureau, Geography Division. https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2022&layergroup=County+Subdivisions Accessed 2 December 2024.
