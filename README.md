# Machine Learning Model Comparison Project

This project implements and compares different regression models (ElasticNet and Random Forests) on a dataset, including data exploration, model training, and performance evaluation.

## Project Structure

The project consists of three main parts:

### 1. Data Exploration
- Analysis of training and test data dimensions and variable types
- Data completeness check and necessary type conversions
- Analysis of target variable distribution (including basic statistics and visualization)
- Correlation analysis of the 250 features most correlated with the target variable
- Heat map visualization of feature correlations

### 2. ElasticNet Model
- Implementation of ElasticNet regression (including Ridge and Lasso as special cases)
- Theoretical background on ElasticNet model:
  - Parameter estimation
  - Optimization function
  - Hyperparameters and their impact
- Grid search for hyperparameter optimization
- Cross-validation for model selection
- Evaluation of training and validation errors

### 3. Random Forests Model
- Implementation of Random Forests regression
- Hyperparameter optimization using grid search on three selected parameters
- Cross-validation using the same data splits as ElasticNet
- Comprehensive comparison with the ElasticNet model
- Comparison against a baseline model (mean prediction)

## Requirements

- Python 3.x
- Required libraries:
  - numpy
  - pandas
  - scikit-learn
  - matplotlib
  - seaborn

## Model Evaluation

The models will be evaluated using:
- Cross-validation scores
- Training error
- Validation error
- Comparison with baseline model (mean prediction)

## Project Goals

1. Implement and compare two different regression approaches:
   - ElasticNet (including Ridge and Lasso as special cases)
   - Random Forests
2. Perform thorough exploratory data analysis
3. Conduct proper model selection and validation
4. Compare model performances using consistent evaluation methods

## Implementation Details

### Data Exploration
- Complete analysis of data structure and quality
- Visualization of target variable distribution
- Correlation analysis with heat map visualization

### ElasticNet Implementation
- Grid search over multiple hyperparameter values
- Special attention to Ridge and Lasso configurations
- Cross-validation for model selection

### Random Forests Implementation
- Three-dimensional grid search for hyperparameter optimization
- Consistent cross-validation splits with ElasticNet
- Comprehensive performance comparison

## Expected Outputs

1. Data exploration visualizations and statistics
2. Model performance metrics
3. Comparative analysis of both models
4. Final model selection with justification

## Note

The project emphasizes thorough model evaluation and comparison, using consistent cross-validation splits across different models to ensure fair comparison.
