# Purpose

This document is for alternating least square matrix factorization model used in recommendation system prototype. Specifically, the model is based on implicit rating of both customer watching frequency and dummy customer behaviors.

The whole system is based on PySpark, and Rank Ordering Error Metric (ROEM), the metric used to evaluate the model, is not defined.  So two functions, ROEM.py and ROEM_cv.py, have been written.

# Content

1. ROEM.py

   This function is for using ROEM to evaluate the performance of the model.

2. ROEM_cv.py

   This function is for using ROEM to cross validate performance of the model with different combination of hyperparameters, and return the optimal setting of hyperparameters.

3. to_long.py

   This function is used to convert wide format to long format. This is because of the requirements of ML package in PySpark.
