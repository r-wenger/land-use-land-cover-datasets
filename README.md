# Land use land cover (LULC) datasets

List of datasets and codes for remote sensing LULC applications.

## Datasets

### Copernicus program

- 2022-[SEASONET](https://zenodo.org/record/5850307)

SeasoNet, a new large-scale multilabel land cover and land use scene understanding dataset. It includes 1 759 830 images from Sentinel-2 tiles, with 12 spectral bands and patch sizes of up to 120 px×120 px. Each image is annotated with large scale pixel level labels from the German land cover model LBM-DE2018 with land cover classes based on the CORINE Land Cover database (CLC) 2018 and a five times smaller minimum mapping unit (MMU) than the original CLC maps.

<ins>Keywords</ins> : Sentinel-2; Multitemporal; Germany; CLC


- 2022-[MultiSenGE](https://zenodo.org/record/6375466)

MultiSenGE is a new large-scale multimodal and multitemporal benchmark dataset covering one of the biggest administrative region located in the Eastern part of France. It contains 8,157 patches of 256 * 256 pixels for Sentinel-2 L2A, Sentinel-1 GRD and a regional LULC topographic regional database.

<ins>Keywords</ins> : Sentinel-1; Sentinel-2; Multitemporal; Multimodal; France

- 2022-[Sen4AgriNet](https://www.sen4agrinet.space.noa.gr/)

Sen4AgriNet, a Sentinel-2 based time series multi country benchmark dataset, tailored for agricultural monitoring applications with Machine and Deep Learning. Sen4AgriNet dataset is annotated from farmer declarations collected via the Land Parcel Identification System (LPIS) for harmonizing country wide labels. These declarations have only recently been made available as open data, allowing for the first time the labeling of satellite imagery from ground truth data. We proceed to propose and standardise a new crop type taxonomy across Europe that address Common Agriculture Policy (CAP) needs, based on the Food and Agriculture Organization (FAO) Indicative Crop Classification scheme. Sen4AgriNet is the only multi-country, multi-year dataset that includes all spectral information.

<ins>Keywords</ins> :

- 2020-[Breizhcrops](https://breizhcrops.org/)

We present Breizhcrops, a novel benchmark dataset for the supervised classification of field crops from satellite time series. We aggregated label data and Sentinel-2 top-of-atmosphere as well as bottom-of-atmosphere time series in the region of Brittany (Breizh in local language), north-east France.

<ins>Keywords</ins> :

- 2020-[CaneSat](https://ieee-dataport.org/documents/canesat)

This dataset contains multispectral high resolution 1627 image patches of size 10 x 10 pixels with each pixel size of 10mx10m. These patches are generated from the Sentinel-2 (A/B) satellite images acquired during the period of October 2018 to May 2019. It covered one life cycle (12 months) of the sugarcane crop in the region of the Karnataka, India.

<ins>Keywords</ins> :

- 2020-[LandCoverNet](https://mlhub.earth/data/landcovernet_af_v1)

LandCoverNet is a global annual land cover classification training dataset with labels for the multi-spectral satellite imagery from Sentinel-1, Sentinel-2 and Landsat-8 missions in 2018. LandCoverNet Africa contains data across Africa, which accounts for ~1/5 of the global dataset. Each pixel is identified as one of the seven land cover classes based on its annual time series. These classes are water, natural bare ground, artificial bare ground, woody vegetation, cultivated vegetation, (semi) natural vegetation, and permanent snow/ice.

<ins>Keywords</ins> :


- 2019-[BigEarthNet](https://bigearth.net/)

BigEarthNet is a benchmark archive, consisting of 590,326 pairs of Sentinel-1 and Sentinel-2 image patches. The first version (v1.0-beta) of BigEarthNet includes only Sentinel 2 images. Recently, it has been enriched by Sentinel-1 images to create a multi-modal BigEarthNet benchmark archive (called also as BigEarthNet-MM).

<ins>Keywords</ins> :

- 2019-[SEN12MS](https://www.isprs-ann-photogramm-remote-sens-spatial-inf-sci.net/IV-2-W7/153/2019/)

The SEN12MS dataset contains 180,662 patch triplets of corresponding Sentinel-1 dual-pol SAR data, Sentinel-2 multi-spectral images, and MODIS-derived land cover maps. The patches are distributed across the land masses of the Earth and spread over all four meteorological seasons. This is reflected by the dataset structure.

<ins>Keywords</ins> :

- 2018-[EuroSAT](https://github.com/phelber/EuroSAT)

Dataset based on Sentinel-2 satellite images covering 13 spectral bands and consisting out of 10 classes with in total 27,000 labeled and geo-referenced images.

<ins>Keywords</ins> :

### Landsat program

- 2020-[LandCoverNet](https://mlhub.earth/data/landcovernet_af_v1)

LandCoverNet is a global annual land cover classification training dataset with labels for the multi-spectral satellite imagery from Sentinel-1, Sentinel-2 and Landsat-8 missions in 2018. LandCoverNet Africa contains data across Africa, which accounts for ~1/5 of the global dataset. Each pixel is identified as one of the seven land cover classes based on its annual time series. These classes are water, natural bare ground, artificial bare ground, woody vegetation, cultivated vegetation, (semi) natural vegetation, and permanent snow/ice.

<ins>Keywords</ins> :

### MODIS program

- 2022-[TimeSpec4LULC](https://essd.copernicus.org/articles/14/1377/2022/essd-14-1377-2022-discussion.html)

This dataset with millions of 22-year time series for seven spectral bands was built by merging Terra and Aqua satellite data and annotated for 29 LULC classes by spatial–temporal agreement across 15 global LULC products. The mean F1 score was 96 % at the coarsest classification level and 87 % at the finest one. The dataset is born to develop and evaluate machine learning models to perform global LULC mapping given the disagreement between current global LULC products.

<ins>Keywords</ins> :

## Codes

- 2022-[MultiSenGE](https://github.com/r-wenger/MultiSenGE-Tools)

This repository contains few tools to sort and extract stats on MultiSenGE dataset

## Challenge

- 2021-[IEEE GRSS Data Fusion Contest: Track DSE](https://www.grss-ieee.org/community/technical-committees/2021-ieee-grss-data-fusion-contest-track-dse/)

The detection of settlements without electricity challenge track (Track DSE) of the 2021 IEEE GRSS Data Fusion Contest, organized by the Image Analysis and Data Fusion Technical Committee (IADF TC) of the IEEE Geoscience and Remote Sensing Society (GRSS), Hewlett Packard Enterprise, SolarAid, and Data Science Experts, aims to promote research in automatic detection of human settlements deprived of access to electricity using multimodal and multitemporal remote sensing data.

<ins>Keywords</ins> :

- 2018-[TiSeLaC](https://sites.google.com/site/dinoienco/tiselac-time-series-land-cover-classification-challenge?authuser=0)

The dataset has been generated from an annual time series of 23 Landsat 8 images acquired in 2014 above the Reunion Island (2866 X 2633 pixels at 30~m spatial resolution), provided at level 2A. Source data have been further processed to fill cloudy observations via pixel-wise multi-temporal linear interpolation on each multi-spectral band (OLI) independently, and compute complementary radiometric indices (NDVI, NDWI and brightness index - BI). A total of 10 features (7 surface reflectances plus 3 indices) are considered for each pixel at each timestamp.

<ins>Keywords</ins> :

## Contact

If we forgot some datasets, do not hesitate to contact us : romain.wenger[at]live-cnrs.unistra.fr

[Mail me](mailto:romain.wenger@live-cnrs.unistra.fr?subject=[GitHub]%20LULC%20datasets)
