# airbnb-dataset

This project is an analysis of an Airbnb open dataset from the Seattle area found on Kaggle <a href="https://www.kaggle.com/airbnb/seattle"> here.</a>

The dataset has been provided under a <a href="https://creativecommons.org/publicdomain/zero/1.0/">Creative Commons CCO</a> Public Domain license

In this analysis we answer the following questions:

### <u>Question 1</u>: What is the distribution of property types in the Seattle Airbnb dataset?
### <u>Question 2</u>: What is the set of possible amenities and what does the distribution look like?
### <u>Question 3</u>: How do amenities correlate with the average guest feedback score for a listing?
### <u>Question 4</u>: Can we build a predictive model for review scores?

<b>results-summary</b> contains a summary of results of the analysis.

Further discussion can be found in blog post <a href="https://medium.com/@bwblock/how-data-science-can-make-you-a-better-airbnb-host-242b57227283">here:</a>

#### Requirements:

- <a href="https://jupyter.org/"> Jupyter notebooks </a>
- <a href="https://www.anaconda.com/"> Anaconda package</a>
- listings.csv

#### Notes:

<b>review-score-model.ipynb</b> contains a linear model of feedback scores based on available quantitative and categorical features.

Jupyter notebook .ipynb files should render directly from github.

#### Results:

Current results of the review score model are as follows:

- Mean Absolute Error: 2.53
- Rsquared score-training data:  0.6924
- Rsquared score-test data:  0.6564

<b>In other words, 63.8 percent of the variance in the review scores are explained by the model.</b>


