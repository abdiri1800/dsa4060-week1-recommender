# dsa4060-week1-recommender
This repository explores MovieLens user-item ratings and builds two non-personalized movie recommendation baselines
# DSA 4060 Week 1 Popularity Recommender

## Student
- Name: Abdirisak Hussein
- Student number: **668776**

## Project overview
This project explores MovieLens user-item ratings and builds two non-personalized movie recommendation baselines:
1. A minimum-rating popularity baseline.
2. A weighted-rating baseline.

## Dataset
MovieLens latest-small from GroupLens:
https://grouplens.org/datasets/movielens/

The notebook automatically downloads the dataset if `movies.csv` and `ratings.csv` are not present. Retain the accompanying MovieLens README and licence information when distributing the dataset.

## Methods
- Rating-count and average-rating exploration
- User and movie interaction summaries
- Rating distribution
- User-item matrix sparsity
- Minimum-rating popularity recommender
- Weighted-rating recommender
- Basic assertions and parameter sensitivity analysis

## How to run
```bash
pip install -r requirements.txt
google colab notebook notebooks/week1_popularity_recommender.ipynb
```


## Limitations
The recommendations are not personalized and may create popularity bias. New movies with no ratings face a cold-start problem. The system does not model changing preferences over time and does not evaluate diversity, novelty, coverage, or accuracy using a train-test split.

## Repository structure
```text
dsa4060-week1-recommender/
├── data/
├── images/
│   └── top10_recommendations.png
├── notebooks/
│   └── week1_popularity_recommender.ipynb
├── .gitignore
├── README.md
└── requirements.txt
```

