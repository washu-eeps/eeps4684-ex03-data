# EEPS 4684/5684 Exercise 03 data

Data bundle and Colab notebook for Exercise 03, Foundations of Geospatial Data.

Open the notebook in Colab:
https://colab.research.google.com/github/washu-eeps/eeps4684-ex03-data/blob/main/ex03_data_diagnosis.ipynb

## What is in `data/`

| File | What it is |
|---|---|
| `tisch_control.csv` | 31 control points on the Danforth campus |
| `benchmark_coordinates.csv` | Four monumented benchmarks, in several frames at once |
| `tisch_control_4326.gpkg` | The control points again, with the reference frame declared |
| `benchmarks.gpkg`, `benchmarks.shp` (+ siblings) | The same table written to two containers |
| `tisch_2024_band5_30cm.tif` | One band of a drone orthophoto of campus, October 2024 |
| `tisch_2024_rgb_30cm.tif` | Natural-color orthophoto, the georeferencing reference |
| `tisch_2024_unreferenced.png` | The same pixels with the georeferencing removed |

Every file here is real course data, and each is missing something or states
something false. Working out what, and what it costs, is the exercise. Do not
treat any of it as a reference dataset.

Derived from surveys held in the course archive. Regenerate with
`build_data.py` in the course folder.
