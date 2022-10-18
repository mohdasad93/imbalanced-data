# Analysing Bank Telemarketing Performance

# About the Project
This project examines the direct phone call marketing efforts used by a Portuguese bank to encourage term deposits among current clients. From May 2008 to November 2010, the campaigns were run and has more than 41,000 records.

In order for the bank to concentrate its marketing efforts on the most receptive consumers, the key goal is to predict customers' responses to upcoming marketing initiatives using classification-based models. The models would assist the bank in securing deposits more effectively, saving on marketing expenses, and cutting back on annoying client adverts.

# Our Goal:

Understand the little distribution of the "little" data that was provided to us.

Analyse the performance of the various classification models through confusion matrix, accuracy and precision.

Applying the Undersampling and Oversampling technique to have a more balanced data set and employ classification based models. 

Determine the Classifiers we are going to use and decide which one has a higher accuracy.

# Correct procedure to deal Imbalanced Datasets:

Never test on the oversampled or undersampled dataset.

If we want to implement cross validation, remember to oversample or undersample your training data during cross-validation, not before!

Don't use accuracy score as a metric with imbalanced datasets (will be usually high and misleading), instead use f1-score, precision/recall score or confusion matrix

# Data Source

The dataset is publicly available in the UCI Machine Learning Repository, which can be retrieved from http://archive.ics.uci.edu/ml/datasets/Bank+Marketing#.
