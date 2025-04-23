# Digits Classifier Project

This project uses the **MNIST dataset** to train and evaluate machine learning models that can recognize handwritten digits (0–9). Two models are implemented: **Logistic Regression** and **Multi-Layer Perceptron (MLP)**.

---

##  Dataset Overview

The **MNIST** dataset is a widely used benchmark in machine learning, consisting of grayscale images of handwritten digits.

- **Image Size**: 28 x 28 pixels = 784 features
- **Pixel Values**: 0 (white) to 255 (black)
- **Label**: A digit from 0 to 9
- **Training Set**: 60,000 images (`mnist_train.csv`)
- **Test Set**: 10,000 images (`mnist_test.csv`)

Each row in the CSV files contains:
- 1 label column (`label`)
- 784 columns for pixel values (`1x1` to `28x28`)

**Note**: To use the datasets first extract dataset_zip zip file.

---

##  Objectives

- Load and explore the MNIST dataset
- Preprocess the data using scaling
- Train and evaluate two machine learning models:
  - Logistic Regression
  - Multi-Layer Perceptron (Neural Network)
- Compare their performance using accuracy and classification metrics
- Visualize sample images and label distribution

### Best Model Accuracy 97.7% approx.

---

##  Libraries Used

- `numpy` – for numerical operations
- `pandas` – for data manipulation
- `matplotlib` – for data visualization
- `scikit-learn` – for machine learning models and evaluation

To install the dependencies:

```bash
pip install numpy pandas matplotlib scikit-learn
