# Tweet Emotion Analysis

This project focuses on **emotion classification of tweets** using deep learning. It trains a model to detect the **emotional tone** behind tweets — such as **joy**, **anger**, **sadness**, **fear**, **surprise**, and **love** — using a labeled dataset and a **Bidirectional LSTM** neural network architecture implemented with **TensorFlow/Keras**.

The dataset provided (`test.csv`) contains pre-labeled tweets, and the model learns to **recognize and classify these emotions** based on the text.

---

## Features

* Loads and processes real-world tweet data from `test.csv`
* Uses TensorFlow’s Bidirectional LSTM layers for sequence learning
* Classifies each tweet into one of six emotional categories
* Prepares the data pipeline including tokenization and padding using TensorFlow
* Displays dataset samples, emotion labels, and model architecture

---

## Dataset

The dataset file `test.csv` includes:

* **`text`**: The tweet text
* **`label`**: The emotion label represented as an integer (0–5)

The label-to-emotion mapping:

```python
{
  0: 'joy',
  1: 'sadness',
  2: 'fear',
  3: 'anger',
  4: 'surprise',
  5: 'love'
}
```

Ensure this file is present in the working directory, or update the file path accordingly.

---

## Requirements

* Python 3.7+
* TensorFlow 2.x
* Pandas
* NumPy

Install the required packages with:

```bash
pip install tensorflow pandas numpy
```

---

## Output

Once trained, the model can predict the emotional category of tweets based on their content. This is useful for:

* Social media sentiment analysis
* Customer emotion tracking
* Mental health monitoring through text

---

