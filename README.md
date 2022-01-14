# Flight Fare Prediction: 

## Table of Content
  * [Demo](#demo)
  * [Overview](#Overview)
  * [Motivation](#motivation)
  * [Installation](#installation)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Directory Tree](#directory-tree)
  * [Bug / Feature Request](#bug---feature-request)
  * [Future scope of project](#future-scope)


## Demo
Link: [https://flight-price-prediction-api.herokuapp.com/](https://flightpricepredictionn.herokuapp.com/)

## Overview
Flight ticket prices can be something hard to guess, today we might see a price, check out the price of the same flight tomorrow, and it will be a different story.
To solve this problem, we have been provided with prices of flight tickets for various airlines between various cities

## AIM
we aim to build a model which predicts the prices of the flights using various input features..

## Motivation
What to do when you are at home due to this pandemic situation? I started to learn Machine Learning model to get most out of it. I came to know mathematics behind all supervised models. Finally it is important to work on application (real world application) to actually make a difference.

## Installation
The Code is written in Python 3.6.10. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Deployement on Heroku
Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project.

[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)

Our next step would be to follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Directory Tree 
```
├── static 
│   ├── css
├── template
│   ├── flight.html
├── Procfile
├── README.md
├── app.py
├── untitle.ipynb
├── DT_regressor_flight.pkl
├── RF_regressor_flight.pkl
├── requirements.txt
```

## Bug / Feature Request

If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an [issue](https://github.com/Priyam-Trivedi/flight_price_prediction/issues) here by including your search query and the expected result

## Future Scope

* Use multiple Algorithms
* Optimize Flask app.py
* Front-End 

