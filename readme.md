# DL_Assignment3: Transliteration using Sequence-to-Sequence Models (Vanilla and Attention)

This repository presents the implementation and analysis for Assignment 3 of the S6910 Deep Learning course. The objective is to transliterate words from Latin script into Tamil script using sequence-to-sequence (seq2seq) models. We implement two model variants: a vanilla seq2seq model and a seq2seq model with attention mechanism. The assignment includes preprocessing, training, hyperparameter tuning, evaluation, and interactive attention visualizations.

## Index

- `DL_Ass3.ipynb`: Google Colab notebook containing the code for the entire assignment including training, evaluation, visualizations, and all question responses.
- `predictions_vanilla/`: Folder containing `predictions_vanilla.csv`, which holds the top-K predictions for each input in the test set using the best **vanilla model** (no attention).
- `predictions_attention/`: Folder containing `predictions_attention.csv`, which holds the top-K predictions for each input in the test set using the best **attention-based model**.
- `requirements.txt`: Contains all Python dependencies required for running the notebook locally on a CPU setup.
- `README.md`: This file.

## Report and Runs

- WANDB Report: Link to final analysis and plots https://wandb.ai/subikksha-indian-institute-of-technology-madras/DA6401_DL_ASSIGNMENT_03/reports/DA24D004-Subikksha-Assignment-3--VmlldzoxMjg2MDcyMw

## Requirements

To run the notebook locally on CPU (Python 3.7 or lower):

