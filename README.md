![swan on a lake](./images/header.png)

## TODO

- [ ] Add flood predictor dataset
- [ ] R markdown zettel notes + `image` + `subtitle` + `description` + `categories`
- [ ] tidymodels zettel notes
- [ ] what is janitor package + `clean_names()`
- [ ] R2 score
  - https://scikit-learn.org/stable/modules/generated/sklearn.metrics.r2_score.html
  - https://scikit-learn.org/stable/modules/model_evaluation.html#r2-score
  - https://en.wikipedia.org/wiki/Coefficient_of_determination
- [ ] since train * test dataset = on apas besoin de faire split sur le train ?
- [ ] split CV pour éviter le sur apprentissage
- [ ] remove `id` : 0 intérêt pour l'apprentissage
- [ ]


**Welcome to the 2024 [Kaggle Playground Series - Season 4, Episode 5](https://www.kaggle.com/competitions/playground-series-s4e5)!**

Each month, Kaggle provides interesting and approachable datasets to practice
machine learning skills. The goal of this competition is to predict the
probability of a region flooding based on various factors.

## Evaluation

Submissions are evaluated using the R2 score.

## Timeline

- **Start Date**: May 1, 2024 at 11:59 PM UTC
- **Entry Deadline**: Same as the Final Submission Deadline
- **Team Merger Deadline**: Same as the Final Submission Deadline
- **Final Submission Deadline**: May 31, 2024 at 11:59 PM UTC

## Tabular Playground Series

The goal of the [Tabular Playground Series](Tabular Playground Series) is to
provide the Kaggle community with a variety of fairly light-weight challenges
that can be used to learn and sharpen skills in different aspects of machine
learning and data science. The challenges will generally use fairly light-weight
datasets that are synthetically generated from real-world data, and will provide
an opportunity to quickly iterate through various model and feature engineering
ideas, create visualizations, etc.

## Synthetically-Generated Datasets

Using synthetic data for Playground competitions allows Kaggle to strike a
balance between having real-world data (with named features) and ensuring test
labels are not publicly available. This allows Kaggle to host competitions with
more interesting datasets than in the past. While there are still challenges
with synthetic data generation, the state-of-the-art is much better now than
when Kaggle started the Tabular Playground Series in 2021, and that goal is to
produce datasets that have far fewer artifacts.

## How to participate

Kaggle provides AP and CLI tools

```bash
kaggle competitions download -c playground-series-s4e5
```