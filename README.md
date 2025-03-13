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
```

How to Run
Logistic Regression Model
Training:

Run the logistic_regression.ipynb notebook to train the logistic regression model.
The notebook will train the model, display a learning curve, and print train/test accuracy.
The trained model is saved (e.g., as model_lr_0.005.pt) in the models/ directory.
Prediction on a Custom Image:

Place your test image in the images/ folder.
Update the image path in the notebook cell that performs the prediction.
The code will load the saved model, process your image, and output whether the image is classified as "cat" or "non-cat".
Upcoming: Neural Network with Hidden Layers
In the next phase, an extended model with one or more hidden layers will be implemented.
This will allow you to compare the performance of the logistic regression model with a deeper neural network.
Results, learning curves, and accuracy comparisons will be documented in the updated notebook.
Results (Baseline - Logistic Regression)
Train Accuracy: Approximately 99%
Test Accuracy: Approximately 70%
These metrics serve as the baseline performance. Future improvements with a deeper network architecture will aim to improve these results.

Experimentation
The project includes code for experimenting with different learning rates and visualizing their impact on the training cost over iterations. You can modify the learning rates and other hyperparameters to see how the model's performance changes.

Contributing
Contributions, improvements, and suggestions are welcome. Please feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License.
