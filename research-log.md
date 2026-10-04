# Research log

## Oct 2026
- Project started. Set up repository and research question.

 ## Oct 4, 2026
- Downloaded NASA POWER hourly data for Doha (2023).
- Built a single-wall heat-conduction model in Python: Q = U x A x (T_out - 24 C).
- Plain wall (U=2.0): 1057 kWh/yr. Insulated (U=0.5): 264 kWh/yr. Reduction: 75%.
- Limitation: model uses air temperature only, ignores sun on the wall, windows, and the AC's efficiency.
- Next: add solar heating of the roof and walls (sol-air temperature).
