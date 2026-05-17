# part-1-neural-network-analysis

# Objective

This project demonstrates neural network model building, training, evaluation, and hyperparameter experimentation using Python and TensorFlow/Keras.

# Tasks Completed

Dataset Understanding
Data Preprocessing
Neural Network Model Building
Training and Evaluation
Hyperparameter Experimentation
Final Reflection

# Technologies Used

Python
TensorFlow / Keras
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn

# Brief Explanation of All Tasks 

## Task 1: Dataset Understanding
Load the dataset using Pandas.
Check the number of rows and columns.
Identify the type of input features, such as numerical and categorical columns.
Understand the target variable churn.
Check whether the dataset has missing values.
Generate a basic statistical summary using describe().
Check the distribution of the target variable to see how many customers churned and how many did not.

### Purpose:
This task helps us understand the structure and quality of the dataset before building the model.

## Task 2: Data Preprocessing
Remove unnecessary columns such as customer_id.
Separate input features X and target variable y.
Handle missing values, if any.
Encode categorical columns using one-hot encoding.
Scale numerical columns using standard scaling.
Split the dataset into training and testing sets.

### Purpose:
This task prepares the dataset so that it can be used properly by the neural network model.

## Task 3: Building the Neural Network Model
Build a feed-forward neural network using TensorFlow/Keras.
Add an input layer based on the number of processed input features.
Add one or more hidden layers.
Use an activation function such as ReLU in the hidden layers.
Add an output layer with sigmoid activation because the target variable is binary.
Compile the model using:
binary_crossentropy as the loss function
adam as the optimizer
accuracy as the metric

### Purpose:
This task creates the neural network model that will learn patterns from the customer churn dataset.

## Task 4: Training and Evaluation
Train the neural network using the training data.
Evaluate the model on both training and testing data.
Display training accuracy, training loss, testing accuracy, and testing loss.
Make predictions on the test data.
Generate a confusion matrix.
Generate a classification report.
Plot accuracy and loss graphs.
Save evaluation output as an image, if required.

### Purpose:
This task checks how well the model performs on both seen and unseen data.

## Task 5: Hyperparameter Experimentation
Run at least three different model experiments.
Change hyperparameters such as:
Number of hidden layers
Number of neurons
Learning rate
Batch size
Number of epochs
Activation function
Compare the results using accuracy, loss, precision, recall, and F1-score.
Create a comparison table.
Save the table as .csv or .png.

### Purpose:
This task helps identify which model configuration gives better performance.

## Task 6: Final Reflection
Explain the role of weights and biases.
Explain why activation functions are needed.
Discuss what happens when the learning rate is too high or too low.
Explain whether the model shows signs of underfitting or overfitting.

### Purpose:
This task shows understanding of how the neural network works and how well the model performed.
