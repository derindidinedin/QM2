# Quantitative Methods 2: Data Science and Visualisation

My completed workbooks for **BASC0005 Quantitative Methods 2: Data Science and Visualisation** at University College London (2023-24).

The module teaches quantitative skills with an emphasis on the context and use of data, working with datasets that explore questions in society, from economics and inequality to criminal justice and policy. Each week combines Python for data manipulation (cleaning and segmentation), analysis (descriptive statistics through to causal inference) and visualisation (graphing and mapping).

The workshop notebooks were written by the module convenor, [Dr Ollie Ballinger](https://oballinger.github.io/BASC0005/), and the originals are in [oballinger/BASC0005](https://github.com/oballinger/BASC0005). This repository contains my own runs of each notebook, with my answers to the exercises and extensions.

The module is assessed through a group research project. Ours is **[Crime in London](https://github.com/derindidinedin/Crime-in-London)** ([project website](https://derindidinedin.wixsite.com/crimeinlondon)), which studies how income, education and employment relate to crime hotspots across London boroughs, using regression, Poisson models and k-means clustering.

## Workshops

| Week | Notebook | Methods and tools |
|---|---|---|
| 1 | [Python Recap](notebooks/W01_Python_Recap.ipynb) | Python fundamentals, pandas, matplotlib |
| 2 | [Intro to Pandas](notebooks/W02_Intro_to_Pandas.ipynb) | Loading, indexing and filtering dataframes, comparing distributions across segments |
| 3 | [Spatiotemporal Data](notebooks/W03_Spatiotemporal_Data.ipynb) | Time series with datetime, grouping and aggregation, interactive maps (ipyleaflet) |
| 4 | [Natural Language Processing](notebooks/W04_Natural_Language_Processing.ipynb) | Regular expressions on company earnings calls, term-frequency comparison (scattertext), sentiment analysis of tweets (spaCy, TextBlob) |
| 5 | [Distributions and Basic Statistics](notebooks/W05_Distributions_and_Basic_Statistics.ipynb) | Summary statistics, sampling bias, the central limit theorem (SciPy, seaborn) |
| 6 | [Merging and Joining](notebooks/W06_Merging_and_Joining.ipynb) | Joins, merges and concatenation in pandas, handling non-unique keys |
| 7 | [Hypothesis Testing](notebooks/W07_Hypothesis_Testing.ipynb) | Confidence intervals, standard error, hypothesis tests |
| 8 | [Regression](notebooks/W08_Regression.ipynb) | Linear regression with statsmodels, checking independence, homoscedasticity and multicollinearity |
| 9 | [Difference in Differences](notebooks/W09_Difference_in_Differences.ipynb) | Panel regression (linearmodels), causal inference with difference in differences |
| 10 | [Regression Discontinuity](notebooks/W10_Regression_Discontinuity.ipynb) | Sharp and fuzzy regression discontinuity, kernel weighting, the McCrary density test |

## Running the notebooks

Each notebook has an **Open in Colab** button at the top. Weeks 2 to 10 download their own data, so they run in Google Colab without any setup. Week 1 asks for a file upload.

## Tools

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?logo=scipy&logoColor=white) ![statsmodels](https://img.shields.io/badge/statsmodels-4051B5) ![linearmodels](https://img.shields.io/badge/linearmodels-4051B5) ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C) ![seaborn](https://img.shields.io/badge/seaborn-4C72B0) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?logo=plotly&logoColor=white) ![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?logo=geopandas&logoColor=white) ![Leaflet](https://img.shields.io/badge/Leaflet-199900?logo=leaflet&logoColor=white) ![spaCy](https://img.shields.io/badge/spaCy-09A3D5?logo=spacy&logoColor=white) ![NLTK](https://img.shields.io/badge/NLTK-4B8BBE) ![scattertext](https://img.shields.io/badge/scattertext-4B8BBE) ![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?logo=googlecolab&logoColor=white)
