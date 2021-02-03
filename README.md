
### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
- python 3.7.7
- scikit-learn 0.23.1
- seaborn 0.10.1
- matplotlib 3.3.1
- numpy 1.18.5
- pandas 1.1.0

## Project Motivation<a name="motivation"></a>

This Project is based on Airbnb Seattle data provded by [kaggle.com](https://www.kaggle.com/airbnb/seattle). Using the data following business questions were answered:

1. What are the type of properties that are listing in?
2. Neighborhood wise price distribution
3. How is the price correlated with other numerical independent variables ?
4. How does the price vary with geographically ?
5. Can I make a model that predict the price?

## File Descriptions <a name="files"></a>
In this repository following files included:
- examine_the_data.ipynb - above mentioned business questions wered answered using visualization
- Data_modeling.ipynb - this notebook contains the machine learning model building and evaluation
- Data Folder - this folder contains the all neccessary data and file use for the model
  - calendar.csv - including listing id and the price and availability for that day
  - listings.csv - including full descriptions and average review score
  - reviews.csv - including unique id for each reviewer and detailed comments
  - seattle.png - map of seattle area

## Results<a name="results"></a>

The main findings of the code can be found at the post available @ [Medium](https://ksekara.medium.com/deep-dive-into-seattle-airbnb-data-f198143f6492).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
Credit to Airbnb for providing the data. Licensing information can be found at the [Kaggle page](https://www.kaggle.com/airbnb/seattle) and the original source from [Airbnb Inside](http://insideairbnb.com/get-the-data.html).


  
