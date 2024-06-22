# Handwriting Rating

This repository contains a project for handwriting recognition utilizing the MNIST dataset with PyTorch. The project explores three different models with varying complexity, evaluates their performance, and makes predictions on a custom dataset.

## Table of Contents
- [Introduction](#introduction)
- [Data Preparation](#data-preparation)
- [Model Definitions](#model-definitions)
    - [Model 1](#model-1)
    - [Model 2](#model-2)
    - [Model 3](#model-3)
- [Custom Dataset](#custom-dataset)
- [Installation](#installation)
- [Usage](#usage)

## Introduction

In this project, we load and transform the MNIST dataset, then define and implement three models of increasing complexity: a simple linear model, a TinyVGG-based model, and a VGG16-based model. I then compare the best model with my own personal handwriting to see which digits are the most legible based on the standards of the MNIST handwritten characters.

## Data Preparation

- The MNIST dataset is loaded and transformed using `torchvision`.
- Data is split into training and testing sets.

## Model Definitions

### Model 1
A simple model with only linear layers.

### Model 2
A more complex model based on the TinyVGG architecture.

### Model 3
The most complex model based on the VGG16 architecture.

## Custom Dataset

- A custom dataset loader is implemented to make predictions on new data.
- The best model is used to make predictions on the custom dataset.
- Results are visualized with confusion matrices and accuracy charts.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/danielshort3/handwriting-rating.git
    cd handwriting-rating
    ```

2. Install the required packages:
   ```bash
   pip install torch torchvision matplotlib tqdm pandas mlxtend
   ```

## Usage
1. Run the notebook: Execute the provided notebook to train models, evaluate them, and make predictions.
2. Make predictions on custom data: Place your custom images in the specified directory and run the prediction cells.


