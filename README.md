# Soft Computing Practicals

**Jagran Lakecity University — Faculty of Science and Technology**

|Field|Detail|
|-|-|
|Course|Soft Computing (EL1)|
|Course Code|STDA2102|
|Submitted By|Tushar Biley|
|JLU ID|JLU08178|
|Roll No.|2023BTCSE019|
|Assignment|Assignment 2 – Module 2|

\---

## Module 2 — Objectives

1. To understand and implement the basic working of an artificial neuron using Python.
2. To implement the weighted sum of inputs and bias used in an artificial neuron using Python.
3. To implement and visualize Sigmoid, Tanh, and ReLU activation functions using Python.
4. To create a simple single-layer neural network using Python.
5. To create a Multilayer Perceptron (MLP) with input, hidden, and output layers using Keras/TensorFlow.
6. To apply Gradient Descent for updating the weights of a simple neural network during training.
7. To understand and implement the basic concept of Backpropagation for training a neural network.
8. To train a simple neural network model on a dataset using Keras/TensorFlow.
9. To evaluate the performance of a trained neural network using suitable evaluation metrics in Python.
10. To design, train, and evaluate a complete Artificial Neural Network-based classification system using Python and Keras/TensorFlow by integrating input features, hidden layers, activation functions, training, and model evaluation.

## Folder Structure

Each experiment is uploaded in its own numbered folder, as required. Every folder contains
a **Jupyter Notebook (`.ipynb`)** with the code already executed and all outputs
(printed results and plots) embedded:

```
Soft Computing Practicals/
├── Experiment 1 - Artificial Neuron/
│   └── artificial\_neuron.ipynb   (with output)
├── Experiment 2 - Weighted Sum and Bias/
│   └── weighted\_sum.ipynb        (with output)
├── Experiment 3 - Activation Functions/
│   ├── activation\_functions.ipynb (with output + inline plot)
│   └── activation\_functions.png
├── Experiment 4 - Single Layer Neural Network/
│   └── single\_layer\_nn.ipynb     (with output)
├── Experiment 5 - MLP using Keras/
│   └── mlp\_keras.ipynb           (with output)
├── Experiment 6 - Gradient Descent/
│   ├── gradient\_descent.ipynb    (with output + inline plot)
│   └── gradient\_descent\_loss.png
├── Experiment 7 - Backpropagation/
│   └── backpropagation.ipynb     (with output)
├── Experiment 8 - Training NN with Keras/
│   └── train\_model.ipynb         (with output)
├── Experiment 9 - Model Evaluation Metrics/
│   ├── evaluate\_model.ipynb      (with output + inline plots)
│   └── evaluation\_metrics.png
├── Experiment 10 - Complete ANN Classification System/
│   ├── complete\_ann\_system.ipynb (with output + inline plots)
│   └── complete\_ann\_results.png
└── README.md
```

## How to Run

Open any `.ipynb` in Jupyter Notebook / JupyterLab / VS Code / Google Colab to view the
code alongside its already-generated output, or re-run it yourself (`Kernel → Restart \& Run All`).

```bash
pip install numpy matplotlib tensorflow scikit-learn jupyter
jupyter notebook "Experiment 1 - Artificial Neuron/artificial\_neuron.ipynb"
```

Experiments 1, 2, 4, 6, and 7 use only NumPy (implemented from scratch).
Experiments 5, 8, 9, and 10 use Keras/TensorFlow.
Experiments 3, 6, 9, and 10 also produce a saved plot (`.png`) in their own folder, shown inline in the notebook.

## Datasets Used

|Experiment|Dataset|
|-|-|
|5|XOR (synthetic, 4 samples) — demonstrates why a hidden layer is needed|
|8|Breast Cancer Wisconsin (built into scikit-learn) — binary classification|
|9|Breast Cancer Wisconsin — evaluated with Accuracy, Precision, Recall, F1, ROC-AUC, Confusion Matrix|
|10|Wine dataset (built into scikit-learn) — 3-class classification, full end-to-end ANN pipeline|



