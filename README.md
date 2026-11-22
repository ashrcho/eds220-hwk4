# Fire Scars Through False Color: Eaton and Palisades Fires

## About
This repository houses a Jupyter notebook whose aim is to visualize the burn scars of the January 2025 Eaton and Palisades fires in Los Angeles County. Landsat 8 imagery from February 23, 2025 is displayed in true color and in false color (shortwave infrared, near infrared, red), then mapped with the fire perimeters to show how false color imagery highlights burned land.

## Repository Structure
eds220-hwk4/
├── .gitignore
├── hwk4-task2-false-color-CHOCKKALINGAM.ipynb
└── README.md
Data files live in a local `data/` folder that is excluded by `.gitignore` and not pushed to this GitHub Repository.

## Data
To run the notebook, create a `data/` folder in the repository root and add:
- **Fire perimeters:** download the Eaton and Palisades layers as GeoJSON from the [LA County eGIS hub](https://egis-lacounty.hub.arcgis.com/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about).
- **Landsat 8 imagery:** `landsat8-2025-02-23-palisades-eaton.nc`, available in the EDS 220 course shared Google Drive. 

## References
- Galaz García, C. (2026). *EDS 220: Working with Environmental Datasets* [Course]. Master of Environmental Data Science, Bren School, UC Santa Barbara. https://meds-eds-220.github.io/MEDS-eds-220-course/
- Los Angeles County Enterprise GIS. (2026). *Palisades and Eaton dissolved fire perimeters (2025)* [Data set]. Source data from CAL FIRE and NIFC FIRIS. https://egis-lacounty.hub.arcgis.com/maps/ad51845ea5fb4eb483bc2a7c38b2370c/about. Accessed November 19, 2026.
- Earth Resources Observation and Science (EROS) Center. (2020). *Landsat 8-9 Operational Land Imager / Thermal Infrared Sensor Level-2, Collection 2* [Data set]. U.S. Geological Survey. https://doi.org/10.5066/P9OGBGM6
- Microsoft Open Source, McFarland, M., Emanuele, R., Morris, D., & Augspurger, T. (2022). *microsoft/PlanetaryComputer: October 2022* (Version 2022.10.28) [Computer software]. Zenodo. https://doi.org/10.5281/zenodo.7261897