# Starbucks-Capstone-Project-
This is a capstone project of Udacity's Data Scientists  nanodegree.

## Installation
This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/installing.html)
- [scikit-learn](http://scikit-learn.org/stable/)
- [Jupyter-Notbook](https://jupyter.org/install.html)

I used [Anaconda](https://www.continuum.io/downloads) for this project.

## Project Motivation
Once every few days, Starbucks sends out offers to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free) or just informational message regarding their new product or opening of a new store near them, etc. According to the project description, some users might not receive any offers during certain weeks. Not all users receive the same offer, and that is the challenge to solve with this data set.
In this project, my main aim is to determine which demographic groups respond best to which offer type. To know that, firstly I am going to do the expository analysis and to see the relationship of customers' demographic information with their purchasing pattern and response to the particular offer types.

## File Descriptions

The data is contained in three files:
* portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.).
* profile.json - demographic data for each customer.
* transcript.json - records for transactions, offers received, offers viewed, and offers completed.

Here is the schema and explanation of each variable in the files:

### portfolio.json
* id (string) - offer id
* offer_type (string) - type of offer ie BOGO, discount, informational
* difficulty (int) - minimum required spend to complete an offer
* reward (int) - reward given for completing an offer
* duration (int) - time for offer to be open, in days
* channels (list of strings)

### profile.json
* age (int) - age of the customer
* became_member_on (int) - date when customer created an app account
* gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
* id (str) - customer id
* income (float) - customer's income

### transcript.json
* event (str) - record description (ie transaction, offer received, offer viewed, etc.)
* person (str) - customer id
* time (int) - time in hours since start of test. The data begins at time t=0
* value - (dict of strings) - either an offer id or transaction amount depending on the record

## Analysis Summary
A blog on this is available at ( https://medium.com/@kapilwankhede22/starbucks-capstone-challenge-31d694e25e19 )
