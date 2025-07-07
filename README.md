🧠 Neural Network Classifier – Letters A, B, and C

📌 Project Overview

This project implements a **2-layer neural network from scratch using only NumPy** to classify simple binary images of the letters **A**, **B**, and **C**.  
The network learns to distinguish between these characters by training on manually crafted 5×6 pixel binary patterns.



🎯 Objectives

- Understand the foundational building blocks of neural networks
- Implement feedforward and backpropagation without using ML libraries (no TensorFlow or PyTorch)
- Work with matrix operations, activation functions, and loss functions
- Visualize the training process using loss curves
- Predict and display binary image inputs using `matplotlib`



🧩 Input Data

Each letter (A, B, C) is represented as a **5x6 binary pixel grid** (30 pixels).  
These are manually encoded as NumPy arrays and reshaped for the model input.

Example (Letter A pattern):

[0, 1, 1, 1, 1, 0,
1, 0, 0, 0, 0, 1,
1, 1, 1, 1, 1, 1,
1, 0, 0, 0, 0, 1,
1, 0, 0, 0, 0, 1]




🛠 Model Architecture

- **Input Layer:** 30 nodes (5×6 pixels)
- **Hidden Layer:** 10 neurons
- **Output Layer:** 3 neurons (for A, B, and C)
- **Activation:** Sigmoid
- **Loss Function:** Cross-Entropy
- **Optimizer:** Custom Gradient Descent



📈 Visualizations

- Training loss vs epochs plot using `matplotlib`
- Input image preview using `imshow()`
- Prediction confidence (softmax-like output)



📂 Files Included

| File Name | Description |
|-----------|-------------|
| `Neural_Network_Letters_ABC.ipynb` | Jupyter notebook with complete code, loss plot, predictions, and visualizations |
| `README.md` | Project overview and documentation |



▶️ How to Run

1. Clone this repository or download the `.ipynb` file
2. Open the notebook in [Jupyter Notebook](https://jupyter.org/) or [Google Colab](https://colab.research.google.com/)
3. Run all cells to:
   - Train the network
   - Visualize the loss
   - Predict the letter from the test image



✅ Output Example

Predicted Class: B
Probabilities: [[0.0012 0.9891 0.0097]]



