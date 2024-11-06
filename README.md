# BankNote-Auth-ANN
This project involves building and training an Artificial Neural Network (ANN) to classify banknotes as genuine or counterfeit based on extracted image features. It serves as a machine learning exercise in the Banking and Finance domain, with an emphasis on data integrity and model performance evaluation.

## Project Overview
- **Domain**: Banking and Finance
- **Objective**: Develop a reliable ANN model to classify banknotes, ensuring robust performance on unseen data.
- **Dataset**: Banknote Authentication Dataset (features include variance, skewness, kurtosis, and entropy)

## Key Steps
1. **Data Handling**
   - Imported dataset and performed initial exploration and statistics.
   - Preprocessed data, addressing missing values and standardizing features for optimal model training.

2. **Model Architecture**
   - Designed an ANN using a sequential model with dense layers.
   - Configured activation functions (ReLU, Sigmoid) and optimized using the Adam optimizer.

3. **Training & Evaluation**
   - Trained the model across 10 epochs with validation checks.
   - Achieved high test accuracy (96%), with accuracy and loss monitored over epochs.
   - Visualized training and validation performance trends using Matplotlib.

4. **Insights & Conclusions**
   - The model demonstrates effective learning and generalization, achieving strong test accuracy.
   - Suggestions for improvement include potential architectural refinements or additional data features.

## Results
- **Test Accuracy**: 96%
- **Training Dynamics**: High accuracy and low loss achieved, with convergence on validation metrics.

---
