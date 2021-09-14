### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Data](#data)
5. [Results](#results)


## Installation <a name="installation"></a>
For development, the following dependencies were used:
- [Pandas](https://pandas.pydata.org)
- [Numpy](https://numpy.org)
- [Seaborn](https://seaborn.pydata.org)
- [Matplotlib](https://matplotlib.org)
- [Calendar](https://docs.python.org/3/library/calendar.html)
- [Sklearn](https://scikit-learn.org/stable/)
- [NLTK](https://www.nltk.org/data.html)

## Project Motivation <a name="motivation"></a>
Choosing well where you are going to stay, is one of the crucial points of any trip to avoid future frustrations. So, analyzing the Airbnb data provided by Kaggle, I decided to answer the following questions:

1. *When do people usually visit Boston?*
2. *Who are the users who rent on AirBnB?*
3. *Which fields most influence rental prices?*
4. *But after all, what do customers have to say?*

## File Descriptions <a name="files"></a>
The following are the files available in this repository:

- `Exploratory.ipynb` - notebook for the complete exploratory analysis of the data following the CRISP-DM criteria.
- `Explanatory.ipynb` - notebook for exploratory data analysis according to CRISP-DM criteria. More condensed than the previous one.
- `listings_reviews.csv` - csv used to help with internal functions (save runtime) 
- `boston/calendar.csv` - csv containing the temporal data of the houses (**id**, **date**, **availability**, **price**)
- `boston/listings.csv` - csv containing the most important data for the analysis, such as _neighborhoods_, _prices_, _house characteristics_ and _score reviews_ for example
- `boston/reviews.csv` - csv containing the data regarding the comments that the users made for each experience (**home id**, **user id**, ..., **comments**)
- `images/*` - all graphics obtained through this study

## Data <a name="data"></a>
All data used in this study are from **Airbnb**, provided by **[Kaggle](https://www.kaggle.com)** at [Boston Airbnb Open Data: A sneak peek into the Airbnb activity in Boston, MA, USA](https://www.kaggle.com/airbnb/boston).

## Results <a name="results"></a>
