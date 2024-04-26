# PyTorch-Fashion-ComputerVision-Toolkit

## Overview

This repository contains code for a computer vision project implemented using PyTorch. The project focuses on classifying fashion images using deep learning techniques.

### Main Project Notebook

The main project notebook `Computer_Vision_Pytorch_Fashion.ipynb` contains the following sections:

- Data preprocessing
- Model training
- Evaluation
- Result analysis

### Helper Functions

The `helper_functions.py` file contains various helper functions used throughout the project, such as:

- Data loading
- Model visualization
- Result analysis

## Requirements
- Python 3.11.5
- PyTorch
- torchvision
- Matplotlib
- NumPy
- requests
- pathlib
- timeit
- tqdm
- Pandas
- torchmetrics
- mlxtend

## Usage

To run the project, follow these steps:

1. Clone the repository:

    ```
    git clone https://github.com/shivam-nath-10003/PyTorch-Fashion-ComputerVision-Toolkit.git
    ```
2. Alternatively, you can explore the analysis and visualization in the Jupyter Notebook:

    ```
    jupyter notebook Computer_Vision_Pytorch_Fashion.ipynb
    
    ```

## Models

1. **Baseline Model (model0)**: A simple feedforward neural network with linear layers.
2. **Non-Linear Model (model1)**: A neural network with both linear and non-linear layers.
3. **Convolutional Neural Network (CNN) Model (model2)**: A CNN model for image classification.

## Training

1. Data loading and preprocessing using PyTorch's DataLoader.
2. Model definition and initialization.
3. Training loop, including forward pass, loss calculation, backward pass, and optimization.
4. Evaluation on the test dataset to assess model performance.

## Evaluation

1. Calculation of accuracy metrics.
2. Visualization of training and testing results.
3. Confusion matrix generation for further analysis.

## Results

Detailed results for each model, including accuracy, loss, and training time, are provided. These results are compared to identify the best-performing model.

## Contributing

Contributions to this project are welcome! Feel free to submit bug reports, feature requests, or pull requests.


