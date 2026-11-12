# COVID-19 Data Visualisation

A small Python exercise that reads a CSV dataset and plots reported cases over time, with country represented by colour.

## Project structure

- `Data_visulization-master/Data_visulization-master/graphs.py` — creates the Plotly scatter plot.
- `Data_visulization-master/Data_visulization-master/data.csv` — input dataset.

## Requirements

```bash
pip install pandas plotly
```

## Run

Run from the directory containing `data.csv`:

```bash
python graphs.py
```

The chart opens using Plotly's default renderer. The dataset's provenance and date coverage are not documented in the original files, so verify those before using the chart as an analytical source.