# Circle Classification Neural Network

This repository contains a Python script that trains a neural network to classify points in a circular dataset. The neural network is implemented using PyTorch.

## Prerequisites

Before running the script, make sure you have the following dependencies installed:

- Python 3.x
- PyTorch
- scikit-learn
- numpy
- matplotlib

You can install the required dependencies using pip:

```shell
pip install torch scikit-learn numpy matplotlib
```

## Usage
1. Clone the repository:

```shell
git clone https://github.com/hugo-gclvs/DNN
```

2. Change to the repository directory:
```shell
cd DNN
```

3. Run the Python script:
```shell
python main.py
```


Make sure you have the required dependencies installed before running the script. You can install the dependencies using the following command:
```shell
pip install torch scikit-learn numpy matplotlib
```

## Dataset

The script generates a circular dataset using the make_circles function from scikit-learn. It creates a dataset with 1000 samples, adding noise and a specific factor. The dataset is then visualized using matplotlib.

## Neural Network Architecture

The neural network architecture consists of an input layer, a hidden layer, and an output layer. The input layer has 2 nodes, the hidden layer has 32 nodes, and the output layer has 1 node.

The activation function used in the hidden layer is ReLU, and the output layer uses a sigmoid activation function.

## Training

The script trains the neural network using the generated dataset. It uses the Adam optimizer and binary cross-entropy loss for training. The training loop runs for 500 epochs with a batch size of 32.

During training, the loss and accuracy are recorded and displayed using matplotlib.

## Testing

After training, the script generates a small test dataset with 10 samples. It passes the test inputs through the trained neural network and compares the predictions with the ground truth labels. The binary predictions are printed to the console.

Feel free to explore the code and modify it to suit your needs. If you have any questions or feedback, please open an issue or contact the repository owner.

Enjoy experimenting with the circle classification neural network!
