# GPU-data-learning

## Idea
Wanted to learn and predict different manufacturers based on GPU information. Used a dataset of 100 GPUs and added benchmarks to each card.
As this was presented as final course work for data science and data mining, the text is in Estonian.


## Results
From using scikit-learn prediction algorithms, I was able to achieve a prediction certanity of about 85% with roughly 20 cards.
Increase in dataset causes the prediction accuracy to rise even further.

In addition, tried to predict benchmark results in discrete amounts of 1000 points.
Results were mixed, accuracy was about 80% with small datasets. More discrete values held less accurate results. (100 points was ~15%, 500 points ~50%)
