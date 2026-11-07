# Python-for-ML-and-Econometrics
This repository contains my notebooks from my journey in python. 

Python has become one of the main programming language worldwide, there is not a specific reason for choosing python over other languages, and is not the scope of this repository to convince anybody. Here i post my notebook showing my progress over this languages. 

## Objectives
It is important to set goals, mine are about understanding how to implement rigorous and reproducible scientific analysis: 
- Statistical analysis;
- Modern machine learning;
- Deep Learning;
- Econometrics analysis.

Of course, i'm aware that topics are so diverse and may require different degree just to capture in depth one of the argument. Here i'm not putting myself as the oracle of the python tribe, but as just an everlong learning enjoyers.



## Contents

| Folder | Notebook | What's inside | |
|---|---|---|---|
| `/` | `distribution.ipynb` | Binomial distribution and PMFs: simulation vs. closed form, following Allen Downey's *Think Stats* (featuring Italian trains and their questionable punctuality) | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AlessandroCaforio/Python-for-ML-and-Econometrics/blob/main/distribution.ipynb) |
| `/` | `Data_preprocessing.ipynb` | Missing data (mean and KNN imputation + a home-made imputer), ordinal vs. nominal encoding, one-hot, `ColumnTransformer`, train/test split, scaling on the Wine dataset | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AlessandroCaforio/Python-for-ML-and-Econometrics/blob/main/Data_preprocessing.ipynb) |
| `Regression/` | `Linear_regression.ipynb` | OLS as a projection onto the column space, the normal equation, `sklearn` comparison, Ames housing data | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AlessandroCaforio/Python-for-ML-and-Econometrics/blob/main/Regression/Linear_regression.ipynb) |
| `Regression/` | `Logistic_Regression.ipynb` | Odds, logit and the sigmoid. 🚧 *Work in progress* | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AlessandroCaforio/Python-for-ML-and-Econometrics/blob/main/Regression/Logistic_Regression.ipynb) |
| `/` | `classifiers.ipynb` | Iris dataset, stratified split, feature scaling, Perceptron, decision-region plots | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AlessandroCaforio/Python-for-ML-and-Econometrics/blob/main/classifiers.ipynb) |
| `/` | `taxi-eda.ipynb` | EDA on NYC motor vehicle collisions: weekly/hourly patterns, spatial distribution, first attempt at predicting hourly injuries | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AlessandroCaforio/Python-for-ML-and-Econometrics/blob/main/taxi-eda.ipynb) |
| `Deeplearning/` | `Makermore-ITA.ipynb` | A character-level MLP language model trained on Italian words, inspired by Andrej Karpathy's [makemore](https://github.com/karpathy/makemore), rewritten with my own OOP classes in PyTorch | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AlessandroCaforio/Python-for-ML-and-Econometrics/blob/main/Deeplearning/Makermore-ITA.ipynb) |

---

## How to run

**Easiest:** click a Colab badge above. Zero setup, someone else's GPU.

**Locally:**

```bash
git clone https://github.com/AlessandroCaforio/Python-for-ML-and-Econometrics.git
cd Python-for-ML-and-Econometrics
pip install pandas numpy scipy scikit-learn matplotlib seaborn mlxtend empiricaldist torch
jupyter lab
```

## Data

Most notebooks download their data on the fly (UCI Wine, Ames housing, Iris). Two don't, so you'll need to grab the files yourself:

- **`taxi-eda.ipynb`**: NYC Open Data, *Motor Vehicle Collisions – Crashes* (dataset id `h9gi-nx95`). Save the CSV as `Data/nyc_h9gi-nx95.csv`.
- **`Makermore-ITA.ipynb`**: a list of Italian words, one per line, saved as `parole.txt`. Source: TODO

---

## Objectives

The goal is learning how to do **rigorous and reproducible** quantitative analysis in Python:

- [x] Statistical analysis
- [x] Machine learning
- [x] Deep learning (first steps)
- [ ] Econometrics: IV, panel data, time series *(the title promised it, I know. It's coming.)*

Yes, each of these topics deserves a whole degree on its own. I'm doing them in parallel anyway. 🙃
