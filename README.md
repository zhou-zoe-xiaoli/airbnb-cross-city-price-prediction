# Cross-City Airbnb Price Prediction

This project studies whether Airbnb price prediction models can generalize across major U.S. tourism cities. Using listing data from Boston, Los Angeles, New York City, San Francisco, and Seattle, we compare within-city prediction, single-city transfer, calibrated transfer, grouped-city training, and leave-one-city-out evaluation.

The project shows that tree-based models perform well within cities, but cross-city transfer is uneven because local market conditions create geographic domain shift. Grouped-city training and calibration improve stability in some cases, while feature importance analysis shows that basic listing features such as room type and accommodates are more transferable across cities.

## Project Highlights

- Built an Airbnb price prediction project across five major U.S. tourism cities: Boston, Los Angeles, New York City, San Francisco, and Seattle.
- Conducted exploratory data analysis to understand price distributions, room type patterns, city-level differences, and feature relationships.
- Started with a simple baseline model to test whether listing-level features can predict Airbnb prices.
- Developed a final modeling notebook with more complete preprocessing, model training, cross-city evaluation, and performance comparison.
- Evaluated how well Airbnb pricing patterns transfer across cities and discussed why local market differences create generalization challenges.

## Files

- `Cross-City_Generalization_in_Airbnb_Price_Prediction.pdf`: final report.
- `data/`: Airbnb listing datasets used for the five-city analysis.
- `simple_model.ipynb`: Initial simple model used as a baseline and workflow check.
- `model_final.ipynb`: Final modeling notebook with preprocessing, model training, evaluation, and cross-city comparison.
- `eda.ipynb`: Exploratory data analysis notebook.
- `eda_insights/`: Saved EDA insights, figures, or summary outputs used to support the report.
