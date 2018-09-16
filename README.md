# Reduced-InceptionV3-model.
Deep Neural Network inspired from InceptionV3 model for MNIST dataset.

This Notebook is written as a part of digit-recognizer kaggle competition (https://www.kaggle.com/c/digit-recognizer/). You can view the Notebook in Kaggle at https://www.kaggle.com/harshaneigapula/dnn-inspired-from-inceptionv3-model/ 

Data is available in Data.zip file. Unzip the files and place it in a folder. Make sure the folder path is correct in the Notebook. 

# Introduction to the Notebook: 

This is a deep neural network model inspired InceptionV3 model. InceptionV3 model is sequential deep convolution neural network model trained for the ImageNet Large Visual Recognition Challenge which achived a top-5 error rate of 3.46%. I modified the original inception V3 model to reduce the complexicity and removed few layers which bought down the number of parameters to train. 

I used another MNIST 60K dataset http://yann.lecun.com/exdb/mnist/) and removed the test dataset enteries which are in the train dataset of MNIST. Overall I trained the model with around 77K images. 

I also used data agumentation to create more data using the existing dataset of 77K which involves in the operations like Rotation, Zooming, width shifting and height shiffting.  

Overall I achieved 99% when I trained with combination of all the datasets. I hope the accuracy is good enough for the model and beyond it may consider as overfit model. 

# Model

Intial Inception V3 Model: 

![Original](https://github.com/harshaneigapula/Reduced-InceptionV3-model/blob/master/Original.png?raw=true)

Modifed  Model: 

To decrease the complexcity of the model, removed few loops in the model. Which results as below:  

![After](https://github.com/harshaneigapula/Reduced-InceptionV3-model/blob/master/After.jpg?raw=true)

