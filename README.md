# Vertical-Ground-Motion-Model-for-the-NGA-West2-Database-Using-Deep-Learning-method
The codes show how to predict vertical PGA,PGV and 5% damped PSA under a specific source, path and site condition using a refined second-order deep neural network.

The codes are developed based on Python with Tensorflow and the description of the codes are as follows:

Simple_example.py: This code can produce the attenuation relationship under a specific source, path and site condition which was described in the csv file 'pga.csv' . One can easily run this code by editing this csv file.

pga.csv: This file provides the source, path, and site condition for the prediction in 'Simple_example.py'.The parameter from the first column to the last column means Fault Type, Ztor, M, RJB, Region, Vs30, z1 and T respectivly.
