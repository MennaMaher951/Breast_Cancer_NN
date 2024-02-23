## Breast Cancer Classification_NN

* This code implements a neural network to classify breast cancer tumors as malignant or benign, based on a dataset of 569 patient records.

*Dependencies:*

1. numpy
2. pandas
3. matplotlib.pyplot
4. sklearn
5. tensorflow

*Instructions:*

* Clone this repository.
* Install the required dependencies using pip install -r requirements.txt.
* Run the Python script Breast_Cancer_Classification.py.

*The code performs the following steps:*

1. Loads the breast cancer dataset: The dataset is loaded from the sklearn library.
2. Preprocesses the data: The data is preprocessed by scaling the features and separating them from the target labels.
3. Splits the data into training and testing sets: The data is split into 80% for training and 20% for testing.
4. Builds a neural network: The neural network consists of three layers:
5. An input layer with 30 neurons, one for each feature.
6. A hidden layer with 20 neurons and a ReLU activation function.
7. An output layer with 2 neurons and a sigmoid activation function, corresponding to the two possible classes (malignant and benign).
8. Trains the neural network: The network is trained on the training data for 10 epochs using the Adam optimizer and the sparse categorical cross-entropy loss function.
9. Evaluates the neural network: The network is evaluated on the testing data and its accuracy is printed.
10. Makes predictions: The user can input a new data point and the network will predict the probability of it being malignant or benign.

*Accuracy:*

* The accuracy of the model on the testing data is approximately 96%.

*Confusion matrix:*

* A confusion matrix is generated to show the performance of the model on each class.

*Predictive system:*

* A simple predictive system is implemented that allows you to input a new data point and get the predicted class label.
