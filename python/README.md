# Python

Notebooks for the heat-transfer model. Run them in order. Each one needs the NASA POWER CSV from `data/raw/`.

## Notebooks

- `01_wall_and_roof_model.ipynb`: heat conduction through a 10 m² wall (plain U = 2.0 vs insulated U = 0.5, 75% reduction), then a 100 m² roof with solar heating via the sol-air temperature (dark α = 0.85 vs white coating α = 0.35, 38% reduction).
## How to run

Open a notebook in Google Colab, upload the CSV from `data/raw/`, and run the cells. The `skiprows=10` setting skips the NASA header lines.

## Assumptions

See `research-log.md` for the values I assumed (U-values, absorptance, h_o) and which ones still need to be verified.
