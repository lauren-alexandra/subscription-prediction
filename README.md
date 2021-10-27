# Subscription Prediction

Identified potential customers for subscribing to a term deposit.

## Data

The [data](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing) is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

## Model Performance and Selection

The Bagging Classifier obtains the best recall performance. Ultimately we want more clients to subscribe term deposit so we want to decrease false negatives. For these reasons, I selected this algorithm and metric.

## Built with

- [Scikit-learn](https://scikit-learn.org/) - Simple and efficient tools for predictive data analysis.
- [NumPy](https://numpy.org/) - A library adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.
- [Pandas](https://pandas.pydata.org/) - A data analysis and manipulation library.
- [Matplotlib](https://matplotlib.org/) - A comprehensive library for creating static, animated, and interactive visualizations in Python.
- [Seaborn](https://seaborn.pydata.org/) - A data visualization library for statistical graphics plotting in Python.
- [Yellowbrick](https://www.scikit-yb.org/) - A suite of visual analysis and diagnostic tools designed to facilitate machine learning with scikit-learn.
