# Fraud-Investigation-on-the-Enron-Email-and-Financial-Dataset

### Introduction
In 2000, Enron was one of the largest companies in the United States. By 2002, it had collapsed into bankruptcy due to widespread corporate fraud. In the resulting Federal investigation, there was a significant amount of typically confidential information entered into the public record, including tens of thousands of emails and detailed financial data for top executives.

[In addition to being the largest bankruptcy reorganization in American history at that time, Enron was cited as the biggest audit failure](http://en.wikipedia.org/wiki/Enron_scandal).From a $90 price per share, to a $1 value represents the huge value loss and scam that happened in Enron. 

This case has been a point of interest for machine learning analysis because of the huge real-world impact that ML could help out and try to figure out what went wrong and how to avoid it in the future. It would be of great value to find a model that could potentially predict these types of events before much damage is done, so as to permit preventive action. Corporate governance, the stock market, and even the Government would be quite interested in a machine learning model that could signal potential fraud detections before hand.

Utilizing `scikit-learn` and machine learning methodologies, I built a "person of interest" (POI) identifier to detect and predict culpable persons, using features from financial data, email data, and labeled data--POIs who were indicted, reached a settlement or plea deal with the government, or testified in exchange for prosecution immunity.

### File Information
* [`verify.py`](https://github.com/arjunchndr/Fraud-Investigation-on-the-Enron-Email-and-Financial-Dataset/blob/master/verify.py): Functions for validation and evaluation of classifier, dumping and loading of pickle files.
* [`classifier.pkl`](https://github.com/arjunchndr/Fraud-Investigation-on-the-Enron-Email-and-Financial-Dataset/blob/master/classifier.pkl): Pickle file for final classifier from `verify.py`.
* [`dataset.pkl`](https://github.com/arjunchndr/Fraud-Investigation-on-the-Enron-Email-and-Financial-Dataset/blob/master/dataset.pkl): Pickle file for final dataset from `verify.py`.
* [`feature_list.pkl`](https://github.com/arjunchndr/Fraud-Investigation-on-the-Enron-Email-and-Financial-Dataset/blob/master/feature_list.pkl): Pickle file for final feature list from `verify.py`.
* [`Enron_Dataset.pkl`](https://github.com/arjunchndr/Fraud-Investigation-on-the-Enron-Email-and-Financial-Dataset/blob/master/Enron_Dataset.pkl)
* [`feature_format.py`](https://github.com/arjunchndr/Fraud-Investigation-on-the-Enron-Email-and-Financial-Dataset/blob/master/feature_format.py): Functions to convert data from dictionary format into numpy arrays and separate target label from features to make it suitable for the machine learning processes.

## Getting Started

Download the Jupyter [notebook](https://github.com/arjunchndr/Fraud-Investigation-on-the-Enron-Email-and-Financial-Dataset/blob/master/Fraud%20Investigation%20on%20the%20Enron%20Email%20and%20Financial%20Dataset.ipynb) if you have all the dependencies listed below.

Head over [here](http://nbviewer.jupyter.org/github/arjunchndr/Fraud-Investigation-on-the-Enron-Email-and-Financial-Dataset/blob/master/Fraud%20Investigation%20on%20the%20Enron%20Email%20and%20Financial%20Dataset.ipynb) to view project on [Jupyter Notebook Viewer](http://nbviewer.jupyter.org/).

You could also download the `html` version of my project from [here](https://github.com/arjunchndr/Fraud-Investigation-on-the-Enron-Email-and-Financial-Dataset/blob/master/Fraud%20Investigation%20on%20the%20Enron%20Email%20and%20Financial%20Dataset.html) and open the file using a web browser of your choice.

## Built With

* [Anaconda](https://www.anaconda.com/download/) - Distribution pre-installed with Python and its associated packages
  * [Python 3.6.3](https://www.python.org/downloads/) 
  * [Pandas](http://pandas.pydata.org/pandas-docs/stable/install.html) 
  * [Jupyter 5.1.0](http://jupyter.org/install.html)
  * [Matplotlib 2.1.1](https://matplotlib.org/users/installing.html#installing-an-official-release)
  * [seaborn 0.8.0](https://seaborn.pydata.org/installing.html)
  * [scikit-learn 0.19.1](http://scikit-learn.org/stable/install.html)
