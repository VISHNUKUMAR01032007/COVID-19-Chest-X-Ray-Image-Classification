# COVID-19 Image Classification

### Workflow
Load and preprocess COVID and Normal chest X-ray images.
Normalize image pixel values.
Build Convolutional Neural Network (CNN) models.
Train and evaluate two CNN architectures.
Compare models using Accuracy and COVID Recall.
Select the model with better generalization.
Test the final model on unseen X-ray images.

### Technologies
Python
TensorFlow & Keras
NumPy
Pandas
Matplotlib
Scikit-learn
CNN / Deep Learning

### Models
CNN Model 1: 3 Convolution + Pooling layers.
CNN Model 2: 2 Convolution + Pooling layers with a lower learning rate.
Final Model: CNN Model 2.

### Key Results
Validation Accuracy: 97.37%
Test Accuracy: 97.37%
COVID Recall: 94.12%
Model 2 showed better generalization with less overfitting.

### Conclusion
The project successfully classifies chest X-ray images as COVID or Normal using CNN. The 2-layer CNN was selected as the final model because it achieved high accuracy with better generalization and less overfitting.
