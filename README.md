This project uses a collaborative filtering technique with implicit feedback. A situation whereby no specific input such as rating is required of the customer/user. It only based on some sort of interaction between the customers and the products.
After the data is prepared and cleaned for analysis. Sparse matrix of ( non zero interactions between customers and products is used to mitigate against the memory usage and computing time) is fed into ALS model.
The recommender system was able to recommend next best product to the customer based on his historic purchase. After evaluating the model it performed so well  With AUC of 77.5%.We now have our recommender system trained and have proven it beats the benchmark of popularity. An AUC of 0.77 means the system is recommending items the user in fact had purchased in the test set far more frequently than items the user never ended up purchasing.
