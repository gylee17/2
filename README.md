# Decision-Tree-Classification-on-the-Iris-Dataset

### Overview
This project implements a Decision Tree Classifier on the Iris dataset. It includes hyperparameter tuning via GridSearchCV to enhance model accuracy. The process involves data preprocessing, model training, evaluation, and visualization of results.

### Features
- Data Preprocessing: One-hot encoding, normalization, and summary statistics.
- Model Training: Decision Tree Classifier with GridSearchCV for hyperparameter optimization.
- Model Evaluation: Metrics such as accuracy and confusion matrix.
- Visualization: Decision tree plot, feature importance, and decision boundaries.
  
### Results
The optimized model, with max_depth=5, achieved 100% accuracy on the test set, and key predictors were identified through feature importance analysis.

### Dependencies
- scikit-learn
- numpy
- pandas
- matplotlib
- seaborn
