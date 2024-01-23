# House Prices: Advanced Regression Techniques

This repository contains a comprehensive data analysis project on the Kaggle dataset [House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data). The project aims to explore, clean, and model the dataset to predict house prices accurately.

## Project Overview

The project is structured in three main phases:

1. **Data Exploration**:
   - Deep dive into relationships between variables.
   - Examination of numerical, categorical, and temporal variables and their impact on housing prices.
   - Analysis of missing values and their proportions in the dataset.

2. **Data Engineering**:
   - Data cleaning including handling missing values:
     - Numerical missing values are replaced with medians due to the presence of outliers.
     - Categorical missing values are labeled as "missing".
   - Management of rare categorical values by labeling them as "rare".
   - Encoding of categorical features.
   - Application of MinMaxScaler to the entire dataset.
   - The cleaned and transformed data is saved as `X_train.csv`.

3. **Feature Selection**:
   - Extraction of the most significant features from a total of 82 features.

Each file in this repository can be run independently but is based on the same dataset. Some design choices made in each file are from insights gathered in previous steps.

## Data Files

The repository includes the following data files:
- `train.csv`: Raw training data from Kaggle.
- `test.csv`: Raw test data from Kaggle.
- `X_train.csv`: Transformed training data post data engineering.

## Getting Started

### Prerequisites

- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn (Install these using `pip install <library>`)

### Installation

Clone the repository using:

```bash
git clone https://github.com/Ling01234/house-price-prediction
```


## Acknowledgements
- Kaggle for providing the dataset
- [Krish Naik](https://www.youtube.com/@krishnaik06) for his clear tutorials