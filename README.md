# CNN-Based Image Classification Model

## Overview

This project implements a Convolutional Neural Network (CNN) for image classification using TensorFlow/Keras.

The notebook includes:

- Dataset loading
- Data preprocessing
- Data augmentation (Albumentations)
- Class balancing (SMOTE and RandomOverSampler)
- CNN model construction
- Model training
- Performance evaluation
- Confusion matrix and precision-recall analysis

---

## Features

- TensorFlow/Keras CNN
- Image preprocessing using OpenCV
- Data augmentation with Albumentations
- Handling class imbalance
- Early stopping
- Precision-Recall evaluation
- Confusion Matrix visualization

---

## Project Structure

```
├── myModel.ipynb
├── requirements.txt
├── README.md
├── .gitignore
└── data/               # Not included
```

---

## Installation

```bash
git clone <repository-url>
cd <repository-name>

python -m venv venv

# Windows
venv\Scripts\activate

# Linux/Mac
source venv/bin/activate

pip install -r requirements.txt
```

---

## Usage

Open the notebook:

```bash
jupyter notebook
```

or upload it to Google Colab.

Update the dataset paths before running the notebook.

---

## Dependencies

- TensorFlow
- Keras
- NumPy
- Pandas
- OpenCV
- Albumentations
- imbalanced-learn
- Scikit-learn
- Matplotlib
- Seaborn

---

## Results

The notebook evaluates the model using:

- Accuracy
- Precision-Recall Curve
- Average Precision
- Confusion Matrix

---

## Notes

- The dataset is **not included** in this repository.
- Large trained model files are excluded via `.gitignore`.
- The notebook was originally developed using Google Colab.

## License

MIT License
