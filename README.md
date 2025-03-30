# Symptom Recommendation using Item-Based Collaborative Filtering

## Overview
This project implements an Item-Based Collaborative Filtering (IBCF) model for symptom recommendation. It utilizes Singular Value Decomposition (SVD) for making predictions based on user-reported symptoms.

## Dataset Structure
The dataset contains the following key columns:
- `no_symptoms_`: Symptoms the user does not have.
- `idk_symptoms_`: Symptoms the user is unsure about.
- `yes_symptoms_`: Symptoms the user reports having.

## Requirements
Ensure you have the following dependencies installed before running the notebook:

```bash
pip install pandas numpy scikit-learn
```

## Usage
1. Open `recommend.ipynb` in Jupyter Notebook.
2. Execute the cells sequentially to:
   - Load and preprocess the dataset.
   - Train the SVD model.
   - Generate symptom recommendations.

## Notes
- The model is trained separately, so ensure you have preprocessed data before running inference.
- The notebook contains data exploration steps to understand the dataset.

## Future Improvements
- Enhance model performance with hyperparameter tuning.
- Implement a user interface for easier interaction.
- Expand dataset for better generalization.

