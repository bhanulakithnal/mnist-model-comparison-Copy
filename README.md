# mnist-model-comparison-Copy
A machine-learning project comparing classification and clustering methods on the MNIST handwritten-digit dataset.

# MNIST Machine Learning Model Comparison

## Project Overview

This project explored machine learning methods for handwritten-digit recognition using the MNIST dataset. We compared different classification algorithms and clustering methods to study their performance on image data.

The project was completed as part of an undergraduate engineering mini-project.

## Models Evaluated

### Classification

| Model | Recorded Result |
|---|---:|
| Logistic Regression | Accuracy: 92.68% |
| k-Nearest Neighbors (k-NN) | Accuracy: 97.05% |
| Support Vector Machine (SVM) | Accuracy: 96.96% |
| Convolutional Neural Network (CNN) | Validation accuracy: 98.83% |

The SVM result was obtained using 10,000 training examples. The k-NN prediction stage took approximately 41.75 seconds in our recorded setup.

### Clustering

| Method | Adjusted Rand Index (ARI) | Normalized Mutual Information (NMI) |
|---|---:|---:|
| K-Means | 0.3704 | 0.4883 |
| Gaussian Mixture Model (GMM) | 0.1392 | 0.3906 |
| Ward Hierarchical Clustering | 0.4232 | 0.6233 |

Ward Hierarchical Clustering achieved the highest NMI among the clustering methods evaluated.

## Key Learning Areas

- Comparing machine learning algorithms.
- Understanding classification and unsupervised clustering.
- Evaluating model performance using appropriate metrics.
- Working collaboratively on a technical project.
- Analysing results and comparing the strengths and limitations of different approaches.

## Project Status

Completed.

## Notes

The results above are the recorded results from our implementations. The models used different evaluation setups, so these figures should not be interpreted as a perfectly controlled comparison.

Additional documentation, implementation details and project evidence may be added after reviewing the files and confirming what can be shared publicly.
