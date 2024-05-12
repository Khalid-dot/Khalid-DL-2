Animal Classification using Transfer Learning

This repository contains code and documentation for a deep learning project on animal classification using transfer learning. The project focuses on fine-tuning the MobileNetV2 model pre-trained on the ImageNet dataset to classify images of cats, dogs, and pandas.

Project Overview
- Dataset: The project uses a dataset containing images of cats, dogs, and pandas for training, validation, and testing.
- Model Architecture: Transfer learning is applied using the MobileNetV2 architecture, with the final classification layers retrained for the specific classification task.
- Data Augmentation: Data augmentation techniques are applied to increase the diversity of the training dataset and improve the model's generalization.
- Performance Tuning: The model is evaluated based on metrics such as accuracy, precision, recall, F1 score, and AUC score. Performance tuning techniques are applied to optimize the model's performance.
- Results: The final model achieves an accuracy of 97% on the test data, demonstrating its effectiveness in classifying the three animal classes.

File Structure
- `code/`: Contains the Python code for data preprocessing, model training, and evaluation.
- `documentation/`: Contains the assignment report, including the introduction, problem statement, model architecture, training process, results, and analytical discussion.

Usage
- Environment Setup: Ensure you have the necessary Python libraries installed. Use `requirements.txt` for library versions.
- Training: Run `train.py` to train the model on the dataset.
- Evaluation: Run `evaluate.py` to evaluate the model on the test data and display performance metrics.
- Deployment: Use the trained model for inference in your applications.


