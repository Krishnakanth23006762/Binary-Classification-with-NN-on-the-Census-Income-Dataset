# Binary-Classification-with-NN-on-the-Census-Income-Dataset
# AIM:
To build, train, and evaluate a deep learning model using PyTorch for tabular data that contains both categorical and continuous features, in order to classify income labels.
## PROCEDURE:

## STEP 1:
Load the Census Income dataset (income.csv) into a Pandas DataFrame.

## STEP 2:
Separate categorical features, continuous features, and the target label.

## STEP 3:
Convert categorical features into embeddings and normalize continuous features.

## STEP 4:
Split the dataset into training (25,000 samples) and testing (5,000 samples) sets.

## STEP 5:
Define the TabularModel class with one hidden layer of 50 neurons and dropout (p=0.4).

## STEP 6:
Set the loss function (CrossEntropyLoss) and optimizer (Adam with lr=0.001).

## STEP 7:
Train the model for 300 epochs using the training data.

## STEP 8:
Evaluate the model on the test data and calculate accuracy.

## STEP 9:
Display the test accuracy, loss, confusion matrix, and classification report.

## STEP 10 (Optional):
Implement a prediction function that accepts new user data and outputs the predicted income class (≤50K or >50K).

# RESULT
A neural network classification model was successfully built and trained using the Census Income dataset. The model achieved good accuracy on the test data and was able to correctly classify individuals earning ≤50K and >50K. A prediction function was also implemented to test new user inputs.
A neural network classification model was successfully built and trained using the Census Income dataset. The model achieved good accuracy on the test data and was able to correctly classify individuals earning ≤50K and >50K. A prediction function was also implemented to test new user inputs.
