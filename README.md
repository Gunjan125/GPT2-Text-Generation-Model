# GPT-2 Text Generation Model

This project demonstrates how to generate human-like text using the GPT-2 language model from Hugging Face Transformers. The notebook loads a pre-trained GPT-2 model, tokenizes an input prompt, and generates text using decoding methods such as **Beam Search** and **Nucleus Sampling (Top-P)**.


## 🚀 Features

- Uses **GPT-2 (gpt2-large)** model for text generation
- Supports **Beam Search** and **Top-P Sampling**
- Implemented using **Transformers** and **PyTorch**
- Simple and easy-to-modify code
- Runs on **CPU or GPU**


## 📌 How It Works

1. Load GPT-2 tokenizer & model
2. Tokenize input text
3. Generate output using:
   - `num_beams` (Beam Search) or
   - `top_p` (Nucleus Sampling)
4. Decode and print the generated text

