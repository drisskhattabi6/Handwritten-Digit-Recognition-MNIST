# Handwritten Digit Recognition using MNIST Dataset

This project demonstrates a machine learning model for recognizing handwritten digits using the MNIST dataset. The model is trained using deep learning techniques, achieving good accuracy on classifying digits from 0 to 9.

## Dataset

The MNIST dataset consists of 28x28 pixel grayscale images of handwritten digits. It contains 60,000 training images and 10,000 test images, each corresponding to one of the 10 digit classes.

You can access the MNIST dataset [here](http://yann.lecun.com/exdb/mnist/).

## Model

The model used in this project is a Convolutional Neural Network (CNN), which is particularly effective for image classification tasks.

## Results

The model achieves an accuracy of approximately XX% on the test set. The following are some visualizations of the model's performance:

### Dataset Images

Below are a few samples of the handwritten digits from the MNIST dataset:

![MNIST Sample 1](imgs/img1.png)
![MNIST Sample 2](imgs/img2.png)

### Metrics :
``` 
Accuracy: 0.9892
Classification Report:
              precision    recall  f1-score   support

    0 - zero       0.98      1.00      0.99      1175
     1 - one       0.99      0.99      0.99      1383
     2 - two       0.99      0.99      0.99      1181
   3 - three       0.99      0.99      0.99      1253
    4 - four       0.99      0.99      0.99      1177
    5 - five       0.99      0.99      0.99      1044
     6 - six       1.00      0.99      0.99      1166
   7 - seven       0.99      0.99      0.99      1266
   8 - eight       0.98      0.99      0.98      1152
    9 - nine       0.99      0.97      0.98      1203

    accuracy                           0.99     12000
   macro avg       0.99      0.99      0.99     12000
weighted avg       0.99      0.99      0.99     12000
```
The confusion matrix below shows the performance of the model on the test dataset:

![Confusion Matrix](imgs/img3.png)
