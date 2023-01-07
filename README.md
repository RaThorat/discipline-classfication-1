# discipline-classfication-1
This is the code to be run in Google Colab

The code imports the necessary modules, including ktrain and TensorFlow, and reads in training and testing data from Excel sheets. The data is cleaned by dropping any rows with null values in the 'summary' column. The ktrain library is then used to build a model using the BERT NLP model and train it on the training data. The optimal learning rate is found and the model is trained for one epoch with this learning rate. The trained model is then used to create a predictor object, which can be used to classify the discipline of a grant application based on its summary. The predictor is saved to a specified folder for later use.
