# ML_indoor_positioning_project
Final project for Data Science course in Royal Holloway university

Machine learning based indoor positioning

Data Set Used: UJIIndoorLoc Data Set
  https://archive.ics.uci.edu/ml/datasets/ujiindoorloc
  

The localisation of users is straightforward when it comes to outdoor localisation as the GPS signals are strong and it is easy to track a user outdoors. However, the problem occurs when a user is to be located indoors where GPS signals are very weak and cannot be used for determining the location of the user. The data set provided focuses on WLAN fingerprinting based methods for finding the location of the user. The location can be determined in terms of latitude and longitude or even by stating which building and floor the user is present. Our problem is to predict such data by training machine learning models on the provided dataset. The predictions mainly need to focus on solving the problem of indoor localisation. In this work, we’ve primarily used the concepts from Supervised Machine Learning to perform classification and regression predictive tasks and have done a thorough analysis using data visualization techniques to understand the underlying structure of the dataset as well.



Summary:

From the multiple methods used to solve various classification and regression problems we can combine a few of them to solve the main problem, which is indoor localisation. We have predicted latitude and longitude based on the WLAN fingerprinting values which to an extent give us the location of the user, however when we are solving the problem of indoor localisation parameter prediction like building id and floor number, it can be helpful for us to accurately determine the position of the user even in the 3rd dimension for which we could not do using latitude and longitude. Thus the combination of all these problems helps us to address the main issue of indoor localisation. We have also predicted the user id, which does not directly address the problem of indoor localisation, however it can be used to predict which user would be present at a position, if the user is from the training dataset itself. This can help in user tracking and other such problems.
