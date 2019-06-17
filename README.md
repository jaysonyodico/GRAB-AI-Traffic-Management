# GRAB-AI-Traffic-Management

Entry for the GRAB AI for SEA Data Science challenge

This project seeks to accurately forecast travel demand on a specific area and time based on historical Grab bookings. This project proposes a unique approach of determining performing models among a multitude of possible configurations, which utilizes a combination of machine learning, fourier transform, and genetic algorithm.

## Getting Started

This repository contains two jupyter notebooks:
- `MODEL DEVELOPMENT.ipynb`. This notebook provides a detailed documentation on how the author arrived at the data model. The notebook also contains instructions and docstrings necessary to run every function in the notebook.

- `PREDICTING THE HOLDOUT DATASET.ipynb`. This notebook contains the codes that are needed to make predictions for the holdout dataset. The code is able to automatically create the desired features for evaluation of the Hold-out test set.

It is highly recommended to go through `MODEL DEVELOPMENT.ipynb` before proceeding to `PREDICTING THE HOLDOUT DATASET.ipynb`.

### Prerequisites

The notebook runs on Python 3.6. The following packages are necessary to run the notebook:
```
pandas
numpy
matplotlib
pygeohash

scipy
tensorflow
sklearn
itertools
os
```

Due to the high computational requirements, it is highly recommended to run on a 8-CPU 16GB-memory resource.

### Installation

No installation needed. Just run the codes on each cell.

## Built With

* Python 3.6.

## Authors

* **Jayson Yodico** - [jaysonyodico](https://github.com/jaysonyodico)

## Acknowledgements

* Asian Institute of Management's Analytics, Computing, and Complex Systems (ACCeSs) Laboratory for lending the necessary computational resources to accomplish this project.
