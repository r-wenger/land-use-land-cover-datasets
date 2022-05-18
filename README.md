# Land use land cover (LULC) datasets 

Liste of codes and datasets for remote sensing LULC applications.

## Datasets

### Copernicus program

- 2022.[MultiSenGE](https://zenodo.org/record/6375466) 
MultiSenGE is a new large-scale multimodal and multitemporal benchmark dataset covering one of the biggest administrative region located in the Eastern part of France. It contains 8,157 patches of 256 * 256 pixels for Sentinel-2 L2A, Sentinel-1 GRD and a regional LULC topographic regional database.

<ins>Keywords</ins> :

- 2020.[CaneSat](https://ieee-dataport.org/documents/canesat)
This dataset contains multispectral high resolution 1627 image patches of size 10 x 10 pixels with each pixel size of 10mx10m. These patches are generated from the Sentinel-2 (A/B) satellite images acquired during the period of October 2018 to May 2019. It covered one life cycle (12 months) of the sugarcane crop in the region of the Karnataka, India.
<ins>Keywords</ins> :

- 2019.[BigEarthNet](https://bigearth.net/)
BigEarthNet is a benchmark archive, consisting of 590,326 pairs of Sentinel-1 and Sentinel-2 image patches. The first version (v1.0-beta) of BigEarthNet includes only Sentinel 2 images. Recently, it has been enriched by Sentinel-1 images to create a multi-modal BigEarthNet benchmark archive (called also as BigEarthNet-MM).
<ins>Keywords</ins> :

- 2019.[SEN12MS](https://www.isprs-ann-photogramm-remote-sens-spatial-inf-sci.net/IV-2-W7/153/2019/)
The SEN12MS dataset contains 180,662 patch triplets of corresponding Sentinel-1 dual-pol SAR data, Sentinel-2 multi-spectral images, and MODIS-derived land cover maps. The patches are distributed across the land masses of the Earth and spread over all four meteorological seasons. This is reflected by the dataset structure.
<ins>Keywords</ins> :

- 2020.[Breizhcrops](https://breizhcrops.org/)
We present Breizhcrops, a novel benchmark dataset for the supervised classification of field crops from satellite time series. We aggregated label data and Sentinel-2 top-of-atmosphere as well as bottom-of-atmosphere time series in the region of Brittany (Breizh in local language), north-east France.
<ins>Keywords</ins> :

### Landsat program

- 

### MODIS program

- 2022.[TimeSpec4LULC](https://essd.copernicus.org/articles/14/1377/2022/essd-14-1377-2022-discussion.html)
This dataset with millions of 22-year time series for seven spectral bands was built by merging Terra and Aqua satellite data and annotated for 29 LULC classes by spatial–temporal agreement across 15 global LULC products. The mean F1 score was 96 % at the coarsest classification level and 87 % at the finest one. The dataset is born to develop and evaluate machine learning models to perform global LULC mapping given the disagreement between current global LULC products.
<ins>Keywords</ins> :

## Codes

- 2022.[MultiSenGE](https://github.com/r-wenger/MultiSenGE-Tools)
This repository contains few tools to sort and extract stats on MultiSenGE dataset

## Challenge

- 2018.[TiSeLaC](https://sites.google.com/site/dinoienco/tiselac-time-series-land-cover-classification-challenge?authuser=0)
The dataset has been generated from an annual time series of 23 Landsat 8 images acquired in 2014 above the Reunion Island (2866 X 2633 pixels at 30~m spatial resolution), provided at level 2A. Source data have been further processed to fill cloudy observations via pixel-wise multi-temporal linear interpolation on each multi-spectral band (OLI) independently, and compute complementary radiometric indices (NDVI, NDWI and brightness index - BI). A total of 10 features (7 surface reflectances plus 3 indices) are considered for each pixel at each timestamp. 
<ins>Keywords</ins> :

## Contact

If we forgot some datasets, do not hesitate to contact us : romain.wenger[at]live-cnrs.unistra.fr

[Mail me](mailto:romain.wenger@live-cnrs.unistra.fr?subject=[GitHub]%20LULC%20datasets)
