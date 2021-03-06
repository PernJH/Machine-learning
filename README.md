# Machine-learning
Medical Mask Selfie Facial Recognition

# Dependencies
https://www.tensorflow.org/  
https://keras.io/  
https://scikit-learn.org/stable/  



# Installation
Install Jupyter Notebook or open Google Colab to open the code.

# About project
This project is developed for Multimedia University, Faculty of Information Science and 
Technology, subject TML2221 Machine Learning. 
This project is for facial recognition using facial images with medical mask selfie acquired by the smartphone/webcam camera. In this project, our group will develop a medical mask facial recognition system using Machine Learning approach. By using Jupyter and Google Colab, we use python as our programming language to develop the program. Furthermore, with the project assignment requirement, we were told to generate 5 different machine learning algorithm methods. Thus, our decision is Logistic Regression, Multilayer Perceptron, Convolutional Neural Network, Random Forest Classifier and Support Vector Machine. Some of the algorithms require further feature extract, so Principal Component Analysis (PCA) is used as a dimension reduction technique. Our goal is to find the highest accuracy within these 5 algorithms method and decide which is the best.

# How to use the code
Run the code according to the sequence.

# Project Outcome and Conclusion

 Method               /Accuracy  
 Logistic Regression  71.98%  
 MLP                  68.85%  
 CNN                  89.71%  
 SVM                  89.25%  
 RFC                  68.15%  
 
  We have trained 5 different models and obtained convolutional neural networks with 89.71% accuracy that have the highest performing because it is more suitable for image classification. The reason CNN can have such good performance is because it can extract important features from images and perform learning from it. With the learning experience from lectures and online resources, we have discovered many different algorithms and gained new knowledge that help us during the experimental period.
  There are some improvements we can make if we have more time, more group members and more computational resources. First, we would like to put more time on image pre-processing to make images more suitable for training. For example, resize images with different pixels, remove noise and image augmentation such as flipping or rotating the images. Next, with more group members and computational resources means we can have more algorithm trained and more hyperparameter settings on every model. Because not every member's computer is powerful and they cannot handle a large computing process which will shut their computer down.
 
# Further Explanation of CNN Methodology
A complete CNN architecture consists of several layers. The first layer, convolutional layer, we pass an array of rescale/resize images to the conv2D layer with rectified linear unit (ReLU) activation functions that filter the images to produce feature maps. 
Next, the output will pass to the pooling layer to reduce the size of the image and return the maximum pixel value which is the important feature for each of the feature maps. There will be multiple convolutional layers followed by a pooling layer in CNN. The next layer is a fully connected layer, first we will flatten the output of the previous layer and pass to the next fully connected layer to make classification. The last layer will output the classification result with softmax activation.

