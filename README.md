# Skip-Gram Mini Project

A simple PyTorch implementation of the Skip-Gram model for learning word embeddings from text.

### Files

- `skipgram_project.ipynb` : Jupyter Notebook containing the full implementation.
- `skipgram_project_report.pdf` : A short report summarizing the model, approach, and results.


### Overview

This mini project implements a basic **Skip-Gram model** using **PyTorch** to learn word embeddings from the **Text8 corpus**.

Key steps include:

- Preprocessing the text and building a vocabulary  
- Creating skip-gram pairs with a window size of 2  
- Training a shallow neural network with **negative sampling**  

The model is evaluated on the **WordSim-353** dataset, showing improved embedding quality as dataset size increases.
