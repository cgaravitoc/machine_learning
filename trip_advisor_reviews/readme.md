# Trip advisor hotel reviews
The purpose of this project is to analyse data from hotel reviews, in such a way that will be possible to implement a model that predicts the score for a given review.

## Project folder structure
The folder structure for this project is the following:

    ├── data
    │   ├── raw
    │   └── proccessed
    ├── notebooks
    ├── images
    ├── reports
    ├── python
    └── readme.md

Each folder contains:

**`data`** Contains two folders, one for raw data and other one for proccessed data.

**`notebooks`** Notebooks are divided to avoid a unique long and confusing notebook. Are organized as follows:

- 1.0_tripadvisor_reviews_EDA: Exploratory data analysis
- 2.0_tripadvisor_reviews_data_prep: Data preparation, this is, imputation of null and duplicated values, and, one hot encoding for categorical variables.
- 3.0_tripadvisor_reviews_models: Model implementation.

**`images`** Contains charts images for reporting.

**`reports`** Contains a pdf presentation to share results and insights.

**`python`** Contains python scripts.
