# databricks-PySpark

PySpark exercises analyzing the NYC Yellow Taxi trip dataset (2015–2016), built for Databricks.

## Contents

- [`Spark_t4.ipynb`](Spark_t4.ipynb) — Notebook covering:
  1. Loading and exploring the NYC yellow taxi trip data
  2. Visualizing pickup locations on a map (`folium`)
  3. Working with pandas/GeoPandas DataFrames on district boundary data
  4. Spatial join to assign pickup/dropoff districts to each trip
  5. Correlation analysis between tips and trip/district features
  6. Correlation between trip volume and district-level socioeconomic rates

## Requirements

- Databricks (or a local Spark environment with `spark.conf.set("spark.sql.session.timeZone", "UTC")` set)
- Python packages: `pyspark`, `pandas`, `numpy`, `folium==0.20.0`, `fsspec==2024.10.0`, `geopandas==1.1.2`

## Usage

Open `Spark_t4.ipynb` in Databricks (or Jupyter with a configured Spark session) and run the cells in order. Each exercise cell defines variables that must be filled in with the requested computation.
