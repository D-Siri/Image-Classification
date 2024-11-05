# Image Classification

## Project Overview

This project implements and compares various deep learning models for image classification using a dataset of 30,000 images (64x64 pixels, RGB) categorized into dogs, food, and vehicles.

## Contents

1. Data Loading and Preprocessing
2. Model Implementation
   - VGG13 Base Model
   - ResNet Model
3. Regularization Techniques
   - L1 and L2 regularization
   - Dropout
   - Early stopping
4. Data Augmentation
5. Model Training and Evaluation
6. Results Visualization

## Requirements
- Python 3.x
- PyTorch
- torchvision
- numpy
- matplotlib
- pandas
- seaborn
- scikit-learn

## Usage

1. Ensure all required libraries are installed.
2. Run the Jupyter notebook.
3. Follow the code cells sequentially to reproduce the analysis and results.

## Key Features

- Implementation of VGG13 and ResNet architectures using pytorch
- Application of various regularization techniques
- Data augmentation for improved model generalization
- Comprehensive model evaluation and performance visualization

## Results

- VGG13 Base Model Test Accuracy: 90.77%
- Significant performance improvements observed with regularization techniques


## License
MIT License

Copyright (c) [2024] [Siri Duggineni]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
