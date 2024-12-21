# Logistic-Regression
Classify emails as spam or not spam using the Spambase dataset, which contains the frequency of occurrence of 57 entities (words and characters) (in %) from 4601 spam and non-spam emails and corresponding class labels

## Tasks

### Task 1: Load the Spambase Dataset 
- Load the Spambase dataset using Pandas.
- Display the first few rows to understand the structure of the data.

### Task 2: Check for Duplicate Entries and Missing Values 
- Check if there are duplicate entries in the dataset.
- Remove any duplicate entries.
- Check for missing values in the dataset.
- Remove entries with missing feature values.

### Task 3: Preprocess the Dataset 
- Preprocess the dataset as required:
  - Perform feature scaling or standardization on the features.

### Task 4: Check Dataset Balance 
- Determine if the dataset is balanced or imbalanced by analyzing the distribution of the target variable.

### Task 5: Split the Data 
- Split the data into training, validation, and test sets with the following proportions:
  - Training set: 70%
  - Validation set: 15%
  - Test set: 15%

### Task 6: Implement Logistic Regression from Scratch 
- Implement a logistic regression model from scratch using:
  - Cross-entropy loss as the cost function.
  - Gradient descent as the learning algorithm.
  - L1 regularization in the cost function.
- Train the logistic regression model using gradient descent.
- Choose appropriate values for the learning rate and regularization parameter through cross-validation.

### Task 7: Evaluate Model Performance 
- Evaluate the performance of your logistic regression model on the test set using:
  - Confusion matrix.
  - Precision.
  - Recall.
  - Area under the Precision-Recall Curve (AUC-PR).

### Task 8: Compare with Scikit-Learn 
- Fit a logistic regression model using scikit-learn.
- Compare the performance of your implementation with the scikit-learn model by evaluating:
  - Confusion matrix.
  - Precision.
  - Recall.
  - Area under the Precision-Recall Curve (AUC-PR).
- Compare the AUC-PR values between your implementation and scikit-learn's implementation.

## Files
- `spambase.zip`: Dataset file containing the Spambase dataset.
- `spambase_classification.py`: Python script containing the implementation for all tasks.
- `README.md`: Project documentation in Markdown format.

## How to Run
1. Clone the repository.
2. Extract the `spambase.zip` dataset into the working directory.
3. Install the required Python libraries: `numpy`, `pandas`, `matplotlib`, `scikit-learn`.
4. Run the `spambase_classification.py` file to execute all tasks.

## Results
- Detailed analysis and plots for each task.
- Comparison between custom implementation and scikit-learn logistic regression, including AUC-PR values.

## License
This project is licensed under the MIT License.
