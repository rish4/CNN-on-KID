# CNN-on-KID
Convolutional Neural Networks (CNN) for healthy v/s unhealthy classification of WCE images from KID dataset
Dataset:
The dataset used in this experiment is the publicly available KID dataset. It is a diverse dataset containing images from the entire GI tract. The images present are of dimensions 360 X 360 pixels. A total of 857 images belonging to eight classes are present. The dataset was modified to accommodate two classes namely healthy and unhealthy for binary classification of data. 12% of the total images were used to test the model and the remaining images were used for training the model.

Developing a baseline CNN model:

A basic CNN model is developed in four steps :
1.	Convolution
2.	Max Pooling
3.	Flattening 
4.	Full Connection

Next step is model compiling. It has a binary cross entropy loss function, which will show the sum of all individual losses. The optimizer algorithm is adam, which adjusts the learning rate throughout training. The accuracy metrics shows the performance of the model.

The images of the training set are augmented so that the model can learn from more examples.

It took the model around 40 minutes to train and it was run on google colab.

Results:
It can be seen that after 25 epochs the validation accuracy is 0.9287, it shows the ability of the model to generalize to new data.

Visualisation of results:
1.	The first plot shows the dependence of loss and validation loss on the number of epochs during the testing.
2.	The second plot shows the dependence of accuracy and validation accuracy on the number of epochs during the testing.
3.  Confusion Matrix and Classification report can be seen which help in better visualisation of the results. 









