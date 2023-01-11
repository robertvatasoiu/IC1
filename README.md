<b> FLOWERS classification using SVM </b>
<br>
<b> Introduction </b>
<br>
This project aims to classify different types of flowers using Support Vector Machines (SVM) and histogram of oriented gradients (HOG) features. The dataset used for this project contains images of flowers from different classes.
<br>
<b> Features Extraction </b>
<br>
The HOG features were extracted from the images for the classification task. HOG is a feature descriptor used in computer vision and image processing for the purpose of object detection. It computes the gradient orientation histograms of regions of an image.
<br>

<b> Dimensionality Reduction </b>
<br>
To reduce the dimensionality of the feature space, Principal Component Analysis (PCA) was applied. PCA is a linear dimensionality reduction technique that helps in identifying patterns in data. It projects the original data onto a new subspace with the directions that maximize the variance of the data.
<br>

<b>Classification</b>
<br>
The features extracted from the images were used to train an SVM classifier. SVM is a powerful and widely used algorithm for classification tasks. The goal of SVM is to find the hyperplane that maximizes the margin between the different classes in the dataset.
</br>
<b>Requirements </b>
<br>
Python 3.x
Numpy
Pandas
OpenCV
Scikit-learn

<b>Usage</b>
<br>
The project can be run by executing the IC1v2.ipynb file. The dataset was downloades from kaggle.
</br>


<b> Results </b>
<br>
The classification model had an accuracy of 56.01% on the test set. The results can be further improved by using more advanced techniques such as deep learning.
</br>
<b> Conclusion </b>
<br>
In this project, I've used SVM and HOG features along with PCA for dimensionality reduction to classify different types of flowers in the dataset. With careful feature engineering and model selection, the model can be improved to achieve better accuracy.
<br>

