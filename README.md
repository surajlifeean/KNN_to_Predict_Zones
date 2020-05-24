# KNN_to_Predict_Zones
The repository has python code to predict if any area falls under red, green or orange zone based on the last recorded case and current case count.

Classification is the process of grouping your data into different classes. Currently to classify the districts into Red, Green and Orange Covid19 zones in India authorities of states and center looks into current case count and the last recorded case duration to mark these zones. 
So, the idea is to come up with a classifier using K nearest neighbor algorithm(KNN) that does the job and I have it here. It correctly predicted 70% of test data. The challenge was to obtain and clean the data set as zone and district-wise time series counts were to be obtained from different API calls and supposed to be processed to bring to a desirable format.
