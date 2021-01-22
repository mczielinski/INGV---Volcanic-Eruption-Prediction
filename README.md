# INGV---Volcanic-Eruption-Prediction
Kaggle INGV - Volcanic Eruption Prediction Notebooks

Kaggle INGV notebooks and submission attempts. 
Best score 5596211 private / 5956165 public (#231, Top 38%)
zscored data pctiles_per_channel:0.001,0.01,0.1:0.9,0.99,0.999 pctnans_per_channel,kurt,skew,hyperskew,hurst,pfd,hj23,fft,coherence,cohermin, cohermax,per channel:5.97:0.995:99.5, fillnan:mean of all non-missing signals, standardscaler:kurt,skew,hyperskew,hj3, done properly UMAP:500dim, HGBR CV10x100 

Idea: Use Coherence between sensors as a prediction metric, combined with standard predictors, non-linear predictors such as Lyapunov exponents and etc, along with standard spectral data. Dimensionality reduction with UMAP, and then CV/prediction with sklearn's new HistGradientBoostingRegressor.

To do: Compare/implement/integrate leaderboard techniques and see where this could be improved!
