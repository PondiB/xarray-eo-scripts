# NDVI Calculation on EO data cubes with Xarray, Dask, and Stackstac

This project demonstrates how to compute and visualize a time series of NDVI (Normalized Difference Vegetation Index) data cubes using satellite imagery from STAC and processing it with Xarray and Dask for scalable and parallel computation.

## Project Overview

The main steps covered in this project include:
1. Fetching satellite imagery using the STAC and Stackstac library.
2. Using Xarray and Dask to handle and process multi-dimensional geospatial data.
3. Aggregating data to monthly intervals and computing NDVI.
4. Parallelizing computations with Dask for efficient processing.
5. Visualizing the NDVI time series using Matplotlib and Xarray's built-in plotting functionalities.

## Installation

To run the code, you'll need to have the following dependencies installed:

### Python Libraries
- `xarray`
- `dask`
- `stackstac`
- `matplotlib`
- `numpy`
- `rioxarray`
- `planetary_computer` (for accessing mmicrosoft hosted satellite imagery)
- `pytorch`

Install the required packages using `pip`:

```bash
pip install xarray dask[complete] stackstac matplotlib numpy rioxarray planetary_computer pytorch
```
