# Tweet-Emotion-Recognition

This project focuses on emotion classification of tweets using deep learning. The model is trained to detect the emotional tone behind a tweet — such as joy, anger, sadness, fear, surprise, and love — using a labeled dataset and an LSTM-based neural network architecture.

## Features
- Loads and processes real-world tweet data (`test.csv`)
- Uses TensorFlow's LSTM layers with bidirectional connections
- Performs multi-class emotion classification
- Prints dataset samples and model architecture
- Prepares the data pipeline including tokenization and padding

## Dataset
The dataset `test.csv` contains two columns:
- `text`: the tweet text
- `label`: the emotion label

Ensure this file is present in the same directory or update the `file_path` accordingly.

## Requirements
- Python 3.7+
- TensorFlow 2.x
- Pandas
- NumPy

Install dependencies using:
```bash
pip install tensorflow pandas numpy
