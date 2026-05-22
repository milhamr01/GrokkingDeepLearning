# Grokking Deep Learning — Code Reproduction and Notes

This repository was created as a structured code reproduction and theoretical explanation project based on **Grokking Deep Learning** by **Andrew W. Trask**.

> The book cover is not embedded. A legal/official image can be added manually if required.

---

## Project Description

This repository contains executed Jupyter notebooks for all 16 chapters of the book. The notebooks are written in English and focus on understanding deep learning from scratch using Python and NumPy.

Each notebook includes:

- learning objectives,
- theoretical explanation,
- original/adapted code reproduction,
- output interpretation,
- extended study notes,
- chapter summary,
- key takeaways.

The code intentionally avoids high-level deep learning frameworks so that the internal mechanics of neural networks remain visible.

---

## Book Information

- **Title:** Grokking Deep Learning
- **Author:** Andrew W. Trask
- **Publisher:** Manning Publications
- **Main Tools:** Python, NumPy, Jupyter Notebook
- **Main Topics:** neural prediction, gradient descent, backpropagation, regularization, activation functions, CNNs, embeddings, RNNs, autograd, LSTM, and federated learning.

---

## Repository Structure

```text
.
├── README.md
├── requirements.txt
└── notebooks/
    ├── Chapter_01_Introducing_Deep_Learning.ipynb
    ├── Chapter_02_Fundamental_Concepts.ipynb
    ├── Chapter_03_Forward_Propagation.ipynb
    ├── Chapter_04_Gradient_Descent.ipynb
    ├── Chapter_05_Generalizing_Gradient_Descent.ipynb
    ├── Chapter_06_Backpropagation.ipynb
    ├── Chapter_07_Picturing_Neural_Networks.ipynb
    ├── Chapter_08_Regularization_and_Batching.ipynb
    ├── Chapter_09_Activation_Functions.ipynb
    ├── Chapter_10_Convolutional_Neural_Networks.ipynb
    ├── Chapter_11_NLP_and_Word_Embeddings.ipynb
    ├── Chapter_12_Recurrent_Neural_Networks.ipynb
    ├── Chapter_13_Building_A_Deep_Learning_Framework.ipynb
    ├── Chapter_14_Long_Short_Term_Memory.ipynb
    ├── Chapter_15_Federated_Learning.ipynb
    └── Chapter_16_Where_To_Go_From_Here.ipynb
```

---

## Chapter Overview

1. **Introducing Deep Learning** — motivation, learning approach, and why understanding internals matters.
2. **Fundamental Concepts** — AI, ML, DL, supervised/unsupervised, parametric/nonparametric learning.
3. **Forward Propagation** — weights, dot products, vectors, matrices, and stacked predictions.
4. **Gradient Descent** — prediction error, delta, weight_delta, derivatives, alpha, and divergence.
5. **Generalizing Gradient Descent** — multiple inputs, outputs, and matrix-shaped weight updates.
6. **Backpropagation** — hidden layers, ReLU, deep networks, and long-distance error attribution.
7. **Picturing Neural Networks** — layers as vectors and weights as matrices.
8. **Regularization and Batching** — overfitting, dropout, early stopping, and mini-batches.
9. **Activation Functions** — ReLU, sigmoid, tanh, softmax, and derivative intuition.
10. **Convolutional Neural Networks** — kernels, convolution, local features, and weight reuse.
11. **NLP and Word Embeddings** — word vectors, semantic similarity, and sentence representations.
12. **Recurrent Neural Networks** — variable-length data, hidden state, and sequence modeling.
13. **Building a Deep Learning Framework** — tensors, computation graphs, and autograd.
14. **LSTM** — gates, memory cells, and long-range sequence modeling.
15. **Federated Learning** — decentralized training, federated averaging, and privacy motivation.
16. **Where to Go from Here** — PyTorch, courses, papers, GPUs, blogging, open source, and community.

---

## Installation

```bash
python -m venv venv
```

Windows:

```bash
.\venv\Scripts\activate
```

macOS/Linux:

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## How to Run

```bash
jupyter notebook
```

Open the `notebooks/` folder and run the desired chapter notebook. The submitted notebooks are already executed, so outputs and plots are visible directly.

---

## Dependencies

```text
numpy
pandas
matplotlib
jupyter
nbformat
nbclient
```

---

## Academic Integrity

This repository is prepared as an academic learning project. The explanations are written in original wording, and the code examples are adapted into original runnable demonstrations. The purpose is to support understanding and practical learning, not to replace the original book.

---

## Completion Status

- [x] Chapter 1 through Chapter 16 completed
- [x] All notebooks executed
- [x] README created
- [x] requirements.txt created
