# NC Measure Analysis

This repository provides an analysis of biases in the **Neural Collapse (NC) measure**. The NC measure is a statistical property often observed in deep learning models, related to the alignment of class means and the last layer weights.

## Project Structure

- `notebooks/`: Contains Jupyter Notebooks for exploring and analyzing the NC measure in various datasets and scenarios.
- `requirements.txt`: Lists all required Python dependencies for this project (might be rather strict).

## Features

- **NC Measure Calculation**: Implements various methods for calculating the NC measure, including handling class imbalance.
- **Synthetic Data Generation**: Creates Gaussian-based synthetic datasets for testing the NC measure in controlled environments.
- **Real Dataset Analysis**: Applies the NC measure to popular classification datasets from scikit-learn (e.g., Iris, Digits, Wine).

## References
This implementation and analysis follow the definition and exploration of the neural collapse as discussed in the publication [Prevalence of neural collapse during the terminal phase of deep learning training](https://www.pnas.org/doi/full/10.1073/pnas.2015509117).

