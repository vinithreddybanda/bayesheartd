# Bayes to the Future: Heart Disease Prediction

- Cleans and preprocesses heart disease data (removes duplicates, fills missing, normalizes, bins numerics).
- Builds a Bayesian Network: age → fbs → target → chol, thalach.
- Trains with Maximum Likelihood Estimation (MLE).
- Answers queries like P(target | fbs, age) and most likely thalach given target.
- Visualizes the network and probability tables.

## Run
1. Install: `pip install pandas scikit-learn pgmpy matplotlib networkx`
2. Open and run `heartds.ipynb` step by step.

Dataset: `heart_disease.csv`.
