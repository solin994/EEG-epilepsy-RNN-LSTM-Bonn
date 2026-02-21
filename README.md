# EEG-epilepsy-RNN-LSTM-Bonn
PyTorch implementation of RNN and LSTM models for three-class EEG epilepsy classification on the Bonn dataset.
# EEG Epilepsy Classification with RNN and LSTM

This repository contains the implementation used in the paper:

> Masoumeh Bahramian, Javad Mohammadzadeh,  
> "Comparative analysis of recurrent neural networks for three-class EEG-based epilepsy classification" (in Persian).

We implement and compare simple RNN and LSTM models for classifying EEG signals into three classes (Z: healthy, O: interictal, S: ictal) using the Bonn EEG dataset.

## Requirements

- Python 3.8+
- PyTorch
- NumPy
- scikit-learn

(Install via `pip install -r requirements.txt` if provided.)

## How to run

1. Download the Bonn EEG dataset from the official website:  
   https://neurophysicsbonn.de/downloads
2. Update the data path in the code/notebook.
3. Run the training script or notebook.
