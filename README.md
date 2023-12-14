# Observing, Measuring, and Assessing the Consequences of Snow Drought

This directory contains all of the data and code to produce the numerical values and figures reported in [Gottlieb & Mankin (2021)](https://journals.ametsoc.org/view/journals/bams/aop/BAMS-D-20-0243.1/BAMS-D-20-0243.1.xml?tab_body=fulltext-display). Users can create a virtual environment with the `python` packages necessary to perform all analysis using the included `environment.yml` file:
`conda create -f environment.yml`


| Dataset | Data Type | Spatial Resolution | Spatial Coverage | Temporal Resolution | Temporal Coverage | Where to Download | Download Method |
| ------- | --------- | ------------------ | ---------------- | ------------------- | ----------------- | ----------------- | --------------- |
| ESA Globsnow | Satellite passive microwave + in situ | 25km | NH | Daily | 1979-2018 | https://www.globsnow.info/swe/ | wget |
| NSIDC AMSR-E/AMSR2 Unified | Satellite passive microwave | 25km | Global | Daily | 2002-present | https://nsidc.org/data/ae\_dysno | wget (NASA Earthdata account required) | 
| Canadian Meteorological Centre | Interpolated in situ | 35km | NH | Daily | 1998-2019 | https://nsidc.org/data/NSIDC-0447/versions/1 | wget (NASA Earthdata account required) |
| ECMWF ERA5-Land | Reanalysis | 0.1° x 0.1° | Global | Hourly | 1979-present | https://cds.climate.copernicus.eu/cdsapp\#!/dataset/reanalysis-era5-land?tab=form | python script (Copernicus CDS account required) |
| NASA GLDAS-2 | Reanalysis | 0.25° x 0.25° | Global | 3-hourly | 2000-present | https://disc.gsfc.nasa.gov/datasets?keywords=GLDAS | wget (NASA Earthdata account required) |
| NASA NLDAS | Reanalysis | 0.125° x 0.125° | CONUS | Hourly | 1979-present  | https://disc.gsfc.nasa.gov/datasets?keywords=NLDAS | wget (NASA Earthdata account required) |
| NASA MERRA-2 | Reanalysis | 0.5° x 0.625° | Global | Daily | 1980-present | https://disc.gsfc.nasa.gov/datasets?project=MERRA-2 | wget (NASA Earthdata account required) |
| JRA-55 | Reanalysis | 55km | Global | 3-hourly | 1958-present | https://rda.ucar.edu/datasets/ds628.0/index.html\#!access | wget (UCAR RDA account required) |
| NOHRSC SNODAS | Reanalysis | 1km | CONUS | Daily | 2003-present | https://nsidc.org/data/g02158 | wget |
| University of Arizona | Interpolated in situ | 4km | CONUS | Daily | 1981-2017 | https://nsidc.org/data/nsidc-0719 | wget (NASA Earthdata account required) |
| DayMet | Reanalysis | 1km | North America | Daily | 1980-present | https://daymet.ornl.gov/getdata | wget |
