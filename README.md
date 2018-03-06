# Titanic-Kaggle
Files of my Titanic Kaggle Competition.

These include:
- *Titanic datatreatment*: prepares the data to be fed to the models. Dummies categorical, scales numerical, engineers new features.
- *Titanic EDA*: Exploratory Data Analysis of the treated data.
- *Titanic CV model selection*: a comprehensive grid parameter scan of different models. It outputs data-frames (into CSV files) of the results for different parameters.
- *DNN CV model selection*: grid parameter scans for multiperceptron models, using Keras and SciKit.
- *CV analyser*: a notebook to study the results of Titanic CV model selection.
- *Titanic Submission Predictions*: The generator of prediction files. It employs the best estimators assessed at CV analyser, and produces further ensemble predictions with voting.
- *Titanic Deck Predictor*: an attempt to predict the deck to fill missing values. These turn out to worsen the predictions for survival chances and are therefore ignored for now.
