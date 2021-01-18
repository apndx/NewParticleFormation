# New Particle Formation

Term project for Helsinki University Introduction to Machine Learning course

This project report is for the Helsinki University course Introduction to Machine Learning. The
report describes the development of an event classifier for a new particle formation data set. The
main goal was to find a binary classifier that could separate event days from nonevent day, predict
how probable these outcomes are and additionally get a multi class prediction for three types of
event classes and nonevent. The project consists of data analysis, model and feature selection, and
model hyper parameter tuning. The performance of the solution was tested in a challenge with a
separate data set where the target values were hidden.

After initial data analysis and exploration decision tree and random forest were compared, and
random forest was chosen and further toned. Predictions for the challenge were made with two
separate random forest models. The overall challenge ranking for the solution was eleventh, and this
was also the ranking of the binary classifier. Best performing part was the multi class classifier that
produced fourth best performance. The worst performing part of the solution was of the perplexity
of the binary classification probabilities. After the challenge some improvements for the perplexity
and model accuracy were found from model calibration.

Jupyter notebook file has with the data analysis and machine learning model code and the report file pdf has the summary of the results.
