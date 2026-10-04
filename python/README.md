# Python

Notebooks for the heat-transfer model. Run them in order. Each one needs the NASA POWER CSV from `data/raw/`.

## Notebooks

- `01_single_wall_model.ipynb`: heat conduction through a 10 m² wall, Q = U × A × (T_out − 24 °C). Compares a plain wall (U = 2.0) with an insulated wall (U = 0.5). Result: 75% reduction.
- `02_roof_model.ipynb`: adds solar heating with the sol-air temperature. Compares a dark roof (α = 0.85) with a white coating (α = 0.35) on a 100 m² roof. Result: 38% reduction.

## How to run

Open a notebook in Google Colab, upload the CSV from `data/raw/`, and run the cells. The `skiprows=10` setting skips the NASA header lines.

## Assumptions

See `research-log.md` for the values I assumed (U-values, absorptance, h_o) and which ones still need to be verified.
