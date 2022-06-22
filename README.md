# Custom-errors-for-cross-validation-using-crossval-crossval_ml

The details of the codeset and plots are included in the attached Adobe Acrobat reader (.pdf) file in this repository. 
You need to download the same to view the contents. There are referrals to other contents in BLUE colour also to follow.

This post is about using custom error measures in crossval, a tool offering generic functions for the cross-validation of Statistical/Machine Learning models. More information about cross-validation of regression models using crossval can be found in this post, or this other one. The default error measure for regression in crossval is Root Mean Squared Error (RMSE). Here, I’ll show you how to obtain two other error measures:

    1.Mean Absolute Percentage Error (MAPE)
    2.Mean Absolute Error (MAE)

Installation of crossval
=========================

From Github, in R console, let’s start by installing crossval:

library("crossval")

