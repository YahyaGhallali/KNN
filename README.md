# K-Nearest Neighbors (KNN) Classifier

This project demonstrates the implementation of a K-Nearest Neighbors (KNN) classifier using Python and popular machine learning libraries.

## Main Notebook

The main implementation can be found in the [Main.ipynb](./Main.ipynb) file.

### Summary of `Main.ipynb`

1. **Data Generation**: Synthetic data is generated using `make_classification` with 4 classes and 2 features.
2. **Data Visualization**: The dataset is visualized using scatter plots to show class distributions.
3. **Data Splitting**: The dataset is split into training and testing sets using `train_test_split`.
4. **Model Training**: A KNN classifier is trained with default parameters (`n_neighbors=5`).
5. **Evaluation**:
   - Predictions are made on the test set.
   - The performance is evaluated using a classification report and a confusion matrix.
6. **Hyperparameter Tuning**:
   - A grid search is performed to find the optimal number of neighbors (`n_neighbors`).
   - The model is retrained with the best parameters and re-evaluated.
