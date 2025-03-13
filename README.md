# Cat vs Non-Cat Classification

This repository contains a machine learning project for classifying images as "cat" or "non-cat". The project starts with a baseline model using logistic regression (interpreted as a neural network without hidden layers) implemented in PyTorch. In a future update, a neural network with hidden layers will be added to compare performance.

## Project Structure

- **logistic_regression.ipynb** – Notebook with the logistic regression model implementation, training, and evaluation.
- **lr_utils.py** – Utility module for loading and preprocessing the dataset.
- **models/** – Directory where the trained model states are saved.
- **images/** – Folder containing test images.
- **README.md** – This file, with an overview of the project and instructions.

## Requirements

- Python 3.7+
- PyTorch (e.g., 2.6.0+cpu)
- NumPy
- Matplotlib
- Pillow (PIL)

You can install the required dependencies using pip:

```bash
pip install torch torchvision torchaudio numpy matplotlib pillow
