# AI Workout Generator (Fine-Tuned Language Model)

This project is a **Python-based AI workout generator** built using the Hugging Face `transformers` library and PyTorch. It loads a **fine-tuned causal language model** and generates personalized workout routines in natural language based on user prompts.

The model is designed to stop generation using a custom `<END>` token, ensuring clean and controlled outputs.

---

## Features

- Loads a **locally fine-tuned language model**
- Uses **custom special tokens** (`<END>`) to control text termination
- Supports **GPU (CUDA)** or **CPU** execution automatically
- Generates workouts using **sampling-based text generation**
- Clean post-processing to remove prompt echo and stop tokens

---

## Requirements

- Python 3.9+
- PyTorch
- Hugging Face Transformers

Install dependencies:

```bash
pip install torch transformers
