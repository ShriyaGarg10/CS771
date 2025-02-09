# CS771- Introduction to Machine Learning

# Project 1: Binary Classification Project
**Description:** This project involves training binary classification models on three distinct datasets derived from the same raw data but represented with different features. The goal is to identify the best-performing model for each dataset and explore if combining the datasets improves model performance.

**Tasks:**
1. Pre-process the datasets to ensure clean and usable data for training models.
2. Train models on each dataset and evaluate their performance.
3. Combine the datasets and assess the performance of a new model.

**Datasets:**
- **Emoticons as Features Dataset**: CSV file with 13 emoticon features.
- **DeepFeatures Dataset**: .npz file with 13 x 786-dimensional embeddings.
- **Text Sequence Dataset**: CSV file with length 50 string features.



# Project 2: Binary Classification with CIFAR-10 Subsets

**Problem:** You are provided with 20 training datasets \( D1, D2, \ldots, D20 \), each a subset of the CIFAR-10 image classification dataset. The first 10 datasets (\( D1, D2, \ldots, D10 \)) have inputs from the same distribution, while the remaining 10 datasets (\( D11, D12, \ldots, D20 \)) have inputs from different distributions. The first dataset \( D1 \) is labeled, and the remaining 19 datasets are unlabeled. Twenty held-out labeled datasets are provided to assess the performance of the models.

**Tasks:**
1. Train a model using \( D1 \) and iteratively update it using the predictions for subsequent datasets \( D2 \) to \( D10 \). Apply each model to held-out datasets and report accuracies in a matrix form.
2. Starting with the final model from Task 1, repeat the procedure using datasets \( D11 \) to \( D20 \). Apply each model to held-out datasets and report accuracies, ensuring performance does not degrade significantly.



