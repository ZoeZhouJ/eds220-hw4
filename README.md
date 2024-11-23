# Mapping the Thomas Fire Scars with Landsat 
![thomas fire in 2017](https://github.com/user-attachments/assets/9c483e70-1959-4474-9895-abee444d84be)
Image credits: Ray Ford / Noozhawk

## About
This project uses false color imagery to visualize the Thomas Fire's impact and burn scars in Ventura and Santa Barbara counties (2017), demonstrating how remote sensing aids environmental monitoring.

## Repository Structure
```
.
├── data/                             
├── .gitignore                       boundary config
├── README.md                         # Project documentation
├── hwk4-task2-fire-perimeter-Zhou.ipynb    
└── hwk4-task3-false-color-Zhou.ipynb       
```

## Data Access

The fire perimeter data was obtained from https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436.
The landsat data is from https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2 and was accessed through the server at `/courses/EDS220/data/hwk4_landsat_data landsat8-2018-01-26-sb-simplified.nc`. This data was pre-processed to remove data outside land and coarsen the spatial resolution.

## Acknowledgments
This repository contains materials created by Carmen Galaz-Garcia for the course [EDS 220 - Working with Environmental Datasets](https://meds-eds-220.github.io/MEDS-eds-220-course/). This course is part of the [UCSB Masters in Environmental Data Science](https://bren.ucsb.edu/masters-programs/master-environmental-data-science).
