# Artificial-Neural-Network
### Download the Dataset from here:-
(https://www.kaggle.com/zalando-research/fashionmnist)

### Description of Data:-

Fashion-MNIST is a dataset of Zalando's article images.
It is a drop-in replacement for the well known MNIST dataset, which contains a lot of handwritten digits.
The Fashion-MNIST Dataset consist of total 70,000 images with training set consisting of 60,000 examples
and test set of 10,000 examples.


Each example is a 28*28 grayscale image, associated with a label from 10 classes.
The First column consist of the class labels, representing the article of clothing and the rest columns consist
of pixel values for specific image in rows.
Each row consist data of a single image.

### Labels:-

Each example in dataset is assigned one of the following Labels

0 T-shirt/top

1 Trouser

2 Pullover

3 Dress

4 Coat

5 Sandal

6 Shirt

7 Sneaker

8 Bag

9 Ankle Boot


### Aim:-
The aim of this project was to build and train an ANN model in tensorflow (keras) to predict the respective classes/labels for the image data and to acquire an efficient accuracy over the test data.


### Tool:- Google Collaboratory


### Dependencies:-

-- tensorflow-gpu==2.0.0.alpha0

-- numpy

-- datetime

-- matplotlib

-- tensorflow.keras

### Procedure:-
The steps followed in the project are as follows:

 - Installing dependencies and setting up GPU environment.
 - Importing required dependencies.
 - Data Preprocessing.
 - Image Normalization.
        This steps will convert pixel in range [0,1].
        By normalising we are making sure that our ANN model runs faster.
 - Reshapping the input in required shape by Neural Network.
         Flatening 60K input into 60k one dimension vectors.
 - Building an Artificial Neural Network.
 -  Layer hyper-parameters:
               - number of units/neurons: 128
               - activation function: ReLU
               - input_shape: (784, )
 -  Dropout is Regularization technique where we randomly set neurons in a layer to zero.
 -  Output Layer:
               - units = number of classes (10)
               - activation = 'softmax'

 - Compiling The Model.
 - Training the model.
 - Model Evaluation and Prediction.
 - Saving The Model.
 - Saving the architecture (topology) of the network.
 - Saving network weights.
 
### Model Evaluation:-
The model was evaluated on metrics such as

  -- Test accuracy score
  
  --Test Loss
