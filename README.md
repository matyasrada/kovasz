# kovász

minimal geospatial data science template

*kovász is hungarian for leaven (sourdough starter)*

## quick start

```bash
uv tool install copier
copier copy --trust gh:matyasrada/kovasz my-project
cd my-project && make run
```

## prompts

- **project_name** — lowercase, hyphens ok
- **description** — one-liner
- **author** — your name

## comes with

**tools** — uv, ruff, pre-commit, nbstripout, jupyterlab, ipykernel

**geospatial stack** — xarray, rioxarray, rasterio, geopandas, pyproj

**storage** — zarr, netcdf4, h5netcdf

**stac/odc** — pystac, pystac-client, odc-stac, odc-geo, odc-loader

**cloud** — boto3, s3fs, obstore

**compute** — dask, distributed

**ml** — scikit-learn, mlflow

**viz** — matplotlib, cartopy, lonboard
