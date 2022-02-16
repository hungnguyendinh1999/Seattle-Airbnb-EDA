# Seattle-Airbnb-EDA

### Table of Contents

1. [Installation](#installation)
2. [Business Focus - Questions](#questions)
3. [Data Source and File Description](#files)
4. [Conclusions](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

This project was created with Anaconda Individual Edition, which already has the default packages such as matplotlib, pandas, numpy. Installation instructions can be found [here (Anaconda official site)](https://www.anaconda.com/products/individual).

Please note that the word cloud visualization module "wordcloud" is also used. There is already a !pip command for installation within the notebook. However, if that doesn't work, please attempt installing it manually.

This project uses Python 3.6.8, however this should work for most versions of 3.*.


## Business Focus - Questions<a name="questions"></a>

I built this project surrounding 3 questions for the Seattle Airbnb data:

1. What are the top factors that affects pricing?
2. What makes a good Airbnb (with many good reviews)?
3. When (should you book your Airbnb in advance) is the busiest time in Seattle?


## Data Source and File Description <a name="files"></a>

There is a folder for 3 datasets, which are provided by Airbnb on [this Kaggle page](https://www.kaggle.com/airbnb/seattle). Please visit there for further descriptions.

- listings.csv: all the Airbnb in Seattle, with descriptions, host information, and review scores
- reviews.csv: reviews from the customers
- calendar.csv: price and availability for a given day

Everything else is written by me.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@taylorbplumer/exploring-the-seattle-airbnb-dataset-b78c2d68573c).
