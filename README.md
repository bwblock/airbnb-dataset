# airbnb-dataset

This project is an analysis of an Airbnb open dataset from the Seattle area found on Kaggle <a href="https://www.kaggle.com/airbnb/seattle"> here.</a>

The dataset has been provided under a <a href="https://creativecommons.org/publicdomain/zero/1.0/">Creative Commons CCO</a> Public Domain license

#### Requirements:

- <a href="https://jupyter.org/"> Jupyter notebooks </a>
- <a href="https://www.anaconda.com/"> Anaconda package</a>
- listings.csv

#### Notes:

<b>review-score-model.ipynb</b> contains a linear model of feedback scores based on available quantitative and categorical features.

Jupyter notebook .ipynb files should render directly from github.

#### Results:

Current results of the review score model are as follows:

- Mean Absolute Error: 2.44
- Rsquared score-training data:  0.6722
- Rsquared score-test data:  0.6564

In other words, 65.6 percent of the variance in the review scores are explained by the model.


