# Cat and Dog Image Classification
This repository contains a machine learning project that aims to classify images of cats and dogs using various classification algorithms. The project involves exploring different classifiers, feature extraction techniques, and evaluating their performance.

## Dataset
The dataset is organized into three main folders:

* training_set: This folder contains images intended for training the models.
* test_set: This folder includes images for testing the trained models.
* unseen_data: Here, you'll find images specifically for evaluating the models on unseen data.
  
Each image in the dataset is categorized into one of two classes: cats or dogs.

## Classifiers Explored
1. __K-Nearest Neighbors (KNN):__ We experimented with different values of n_neighbors to find the optimal parameter for the KNN classifier. The accuracy scores were recorded to evaluate its performance.

2. __Logistic Regression:__ A linear classifier was implemented using logistic regression. We determined the best theta and cost values to minimize the cost function.

3. __Support Vector Machine (SVM):__ The SVM classifier was employed with varying combinations of cost and gamma values. We used techniques like GridSearchCV and RandomizedSearchCV to identify the most suitable parameters.

## Feature Extraction
__HOG__ (Histogram of Oriented Gradients): We applied the HOG feature extraction method to preprocess the images. These extracted features were then utilized as inputs for the SVM classifier.
## Results
We created a histogram graph to visualize and compare the performance of the different classifiers.
To enhance accuracy, we implemented a Voting Classifier that combines predictions from multiple classifiers.
