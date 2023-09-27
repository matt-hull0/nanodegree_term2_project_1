## Introduction

This repo is for the Udacity Datascience Nanodegree Term 2 Project 1, where data from Airbnb has been analysed.

Specifically data from Seattle, where business questions have been proposed and a Jupyter notebook used to answer them.
A blog post has also been written to share the resultsm and can be found [here](https://medium.com/@matthewhull56/this-is-why-airbnb-owners-want-your-good-reviews-7781ab4aaaa9)

## Libraries Used

Refer to pyproject.toml for a full list (and poetry.lock for all the sub dependancies). The key libraries used are:
 - numpy
 - pandas
 - seaborn
 - sklearn
 - ydata_profiling

 ## Motivation
I was keen to check out a new data source I have not seen before, so opted for the Seattle Airbnb data. Having stayed at a few Airbnb locations, I am aware on how keen they are on gathering reviews on hosts/locations after stays. I browsed what data was available and came up with questions around what might lead to good/bas reviews, and what the impact of bad/good reviews might be, should I ever become an Airbnb host myself! 

 ## Files

 .
├── README.md
├── data
│   └── seattle_airbnb_open_data
│       ├── calendar.csv
│       ├── listings.csv
│       └── reviews.csv
├── notebook.ipynb
├── poetry.lock
└── pyproject.toml

The data folder contains the data used in the analysis, taken from [kaggle](https://www.kaggle.com/datasets/airbnb/seattle/):

The notebook.ipynb contains the Jupyter notebook, including the 3 business questions.

poetry.lock & pyproject.toml are used by the _poetry_ package for managing libraries.

 ## Summary

 The notebook looks at the following three business quesions:

1. Are properties with better reviews occupied more?

2. Do properties with more details in the listing have better reviews?

3. Can you predict a locations review score based on the listing details?

 (No spoilers here either checkout the notebook or my blog post!)

 ## Acknowledgements

 Kaggle for hosting the data
 Airbnb for making the data available
 Udacity for the training material used to help work through this analysis