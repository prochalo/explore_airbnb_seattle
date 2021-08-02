# Plan a trip to Seattle at a low price by using Seattle AirBnB
<p align="center">
  <img src="https://miro.medium.com/max/1400/1*-G93YyAeZLYLWNHKPqe9Tw.jpeg">
</p>

This project was done as a part of Udacity Data Scientist Nanodegree.

Link to the article is [here](https://medium.com/@chalothorn.cha/plan-a-trip-to-seattle-at-a-low-price-by-using-seattle-airbnb-3972d441b572)

### Table of Contents
1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Data](#data)
4. [Code](#running)
5. [Results](#results)
6. [Acknowledgements](#acknowledgements)

### Introduction<a name="introduction"></a>

The objective of this project is to analyse data from Seattle AirBnB to clarify the questions.

1. What is the most occupancy by month in 2016?
2. Which month is the most expensive?
3. Which day is the most costly?
4. Is the host respond to you appropriately?
5. What features were affected the price?

This project follows CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology. It consists of business understanding to evaluation.


### Prerequisites<a name="prerequisites"></a>

- Pandas (for data loading and analysis)
- Matplotlib (datavisualizations)
- Seaborn (data visualizations)
- Calendar (help convert integer to month name)


### Dataset<a name="data"></a>
There are three files in the dataset folder.
- calendar.csv - contains listing id and the price and availability in the specific date range.
- listings.csv - many features and details about listing with review scores.
- reviews.csv - reviews from reviewers and including comments from renters.

### Code<a name="running"></a>

Just one file in the root folder, I prefred to
- explore_seattle_airbnb.ipynb, which contains data manipulation and explore data analysis parts using 3 csv files in the dataset.

### Results<a name="results"></a>

- Booking in the 4th quarter will provide you with many choices, especially in December.
- Try to avoid booking between June and August because it had the highest prices in the year.
- Recommended to booking from Sunday to Wednesday, You might get a lower price.
- Avoid hosts that always respond more than 24 hours because they have a high risk of no response.
- However, you usually have a response from the host within an hour.
- The number of accommodate, bathrooms, beds and bedrooms can increase the booking price.
  
### Acknowledgements<a name="acknowledgements"></a>

This project use data from [Kaggle] (https://www.kaggle.com/airbnb/seattle)