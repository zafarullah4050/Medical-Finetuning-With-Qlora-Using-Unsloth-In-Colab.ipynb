# Medical-Finetuning-With-Qlora-Using-Unsloth-In-Colab.ipynb
Medical QLoRA Fine-tuning App
This is a Streamlit-based app to fine-tune a large language model (LLM) for medical domain tasks using QLoRA (quantized Low-Rank Adaptation). It enables loading a base model, uploading a custom medical dataset, tokenizing data, fine-tuning with LoRA adapters, and testing the fine-tuned model — all from an interactive web interface.

Features
Load base pretrained models (e.g., LLaMA variants)

Upload custom domain-specific medical dataset in .jsonl format

Tokenize dataset for training

Set up LoRA adapters and fine-tune model efficiently using QLoRA

Save fine-tuned model locally

Generate responses to medical queries using the fine-tuned model

Requirements
Python 3.8+

Streamlit

Transformers

Datasets

PEFT (Parameter-Efficient Fine-Tuning)

bitsandbytes

PyTorch

Installation
bash
Copy
Edit
pip install streamlit transformers datasets peft bitsandbytes accelerate torch
