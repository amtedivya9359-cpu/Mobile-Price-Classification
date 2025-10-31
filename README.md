# Mobile-Price-Classification
## Train Module
The train module is responsible for building a predictive model using labeled data. It learns patterns and relationships between input features and target outputs.

> Key Functions:

- Data preprocessing: Cleans and transforms raw data (e.g., normalization, encoding).

- Model selection: Chooses an algorithm (e.g., linear regression, decision tree, neural network).

- Training: Fits the model to the training dataset by optimizing parameters.

- Evaluation (optional): Assesses performance using metrics like accuracy or loss on a validation set.

- Model saving: Stores the trained model for future use.


## Test Module
The test module evaluates the trained model’s performance on unseen data to measure generalization.

> Key Functions:

- Load model: Retrieves the trained model.

- Data preprocessing: Applies the same transformations used during training.

- Prediction: Uses the model to predict outcomes for test data.

- Performance metrics: Calculates accuracy, precision, recall, F1-score, etc.
