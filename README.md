# Kaggle-Instacart-Purchase-Prediction
Predict customer's future purchases ([past Kaggle competition](https://www.kaggle.com/c/instacart-market-basket-analysis/overview))

Last updated on: 11/13/2020


## Data

Please visit the notebook `data_exploration.ipynb` for more exploratory analysis on the data




## Evaluation

This Kaggle competition evaluated the performance of a model by the **mean F1 score**, which is given by the following formula:

F1 = TP / (TP + (FP + FN)/2)

## Benchmark Models

Details of the benchmark model can been viewed in the notebook `benchmark_models.ipynb`.

**Benchmark model #1**

This model predicts the products by simply returning all products that an user had ever purchased before, yielding the mean F1 score of **0.21648**.
