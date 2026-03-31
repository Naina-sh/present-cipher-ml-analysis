# S-Box Classification using ANN and CNN (PRESENT Cipher)

This project explores how machine learning models can identify patterns in ciphertext generated using different S-box configurations of the PRESENT block cipher.

## Objective
To analyze whether neural networks can distinguish between ciphertext generated using different S-boxes, and to study the generalization ability of these models.

## What I Implemented
- Generated ciphertext datasets using multiple S-box configurations
- Built and trained:
  - Artificial Neural Network (ANN)
  - Convolutional Neural Network (CNN)

## Key Experiments
- Trained models on ciphertext generated with a fixed encryption key
- Tested models on ciphertext generated using a different key

## Key Insight
The models achieved good accuracy on known data but failed to generalize when the encryption key changed.  
This indicates that the models were overfitting to key-specific patterns rather than learning true S-box characteristics.

## Tech Stack
- Python
- NumPy
- TensorFlow / Keras
- Google Colab

## Future Work
- Improve generalization using diversified training data
- Explore different architectures and regularization techniques
- Extend analysis to other cryptographic components

## Files
- Notebook containing data generation, model training, and evaluation
