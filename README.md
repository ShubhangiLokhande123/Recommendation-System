# Recommendation System 
## Real world/Business Objectives and constraints 
## Objectives:
Predict the rating that a user would give to a movie that he has not yet rated.

Minimize the difference between predicted and actual rating (RMSE and MAPE) 

## Constraints:
Some form of interpretability.
There is no low latency requirement as the recommended movies can be precomputed earlier.
## Type of Data:
There are 17770 unique movie IDs.

There are 480189 unique user IDs.

There are ratings. Ratings are on a five star (integral) scale from 1 to 5.
There is a date on which the movie is watched by the user in the format YYYY-MM-DD.
Getting Started
Start by downloading the project and run "NetflixMoviesRecommendation.ipynb" file in ipython-notebook.

## softwares and libraries 

Python 3
Anaconda: It will install ipython notebook and most of the libraries which are needed like sklearn, pandas, seaborn, matplotlib, numpy, scipy.
XGBoost
Surprise
Installing
Python 3: https://www.python.org/downloads/
Anaconda: https://www.anaconda.com/download/
XGBoost: conda install -c conda-forge xgboost
Surprise: pip install surprise
Built With
ipython-notebook - Python Text Editor
sklearn - Machine learning library
seaborn, matplotlib.pyplot, - Visualization libraries
numpy, scipy- number python library
pandas - data handling library
XGBoost - Used for making regression models
Surprise - used for making recommendation system models
