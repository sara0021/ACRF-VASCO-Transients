# ACRF: VASCO Transients Model

**2-3x Spikes on Nuclear/UAP Days | 95% Causal**

By @sara0021 | Oct 29, 2025

## Results
| Predictor | Coeff | p-val | Spike |
|-----------|-------|-------|-------|
| Nuclear   | +1.009| <0.001| 2.7x |
| UAP       | +1.386| <0.001| 4.0x |

## Run
pip install -r requirements.txt
jupyter notebook notebooks/01_acrf_glm_analysis.ipynb

## Files
- data/ → VASCO CSV
- notebooks/ → GLM + plots
- docs/manuscripts/ → Upload PDFs
- results/ → spikes.png (auto)

License: MIT
