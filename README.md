# CaptchaSolvingWithDeepLearning
Captcha Solving with Deep Learning

# PROBLEM STATEMENT 
The CAPTCHA has become an important issue in multimedia security. Aimed at a commonly used text-based CAPTCHA, this project outlines some typical algorithms and summarizes the technological progress in text-based CAPTCHA breaking. 
CAPTCHAs were designed to prevent computers from automatically filling out forms by verifying that you are a real person. But with the rise of deep learning and computer vision, they can now often be defeated easily. 
This project is focused on automatic character recognition from multiple text-based CAPTCHA images using convolutional neural networks (CNNs) and random forest classifier.

# OBJECTIVE
The final goal of this project is to take captcha letters as an input while outputting transcription of the text presented in the captcha. In this project a framework of text-based CAPTCHA breaking technique is proposed. 
First, extracting single letter from captcha images. Second, train the neural network to recognize single letters and using this model to solve captchas. 
Python3, OpenCV, Kera's, TensorFlow are the toolset which are used in this project for breaking the captcha.

# ALGORITHM USED FOR CAPTCHA PREDICTION

Convolutional Neural Network
Random Forest Classifier
K-nearest neighbor algorithm

# CONVOLUTIONAL NEURAL NETWORK

Used a simple convolutional neural network (CNN) architecture with two convolutional layers and two fully-connected layers.
CNN algorithm consist of first and second convolutional layer with max pooling, one hidden layer with 500 nodes and output layer with 32 nodes.
After 10 passes over the training data set, It hit nearly 99.32% accuracy. At this point, we are be able to automatically bypass any CAPTCHA whenever we want.


# RANDOM FOREST CLASSIFIER

We are using Random forest classifier as our second algorithm because of its simplicity and diversity as it can be used for both classification and regression tasks.
We are considering 100 n_estimators before taking the average of prediction.
N_jobs is an integer, specifying the maximum number of concurrently running workers, we have set that variable to (-1).
After training and testing the model with 26124 images we hit nearly 99.94% accuracy. 

# K-NEAREST NEIGHBORS ALGORITHM

K-nearest neighbor algorithm (KNN) is our third algorithm used for captcha prediction, it is one of the simplest of classification algorithms available for supervised learning. 
The idea is to search for closest match of the test data in feature space of the image given. After plotting the training points we got 4 clusters groups. 
So, we are considering 4 (k_range) iteration before taking the prediction accuracy of the captcha. 
After 4 iterations over the training and testing data set, we hit nearly 98.78% accuracy. 

# CONCLUSION

