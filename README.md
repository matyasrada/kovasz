# kovász

minimal geospatial data science template

## quick start

```bash
uv tool install copier
mkdir -p my-project && copier copy --trust gh:matyasrada/kovasz my-project
```

or from a local clone:

```bash
mkdir -p my-project && copier copy --trust path/to/kovasz my-project
```

## prompts

- **project_name** — lowercase, hyphens ok
- **description** — one-liner
- **author** — name

## comes with

**tools** — uv, ruff, pre-commit, nbstripout, jupyterlab, ipykernel

**geospatial stack** — xarray, rioxarray, rasterio, geopandas, pyproj

**storage** — zarr, netcdf4, h5netcdf

**stac/odc** — pystac, pystac-client, odc-stac, odc-geo, odc-loader

**cloud** — boto3, s3fs, obstore

**compute** — dask, distributed

**ml** — scikit-learn, mlflow

**viz** — matplotlib, cartopy, lonboard
