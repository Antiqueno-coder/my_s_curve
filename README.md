# my_s_curve
s-curves of select companies
# Growth Curve Intelligence Platform

An interactive, serverless corporate lifecycle analytics dashboard. This platform fits historical corporate annual revenues to non-linear S-Curves (Symmetric 3-Parameter Logistic Models) and evaluates efficiency margin profiles entirely inside the client browser.

## Features
* **Serverless Architecture:** The front-end operates entirely client-side. S-Curve non-linear regressions, Euclidean distance peer comparisons, and KPI calculations are processed dynamically in JavaScript.
* **Dual Data Pipeline:** Backed by an automated extraction script (`sec_growth_extractor.py`) that normalizes GAAP and IFRS datasets from SEC EDGAR and Yahoo Finance.
* **Dynamic Visualization:** Interactive charting using Chart.js, rendering historical S-curve trajectories and structural margins over long-term horizons.
