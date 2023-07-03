# Machine Learning, Deep Learning and Neural Networks

This is a repository which contains programs related to Neural Networks implementation and Deep Learning Models. Programming language used is Python.

* # CNN Model On Cats and Dogs Dataset
  <br>This is a model to classify input images as either cats or dogs. The model is trained on 2000 images of cats and dogs each.<br>
  <p>      In this model I learnt how to read images from dataset using opencv,convert the images to array format and resize them for the model. I also implemented the necessary hidden layers for CNN model i.e Convolutional Layer, Pooling Layer and Fully-Connnected Layer. After some hyperparameter tuning the maximum accuracy obtained is 92.37%</p>

* # Deep Learning Model On MNIST Dataset
  <br>This is a model to classify hand written digits (0-9).The dataset used is MNIST dataset. Shape of dataset is (42000,785).
  <br>
  <p>In this model, I learnt how to create input layers,hiiden layers and output layers for a neural network. I also learnt about the concept of normalization of data.
  To overcome overfiiting of model on dataset I used the dropout method . Dropout removes a certain number of neurons after each iteration from the hidden layers.
  The maximum accuracy obtained is 96.38%</p>

* # LSTM Model for Spam Detection
  <br>This is a model to detect spam messages using Long Short Term Memory (LSTM) alogrithm. Shape of the dataset is (6776, 5).
  <br>
  <p>In this model, I learnt how word embeddings are used in Natural Language Processing. I also learnt the concept of tokenization and sequencing. Thus, overall this project provided me with an insight about NLP. After hyperparameter tuning, the maximum accuracy is 99.63%</p>


* # Logistic Regression Model for Rain Prediction
  <br>This is a model to predict whether rain will occur tomorrow or not. The machine learning algorithm used is logistic regression as the target variable is discrete. The dataset is obtained from kaggle titled 'Rain Dataset for Australia'. The shape of the dataset is (145460, 23).<br>
  <p>In this model, I learnt how the logistic regression algorithm works and how to implement it. While using this algorithm, I got to know about concepts like Imputing, Scaling of dataset and how to apply them. The dataset also had 'NaN' values and I was able to handle these missing values using various approaches. the final accuracy of the model is 84.61%</p>
