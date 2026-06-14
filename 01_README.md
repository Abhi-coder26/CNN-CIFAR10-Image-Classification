# CNN-CIFAR10-Image-Classification
CNN-based image classification on CIFAR-10 using TensorFlow and Keras with comprehensive performance evaluation.

## Project Overview

This project implements a Convolutional Neural Network (CNN) for image classification on the Canadian Institute For Advanced Research (CIFAR-10) dataset using TensorFlow and Keras.

The model was trained and evaluated on the CIFAR-10 benchmark dataset containing 60,000 RGB images belonging to 10 different object categories. Performance was assessed using accuracy, precision, recall, F1-score, confusion matrix analysis, and external image testing.

---

## Dataset Information

- Dataset: CIFAR-10
- Total Images: 60,000
- Training Images: 50,000
- Test Images: 10,000
- Classes: 10
  - Airplane
  - Automobile
  - Bird
  - Cat
  - Deer
  - Dog
  - Frog
  - Horse
  - Ship
  - Truck

Image Size: 32 × 32 RGB

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-Learn

---

## Model Performance

| Metric | Value |
|----------|----------|
| Training Accuracy | 92.06% |
| Validation Accuracy | 91.28% |
| Test Accuracy | 90.25% |
| Test Loss | 0.4396 |
| Precision | 0.9027 |
| Recall | 0.9025 |
| F1-Score | 0.9015 |
| Model Size | 13.68 MB |
| Inference Time | 0.7913 ms/image |

---

## Learning Curves

The training and validation loss steadily decreased while accuracy improved throughout training, demonstrating good convergence and generalization performance.

---

## External Image Testing

The trained model was tested on external images collected outside the CIFAR-10 dataset.

| Metric | Value |
|----------|----------|
| Total Images Tested | 10 |
| Correct Predictions | 6 |
| Incorrect Predictions | 4 |
| External Accuracy | 60.00% |

### Sample Results

| Actual Class | Predicted Class |
|-------------|----------------|
| Airplane | Airplane |
| Bird | Bird |
| Dog | Dog |
| Frog | Frog |
| Horse | Horse |
| Truck | Truck |
| Automobile | Truck |
| Deer | Bird |
| Cat | Frog |
| Ship | Bird |

---

## Confusion Matrix Analysis

The confusion matrix indicates strong classification performance across most classes. Misclassifications primarily occurred between visually similar categories such as:

- Automobile and Truck
- Deer and Bird
- Cat and Frog
- Ship and Bird

---

## Repository Contents

```text
01_README.md
CIFAR10_Project_Report.pdf
CNN_CIFAR10_Project.ipynb
```

---

## Results Summary

This CNN model achieved:

✅ 90.25% Test Accuracy

✅ 0.9027 Precision

✅ 0.9025 Recall

✅ 0.9015 F1-Score

✅ Successful external image testing

The project demonstrates the effectiveness of Convolutional Neural Networks for multi-class image classification on the CIFAR-10 benchmark dataset.

---

## Author

Abhishek Chaurasiya

Research Internship Project – Computer Vision and Deep Learning
