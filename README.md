# Review of Model Calibration and Validation

Systematic review code and extracted data for reporting of calibration and validation in cardiometabolic microsimulation models.

## Contents

| File | Description |
|------|-------------|
| `data.xlsx` | Extracted review data (study characteristics and calibration/validation reporting). |
| `analysis.ipynb` | Jupyter notebook: tests association between model characteristics and calibration/validation reporting (Chi-square / Fisher's exact). |

## How to run

1. Clone the repository and open the folder.
2. Install dependencies: `pandas`, `numpy`, `scipy`, `openpyxl` (for Excel).
   ```bash
   pip install pandas numpy scipy openpyxl
   ```
3. Open and run `analysis.ipynb` (e.g. in Jupyter or VS Code).
4. The notebook writes results to `chi_square_vs_fisher_results.xlsx` in the same folder (this file is not tracked in the repo).

## License

MIT — see [LICENSE](LICENSE).
