# GPT-2 Attention Visualization

This repository demonstrates how to inspect and visualize the inner workings of the GPT-2 model using PyTorch and Hugging Face Transformers. It covers token embeddings, attention mechanisms, hidden states, and next-token prediction.

---

## Features
- Load pre-trained GPT-2 model and tokenizer
- Encode text into token IDs
- Extract attention scores for each layer and head
- Visualize attention using `bertviz`
- Inspect hidden states and next-token predictions

---

## Requirements
- Python 3.8+
- torch
- transformers
- pandas
- bertviz

---

## Usage
1. Clone the repository:
```bash
git clone https://github.com/yourusername/gpt2-attention-visualization.git

Install dependencies:

pip install torch transformers pandas bertviz

Run the notebook to explore GPT-2 attention and hidden states.
