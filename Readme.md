# Overview

This repository contains three notebooks that can be used to recreate the scientific figures of the PNAS paper describing mrCOSTS. The data used are included. These data were altered slightly from their original versions for ease of use (i.e., subsets, converting to xarray friendly formats).

## Requirements

numpy
scipy
matplotlib
seaborn
xarray
pydmd
cartopy
netcdf4
h5netcdf

You might have to do some trouble shooting. This repository is provided as a demonstration, not a tutorial.

## Set up

You will need to create a directory called "data" by expanding `data.zip`.

For storing the model results you will need to set up a directory called `results` with a subdirectory for each data type. See the `Directories` heading in the notebooks for an example of the expected structure.
