# Fabric CNN Classification

This repository provides a complete pipeline for **fabric image
classification** using **Convolutional Neural Networks (CNNs)**.\
It includes model generation, training routines, evaluation tools,
metric visualization, and prediction scripts.

------------------------------------------------------------------------

## 📂 Project Structure

    cnn-classification-fabric/
    │
    ├── main.py                # Main execution script
    ├── settings.py            # Global configuration (paths, hyperparameters)
    ├── test.py                # Inference script
    │
    ├── data/                  # Expected dataset folder
    │   └── .gitignore
    │
    ├── logs/                  # Training logs
    │   └── .gitignore
    │
    ├── models/
    │   ├── .gitignore
    │   └── modelgenerator.py  # CNN architecture generator
    │
    └── train/
        ├── modeltrain.py      # Training loop
        ├── confusionmatrix.py # Confusion matrix generator
        └── trainingplot.py    # Accuracy/loss plot generator

------------------------------------------------------------------------

## 🚀 Features

-   Build CNN architectures for fabric classification\
-   Train and evaluate models\
-   Automatically generate:
    -   Confusion matrix\
    -   Accuracy/Loss training curves\
    -   Saved model weights\
-   Script for predicting new images\
-   Configurable via `settings.py`

------------------------------------------------------------------------

## 📦 Requirements

    tensorflow
    keras
    numpy
    matplotlib
    scikit-learn
    opencv-python
    pillow

------------------------------------------------------------------------

## 🛠️ Installation Guide

### 1. Clone the Repository

``` bash
git clone https://github.com/your-username/cnn-classification-fabric.git
cd cnn-classification-fabric
```

Or unzip:

``` bash
unzip cnn-classification-fabric.zip
cd cnn-classification-fabric
```

------------------------------------------------------------------------

### 2. Create and Activate a Virtual Environment

**Windows:**

``` bash
python -m venv venv
venv\Scripts\activate
```

**Linux/macOS:**

``` bash
python3 -m venv venv
source venv/bin/activate
```

------------------------------------------------------------------------

### 3. Install Dependencies

``` bash
pip install -r requirements.txt
```

------------------------------------------------------------------------

## 🗂️ Dataset Structure

    data/
    ├── class_A/
    ├── class_B/
    └── class_N/

------------------------------------------------------------------------

## 🏋️ Training

``` bash
python main.py
```

------------------------------------------------------------------------

## 🔍 Inference

``` bash
python test.py
```

------------------------------------------------------------------------

## 📝 License

MIT License
