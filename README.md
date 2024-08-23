# Federated Learning for Image Classification

This repository contains a Jupyter Notebook that implements a federated learning model for image classification using a pre-trained ResNet152V2 model. The notebook demonstrates how to prepare a dataset, split it into multiple clients, and train a model across these clients in a federated manner.

## Project Structure

- **Data Preparation:**
  - Loads the dataset and processes it.
  - Splits the dataset into multiple clients for federated learning.

- **Model Architecture:**
  - Uses the pre-trained ResNet152V2 model.
  - Adds custom layers for the classification task.
  
- **Training:**
  - Sets up data generators for training and validation.
  - Trains the model using federated learning techniques.
  - Includes callbacks for early stopping and model checkpointing.

- **Evaluation:**
  - Evaluates the model on a validation set to monitor performance.

## Requirements

To run this notebook, you will need the following Python libraries:

- `tensorflow`
- `keras`
- `numpy`
- `tqdm`

You can install the necessary libraries using pip:

```bash
pip install tensorflow keras numpy tqdm
