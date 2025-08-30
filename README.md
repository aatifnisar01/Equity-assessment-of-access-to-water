# Equity-assessment-of-access-to-water

## Codes to detect Ponds and Wells used in this study can be found here:
    https://github.com/aatifnisar01/Ponds_and_wells_detection.git


This repository contains code and workflows developed to assess the equity of water access and its implications for agroforestry adoption and agricultural income in rural India. The methodology integrates multi-source data to analyze water resource distribution and its impact on cropping patterns, including single, double, and triple-cropped lands.

All analyses are carried out at the micro-watershed (MWS) level (500–1500 ha), delineated using watershed boundaries from India-WRIS and SRTM Digital Elevation Models. The geospatial dataset includes canals, check dams, ponds, wells, surface water bodies, and cropping intensity, mapped through a combination of open datasets (IndiaSAT LULC, WRIS canal networks) and computer vision models trained on high-resolution Google Maps imagery to detect small structures such as farm ponds and wells (Code to detect ponds and wells can be found in the link above). Seasonal surface water bodies (Kharif, Rabi, Zaid) and cropping intensity classes (single, double, triple cropping) are derived from IndiaSAT. Crop health is assessed using NDVI sensitivity, which quantifies vegetation response to drought by comparing NDVI values in drought vs. non-drought years. Groundwater abstraction (ΔG) is estimated using a water balance approach incorporating precipitation, evapotranspiration, soil moisture change, and runoff, where negative values indicate groundwater extraction for irrigation. Check dams are explicitly incorporated with assigned buffer radii to capture their role in local irrigation coverage. Agricultural pixels outside these protective buffers are classified using a dual framework of NDVI sensitivity and ΔG, distinguishing stable from vulnerable irrigated areas. The processed features—21 per MWS across three seasons—are consolidated and clustered to evaluate irrigation equity and its implications for agroforestry adoption.



### To get more information of details about this work, reach out to me - aatif.dar11@gmail.com
