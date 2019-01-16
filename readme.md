# Run/walk image recognition with ML and CNN

The dataset contains 745 labelled images of people running or walking. The task is to use those images to train a classification algorithm capable of recognising the difference between these two activities and predicting the correct class for any new unseen images.

I have added two notebooks where you can find the code and the results of two approaches to this problem:

1. Machine Learning approach where I perform feature engineering using PCA and compare predictions from Naive Bayes, SGDClassifier, Random Forest and AdaBoost. The highest test score obtained is 70%.

2. Deep Learning approach where I convert the images to grayscale for faster learning then feed them to a Convolutional Neural Network (CNN) using Keras. The prediction accuracy after 10 epochs stagnated at 60%, which means that the network needs more data for better prediction rates. 
