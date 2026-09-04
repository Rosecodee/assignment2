# Assignment 2 – Geostrophic Transport and AMOC

This repository contains the analysis and implementation for Assignment 2, including geostrophic transport calculations, AMOC analysis, correlation, seasonal variability, trend analysis, and statistical significance testing.

## Repository Structure

* `notebook.ipynb` – Main analysis notebook containing the calculations, analysis, and figures.
* `Geostrophic_transport_and_AMOC.md` – Assignment report in Markdown format. (Unfortunetly converter did a bad job)
* `Geostrophic_transport_and_AMOC.pdf` – Assignment report in PDF format.
* `correlation_trends/` – Python package containing the analysis functions:

  * `geostrophy.py` – Geostrophic transport calculations
  * `correlation.py` – Correlation analysis
  * `seasonal.py` – Seasonal and climatological analysis
  * `trends.py` – Trend and statistical significance analysis
  * `data_io.py` – Data input/output utilities
* `tests/` – Unit tests for the implemented functions.
* `figs/` – Figures generated during the analysis.
* `requirements.txt` – Python dependencies required to run the analysis and tests.

## Running the Tests

Install the required dependencies with:

```bash
pip install -r requirements.txt
```

Then run the test suite with:

```bash
pytest
```

## Report

The full analysis and discussion can be found in:

**`Geostrophic_transport_and_AMOC.pdf`**
