# ReconstructedPerceptronRefactor
1. Data Loading: Load the penguins dataset.
2. Preprocessing:
  2.1. Drop rows with missing values.
  2.2. Select only numerical columns for simplicity.
  2.3. Select features (X) and target variable (y).
  2.4. Convert the problem into a binary classification task: predicting whether a penguin is of species Adelie or not.
  2.5. Split the dataset into training and testing sets.
  2.6. Standardize the features.
3. Perceptron Implementation:
  3.1. Define a Perceptron class with methods for initializing the model, defining the activation function (step function), updating weights using the perceptron learning rule, training the model, and making predictions.
  3.2. Initialize and train the perceptron model on the training data.
  3.3. Predict classes for the test set.
4. Evaluation:
   Calculate accuracy: Compare the predicted classes with the actual classes and calculate the accuracy of the model on the test set.
