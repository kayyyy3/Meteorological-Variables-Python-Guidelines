# Meteorological-Variables-Python-Guidelines

The main purpose of this guideline is to provide the updated statistical application in climate variability studies. This tutorials will show you how to work on basic time series, the seasonal variabilities and basic plotting of different kinds of climate variables, e.g. sea surface temperature (SST), rainfall, wind vectors, vertically intergrated mositure flux, Walker circulation cross section etc.

## Basic introduction to Meteorological Data

Meteorological data is mainly spatio-temporal data that holds observations and analog quantities for individual physical quantities within a time or space range. Data formats commonly encountered in climate research fall into 3 generic categories: netCDF (network common data form), HDF (hierarchical data format) and GRIB (gridded binary). All of these formats are portable (machine independent) and self-describing. Self-describing files can be examined and read by the appropriate software without the user knowing the file's structural details.

### The netCDF

NetCDF is a data abstraction for array-oriented (fixed dimension and regular) data access (direct), which it is designed and maintained by University Corporation for Atmospheric Research (UCAR) under the Unidata Program. NetCDF is widely support by many 3rd party software (e.g Python, GrADS, NCL, MATLAB, ArcGIS etc).
