# Preprocessing KNMI radar data for hydrology
This repository contains scripts, files and info to download and preprocess radar data from the Royal Netherlands Meteorological Institute (KNMI) for use in (catchment) hydrological studies.

The repository inlcudes:
- A readme (pdf) with instructions on how to download several KNMI datasets, extract a certain area and save them as time series.
- An overview (xls) of the (radar) precipitation datasets available from the KNMI data portal.
- Zip files (for each product) with the scripts (python for downloading, R for preprocessing), coordinates and some examples.
- A separate zip file with the coordinates for the EURADCLIM dataset.

Specific examples are made for the following commonly used products:
-	IRC RTCOR: for real-time applications.
-	RAC: for offline studies (starting) before 2018.
-	IRC RFCOR: for offline studies after February 2023. IRC RFCOR is available for the period 2018 to Feb 2023, but the RAC product is probably better.
-	EURADCLIM: for studies (partly) outside the Netherlands.
-	KNMI’23: climate scenarios (not radar but model output).

_Note: Always check your data carefully with other datasets and let me know if you find an error._

![WUR logo](https://github.com/ClaudiaBrauer/WALRUS/blob/master/documentation/figures/wu.png).

[Hydrology and Environmental Hydraulics Group](https://www.hwm.wur.nl), Wageningen University, The Netherlands
