# Sports Analytics Portfolio (Python)

A collection of applied sports data science projects spanning baseball, soccer, hockey, and basketball — built in Python (developed and run in Google Colab). Each notebook tackles a self-contained problem end-to-end: data wrangling, modeling, and a written interpretation of the results. Techniques range from classical ML (logistic regression, clustering) to Bayesian hierarchical modeling and neural networks.

Originally developed as part of a graduate course in AI/analytics applications in sports (Master of Science in Kinesiology), cleaned up here as a standalone project portfolio.

## Projects

| Notebook | Sport | Problem | Techniques |
|---|---|---|---|
| [`pitch_classification_model.ipynb`](pitch_classification_model.ipynb) | Baseball | Predict pitch type from pitch-level characteristics | Multi-class classification, model comparison |
| [`soccer_pass_clustering.ipynb`](soccer_pass_clustering.ipynb) | Soccer | Cluster ~68,500 passes by spatial characteristics; analyze Canada's passing tendencies at the 2022 World Cup | K-means clustering |
| [`hockey_poisson_simulation.ipynb`](hockey_poisson_simulation.ipynb) | Hockey | Resimulate a full NHL season from team xG For/Against | Poisson simulation |
| [`mlb_home_run_rate_bayesian_model.ipynb`](mlb_home_run_rate_bayesian_model.ipynb) | Baseball | Estimate player home run rates with uncertainty | Bayesian hierarchical (beta-binomial) modeling, posterior predictive checks |
| [`soccer_run_clustering.ipynb`](soccer_run_clustering.ipynb) | Soccer | Cluster player off-ball run types from tracking data | Unsupervised clustering on tracking data (`kloppy`) |
| [`mlb_home_run_rate_neural_network.ipynb`](mlb_home_run_rate_neural_network.ipynb) | Baseball | Predict HR/AB rate from player statistics | Neural network vs. logistic regression comparison |
| [`basketball_free_throw_mechanics.ipynb`](basketball_free_throw_mechanics.ipynb) | Basketball | Quantify variability in free-throw shooting mechanics from motion keypoint data | Biomechanical keypoint analysis |
| [`soccer_expected_goals_model.ipynb`](soccer_expected_goals_model.ipynb) | Soccer | Build an Expected Goals (xG) shot difficulty model | Logistic regression, model diagnostics |

## Tools & data sources
Python (Google Colab) · pandas / scikit-learn · Bayesian modeling (PyMC-style hierarchical models) · neural networks · `mplsoccer` · `kloppy` · StatsBomb Open Data · Metrica tracking data · SPL Open Data

## Running the notebooks
Each notebook was built to run in Google Colab. Open a notebook in Colab (or Jupyter) and run cells top to bottom; any dataset needed is either pulled from the open data sources named above or loaded from a CSV described in that notebook's first few cells.
