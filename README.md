# Occident-Paper

Code for creating figures from [Occident paper "Dynamic phenotyping of CAR T-cell-cancer cell interactions with live-cell imaging and cellular behavior analysis"](https://doi.org/10.1101/2024.11.19.624390). In particular, this repo contains notebook to generate graphs in Figures 3, 4, and 5. This repository uses many functions from the occident library https://github.com/bee-hive/occident to perform the underlying analysis. For Figure 2 code, see [here](https://github.com/vanvalenlab/Caliban-2024_Schwartz_et_al). 

## Data

Live cell images with segmentation and tracking will be made available on bioimage aarchive shortly.

## Environment

Code is written in Python 3.11.9.
The following packages are required:
1. numpy 1.26.4
2. matplotlib 3.8.2
3. statsmodel 0.14.2
4. pandas 2.1.4
5. scipy 1.11.4
6. skimage 0.23.2
7. tifffile 2024.5.10

## Organization

Each folder contains notebooks to produce the associated figure.

