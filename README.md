# Model Complexity Demonstration: Underfitting vs Overfitting

This project provides a visual demonstration of different model complexities in machine learning using polynomial regression. It specifically illustrates the concepts of underfitting, optimal fitting, and overfitting using a synthetic dataset.

## Project Overview

The project demonstrates how different polynomial degrees affect model performance in a regression task. It uses a sine wave with added noise as the underlying pattern to be learned.

### Key Features

- **Synthetic Data Generation**
  - Creates a sine wave pattern with controlled noise
  - Uses 100 data points distributed across range 0-10
  - Implements reproducible randomization (fixed seed)

- **Multiple Model Implementations**
  - Linear Model (Degree 1) - Demonstrates underfitting
  - Polynomial Model (Degree 4) - Shows optimal fitting
  - High-Degree Polynomial (Degree 10) - Illustrates overfitting

- **Visual Analysis**
  - Side-by-side comparison of three model complexities
  - Clear visualization of training and test data points
  - Model predictions shown as continuous curves
  - Mean Squared Error (MSE) metrics for quantitative comparison

### Dependencies

- Python 3.x
- NumPy
- Matplotlib
- Scikit-learn

### Installation

```bash
pip install numpy scikit-learn matplotlib
```

### Usage

Simply run the Jupyter notebook `model.ipynb`. The code will:
1. Generate synthetic data
2. Train three different polynomial regression models
3. Create visualizations comparing their performance

### Key Concepts Demonstrated

1. **Underfitting (High Bias)**
   - Using a linear model (degree 1)
   - Shows inability to capture the underlying pattern
   - Results in high error on both training and test data

2. **Optimal Fitting**
   - Using a polynomial of degree 4
   - Captures the underlying pattern well
   - Balances between bias and variance

3. **Overfitting (High Variance)**
   - Using a polynomial of degree 10
   - Fits training data too closely
   - Poor generalization to test data

### Educational Value

This project serves as an excellent educational tool for understanding:
- Bias-variance tradeoff
- Model complexity and its impact on performance
- The importance of choosing appropriate model complexity
- Visual interpretation of machine learning concepts

## Contributing

Feel free to fork this repository and submit pull requests for improvements.

## License

This project is open-sourced under the MIT License.