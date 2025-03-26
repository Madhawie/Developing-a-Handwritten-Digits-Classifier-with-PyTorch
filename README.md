# Handwritten Digits Classifier with PyTorch

This project focuses on building a machine learning model that can recognize and classify handwritten digits (0-9) using the MNIST dataset. The model is implemented using **PyTorch**, a deep learning framework.

## Project Structure

- `data/`: Contains the MNIST dataset images and labels.
- `model.py`: Defines the neural network architecture using PyTorch.
- `train.py`: Handles the training of the model, including loading the dataset, setting up the loss function and optimizer, and running the training loop.
- `test.py`: Evaluates the model's performance on the test set after training.
- `requirements.txt`: Contains the necessary Python dependencies to run the project.
- `.gitignore`: A file to ignore unnecessary files such as model checkpoints and temporary files.

## Requirements

- Python 3.x
- PyTorch
- torchvision
- matplotlib
- numpy

To install the required dependencies, run:

```bash
pip install -r requirements.txt
