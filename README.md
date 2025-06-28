# Bayes to the Future: Heart Disease Prediction

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1YEdtaZq-rTHv_wQexMLsXqX8lIvFzLdn?usp=sharing)

Cleans and preprocesses heart disease data (removes duplicates, fills missing, normalizes, bins numerics).
Builds a Bayesian Network: age → fbs → target → chol, thalach.
Trains with Maximum Likelihood Estimation (MLE).
Answers queries like P(target | fbs, age) and most likely thalach given target.
Visualizes the network and probability tables.

## Run
- Install: `pip install pandas scikit-learn pgmpy matplotlib networkx`
- Open and run `heartds.ipynb` step by step.
- Dataset: `heart_disease.csv`.
