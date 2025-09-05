# k-Nearest Neighbors (k-NN) Implementation

This project implements the k-Nearest Neighbors (k-NN) algorithm from scratch using Python. The dataset used is a breast cancer diagnostic dataset, where the goal is to classify tumors as either benign (`B`) or malignant (`M`) based on various features extracted from medical imaging.

## Features
- **Custom k-NN Implementation**: The algorithm is implemented without using external libraries like `scikit-learn` for the k-NN logic.
- **Data Preprocessing**: Includes handling missing values and scaling features for better performance.
- **Visualization**: Scatter plots to visualize the distribution of benign and malignant samples.
- **Accuracy Calculation**: Evaluates the model's performance on a test dataset.

## Dataset
The dataset contains the following columns:
- `id`: Unique identifier for each sample.
- `diagnosis`: Diagnosis result (`B` for benign, `M` for malignant).
- Various features such as `radius_mean`, `texture_mean`, `perimeter_mean`, etc., which describe the characteristics of the tumor.

## Code Structure
1. **Data Loading and Preprocessing**:
   - Load the dataset using `pandas`.
   - Drop unnecessary columns and handle missing values.
   - Split the data into training and testing sets.

2. **k-NN Implementation**:
   - A custom `KNN` class is implemented with methods for fitting the model, predicting new samples, and calculating distances.

3. **Visualization**:
   - Scatter plots to visualize the distribution of benign and malignant samples in the feature space.

4. **Evaluation**:
   - Calculate the accuracy of the model on the test set.

## Example Output
- **Accuracy**: Displays the accuracy of the k-NN model on the test set.
- **Scatter Plot**: Visualizes the predicted benign and malignant samples in the feature space.

