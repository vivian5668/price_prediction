# price_prediction

Regression Case Study
======================

In today's exercise you'll get a chance to try some of what you've learned
about supervised learning on a real-world problem.

The goal of the contest is to predict the sale price of a particular piece of
heavy equipment at auction based on its usage, equipment type, and
configuration.  The data is sourced from auction result postings and includes
information on usage and equipment configurations.



Evaluation
======================
The evaluation of your model will be based on Root Mean Squared Log Error.
Which is computed as follows:

![Root Mean Squared Logarithmic Error](images/rmsle.png)

where *p<sub>i</sub>* are the predicted values and *a<sub>i</sub>* are the
target values.

Note that this loss function is sensitive to the *ratio* of predicted values to
the actual values, a prediction of 200 for an actual value of 100 contributes
approximately the same amount to the loss as a prediction of 2000 for an actual
value of 1000.  To convince yourself of this, recall that a difference of
logarithms is equal to a single logarithm of a ratio, and rewrite each summand
as a single logarithm of a ratio.

Data for this case study comes from Galvanize 
https://github.com/gSchool/dsi-regression-case-study

