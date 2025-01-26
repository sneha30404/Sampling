# README: Sampling Techniques and Accuracy Score Evaluation

## Overview
This repository demonstrates the use of various sampling techniques to evaluate the accuracy of multiple machine learning models. The dataset used is sourced from the Credit Card Fraud Detection dataset, and the evaluation focuses on understanding how different sampling methods impact model performance.

### Features
- **Sampling Techniques:**
  - Simple Random Sampling
  - Stratified Sampling
  - Systematic Sampling
  - Cluster Sampling
  - Reservoir Sampling

- **Machine Learning Models:**
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
  - K-Nearest Neighbors
  - Naive Bayes

- **Evaluation Metric:**
  - Accuracy Score

## Dataset
The dataset used for this project is hosted on GitHub.

## Requirements
The project requires the following libraries:
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- imbalanced-learn

To install the necessary dependencies, run:
```bash
pip install pandas numpy seaborn matplotlib scikit-learn imbalanced-learn
```

## Usage
1. Clone the repository or download the code.
2. Run the script to perform sampling, train models, and evaluate accuracy scores.
3. The script generates:
   - A CSV file (`sampling_results_accuracy.csv`) containing accuracy scores for all models and sampling methods.
   - A heatmap visualization of accuracy scores.

## Sampling Techniques
1. **Simple Random Sampling:** Randomly selects rows from the dataset.
2. **Stratified Sampling:** Ensures the class distribution in the sample matches the original dataset.
3. **Systematic Sampling:** Selects every nth row from the dataset.
4. **Cluster Sampling:** Randomly selects a subset of clusters (groups) from the dataset.
5. **Reservoir Sampling:** Randomly selects a fixed number of rows from the dataset.

## Results Visualization
The heatmap below shows the accuracy scores of different models across sampling techniques:

**Heatmap Example:**
![image](https://github.com/user-attachments/assets/2331db44-f1cd-4001-871e-d76bd6fb8cef)



> **Note:** The heatmap highlights the comparative performance of models under various sampling strategies.

## Output
- `sampling_results_accuracy.csv`: Tabular data of accuracy scores.
- Heatmap visualization: Provides an easy-to-read comparison of model performance.

## Acknowledgments
- **Dataset Source:** Credit Card Fraud Detection dataset.
- **Sampling and Modeling Concepts:** Inspired by the "Sampling Assignment" on GitHub.

## Contact
For queries or contributions, contact:
- **Email:** sneha30404@gmail.com
- **LinkedIn:** [LinkedIn Profile](https://linkedin.com/in/sneha-2b3271258)
- **GitHub:** [GitHub Profile](https://github.com/sneha30404)
