# Geospatial-Analysis-of-Wildfires
A Spatiotemporal analysis of wildfires in Nevada with environmental factors such as temperature, precipitation and vapour pressure deficit. The project aims to find the pattern of wildfires , their occurrence and behaviour in response to certain environmental factors.

## dependencies
1. Install miniconda/Anaconda  [link to official website] https://www.anaconda.com/docs/getting-started/miniconda/install
### Setting Environment
```
conda create --n wildire_env python=3.9
conda activate wildfire_env
pip install -r requirements.txt
```
**[Links to the dataset]**
1. ***Nevada Wildfire Data***
- https://nvfireintel-nifc.hub.arcgis.com/datasets/eaf3d5985b874ba38ae61a1a1b4093ce_0/explore
2. ***Environmental Factors***
- https://prism.oregonstate.edu/normals/

### Dataset Collection and folder structure
- Download Shapefile for ***Nevada Wildfire Data***
- Download monthly data for environmental factors i.e *Mean Temperature,Precipitation,Max Vapour Pressure Deficit* for 4km resolution from the link given for website.

  **Folder Structure**
  ```
  datasets/
    |--- California/
            |--- VPD-2020/
                    |--- PRISM_vpdmax_stable_4kmM3_202001_bil.bil
                    |--- PRISM_vpdmax_stable_4kmM3_202002_bil.bil
                      ...
            |--- VPD-2021/
                      ...
            |--- VPD-2022/
                      ...
            |--- precipitation-2020/
                      |--- PRISM_ppt_stable_4kmM3_202001_bil.bil
                      |--- PRISM_ppt_stable_4kmM3_202002_bil.bil
                      ...
            |--- precipitation-2021/
                      ...
            |--- precipitation-2022/
                      ...
            |--- temperature-2020/
                    |--- PRISM_tmean_stable_4kmD2_202001_bil.bil
                    |--- PRISM_tmean_stable_4kmD2_202002_bil.bil
                      ...
            |--- temperature-2021/
                      ...
            |--- temperature-2022/
                      ...
