# BayesOpt-Antarctica

In this repository Bayesian Optimisation over the Antarctica ice sheet.

## Contents

Open the **html** version to avoid having to run code locally to see results and visualisations.

> 2DBayesianOptimisation.ipynb  
> 2DBayesianOptimisation.html

Simple Bayesian Optimisation loop over modelled RACMO2.3p3 ANT27 surface mass balance (smb) data. Input variables are restricted to x1 and x2 coordinates, projected using [EPSG:3031](https://epsg.io/3031) WGS 84 / Antarctic Polar Stereographic projection. Implementation using BoTorch package. 

## Data

### surface mass balance (modelled with regional climate model)

| name       | description|
| :---         |          ---: |
| model version       | RACMO2.3p3   |
| file name       | `smb_monthlyS_ANT27_CONsettings_197901_201812.nc`   |
| file source       | [Zenodo](https://zenodo.org/record/5512077#.Y-BERuxBwvo)   |
| file format    | `.nc` NetCDF (Network Common Data Form)    |
| key model publication        | [van Dalum et al. 2022](10.5194/egusphere-egu22-12543)   |
| spatial resolution    | 27 km gridded    |
| projection    | rotated pole    |
| spatial coverage    | Antarctica    |
| temporal resolution    | aggregated (but monthy available)  |
| temporal coverage    | 1979 - 2019 available     |
| target variable    | SMB (surface mass balance)     |
| uncertainty estimates    | -     |
| unit    | mm w.e. a<sup>-1</sup> (millimeter water equivalent per year)   |
|     | equivalent to kg m<sup>-2</sup>   |

## Contact

Kim Bente
Data Science PhD student, School of Computer Science, University of Sydney  
kim.bente@sydney.edu.au  
www.kimbente.com
