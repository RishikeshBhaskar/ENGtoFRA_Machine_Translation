## Overview
This project implements a **Neural Machine Translation (NMT)** system that translates English sentences to French using various Recurrent Neural Network (RNN) architectures. The models are built from scratch using TensorFlow/Keras without pre-trained embeddings.

## Key Features
- **3 Different RNN Architectures**:
  - Simple GRU with TimeDistributed layers
  - Bidirectional GRU for better context understanding
  - Bidirectional GRU with custom Embedding layer
- **Complete preprocessing pipeline** (tokenization, padding, sequence alignment)
- **Model persistence** (saved models + tokenizers in JSON format)
- **Training with validation split** and real-time accuracy tracking
