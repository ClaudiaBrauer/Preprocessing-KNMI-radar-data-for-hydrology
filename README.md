# Preprocessing KNMI radar data for hydrology
This repository contains scripts, files and info to download and preprocess radar data from the Royal Netherlands Meteorological Institute (KNMI) for use in (catchment) hydrological studies.

The repository inlcudes:
- A readme (pdf) with instructions on how to download several KNMI datasets, extract a certain area and save them as time series.
- An overview (xls) of the (radar) precipitation datasets available from the KNMI data portal.
- A zip file with the scripts (python for downloading, R for preprocessing), coordinates and some examples.
- A separate zip file with the coordinates for the EURADCLIM dataset.

Specific examples are made for the following commonly used products:
-	IRC RTCOR: for real-time applications.
-	IRC RFCOR: for offline studies after 2023. (For 2018-2022 it's not known whether RAC or IRC RFCOR is better.)
-	RAC: for offline studies (starting) before 2018.
-	EURADCLIM: for studies (partly) outside the Netherlands.
-	KNMI’23: climate scenarios (not radar but model output).

_Please note that these scripts are new and may contain errors. Please check your data carefully with other datasets and let me know if you find an error._
