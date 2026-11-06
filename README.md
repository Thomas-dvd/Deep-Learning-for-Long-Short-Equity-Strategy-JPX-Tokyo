# Deep Learning for Long/Short Equity Strategy (JPX Tokyo)

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Domain](https://img.shields.io/badge/Domain-Quantitative_Finance-success)

[![Open in Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/thomasdaviaud/deep-learning-for-long-short-equity-strategy)

This repository contains a deep learning approach to the [Kaggle JPX Tokyo Stock Exchange Prediction](https://www.kaggle.com/competitions/jpx-tokyo-stock-exchange-prediction) challenge. Developed as an academic project, it implements a Multi-Layer Perceptron (MLP) to predict daily stock rankings and simulate a Long/Short equity portfolio.

The pipeline is divided into two main parts:
1. **Data Cleaning & Feature Engineering**: Developed by AdnanCvk, handling JPX dataset specificities (stock splits, missing values, etc.). [Link to the data pipeline](https://www.kaggle.com/code/adncav/nettoyage-dataset).
2. **Deep Learning Model**: This repository focuses on the predictive modeling phase, including feature construction (candlestick shadows, sector-relative returns), batch generation, and the PyTorch training loop.
