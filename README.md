# Assignment 2: Neural Language Model Training (PyTorch)

This repository contains the code for an assignment to train and evaluate several neural language models from scratch using PyTorch. The goal is to analyze how different architectures (RNN, LSTM, GRU, Transformer) and preprocessing techniques (Character, Word, BPE) perform on a text generation task.
**Dataset:** `Pride_and_Prejudice-Jane_Austen.txt`
**Primary Metric:** Perplexity 

---

## Repository Structure

* `experiments/`: This directory contains all the Jupyter/Colab notebooks (`.ipynb`) used for the experiments.
    * `[Ablation_Study.ipynb]`: (Example) This notebook contains the ablation study for the Character-Level LSTM, demonstrating the "Underfit," "Best Fit," and "Overfit" scenarios .
* `Pride_and_Prejudice-Jane_Austen.txt`: The raw dataset used for training.
