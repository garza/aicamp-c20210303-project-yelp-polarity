# AICamp - Project - Estimate stars for Yelp reviews

- Download data from https://s3.amazonaws.com/fast-ai-nlp/yelp_review_polarity_csv.tgz
    - The dataset contains 2 columns (# of stars, yelp comment text)
- Develop a model to estimate the number of stars from yelp comment text
- Use the test dataset to calculate test accuracies
- Compare multiple models and recommend the best model

## Table of Contents

- 01-clean-data.ipynb: Notebook covering dataset download and text preprocessing
- 02-prepare-spacy-docs.ipynb: Formatting data into spaCy doc format
- 03-build-model-basic.ipynb: Training vanilla spaCy model with a default text classification config
- 04-build-model-TextCatBOW.ipynb: Training a BOW spaCy model for text classification
- 05-build-model-TextCatCNN.ipynb: Training a CNN spaCy model for text classification
- 06-build-model-TextCatEnsemble.ipynb: Training a stacked ensemble of a linear BOW model and a NN model for text classification
- 07-evalute-review.ipynb: Aggregation and review of model stats, accuracy, f-score and text classfication results on the validation set
