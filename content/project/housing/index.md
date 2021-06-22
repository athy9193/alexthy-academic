---
title: Housing Price Predictor
summary: Predicting residential housing prices in Ames, Iowa using advanced regression techniques
tags:
- Deep Learning
date: "2021-05-30T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: "https://www.kaggle.com/alextruong91/housepricepredictor"
# to have a project page
# external_link: ""

image:
  caption: Photo by [Paul Kapischka](https://unsplash.com/@kapischka) on Unsplash
  focal_point: Smart

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

This project is my attempt to apply data science and machine learning techniques in real estate investment aspect. It was structured to follow a standard machine learning framework, which can be adopted and further developed for other projects, from splitting of train and test data, EDA, preprocessing, selection of evaluation metric, model training, hyperparameter tuning.

Using CatBoostRegressor with hyperparameter tuning, the predictor achieved Mean Absolute Percentage Error (MAPE) at around 9% on validation set.

#![results](/static/housing/results.png)
