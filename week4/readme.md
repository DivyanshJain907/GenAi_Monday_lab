# Text Generation using LSTM and Transformer

## Overview

This project implements simple text generation models using two approaches:

1. **LSTM (Recurrent Neural Network)**
2. **Transformer-based model**

The models are trained on a small custom text corpus and generate new meaningful text based on a seed input.

---

## Objectives

* Understand basics of text generation
* Preprocess textual data
* Implement sequence-based neural networks
* Generate new text samples
* Compare LSTM and Transformer performance

---

## Dataset

A small sample dataset based on Artificial Intelligence, NLP, education, and ethics was used for training.

---

## Implementation Steps

### Component I – LSTM

* Tokenization of text
* Creation of input-output sequences
* LSTM model with embedding layer
* Training using categorical cross entropy
* Text generation using seed input

### Component II – Transformer

* Word-level tokenization
* Positional encoding
* Multi-head attention block
* Transformer training
* Text generation

---

## Requirements

* Python
* TensorFlow
* NumPy
* Google Colab (recommended)

---

## How to Run

1. Open Google Colab
2. Paste the provided code cells
3. Run all cells sequentially
4. Use the generate function to create text

---

## Output

* Generated text samples from LSTM
* Generated text samples from Transformer
* Comparison of both approaches

---

## Conclusion

* LSTM works well for small sequences but struggles with long context
* Transformer gives better and more coherent results
* Text generation quality depends on dataset size

---

## Author

Lab Work – Introduction to Generative AI
