# Fine-Tune a Vision Transformer with LoRA

## Description
This project demonstrates how to adapt a **pre-trained Vision Transformer (ViT)** to recognize a new class (e.g., "raccoon") using **LoRA**.  
It allows efficient fine-tuning of a large model with **few trainable parameters**.

## Features
- Prepare a small image dataset
- Update the classification head for a new class
- Efficient fine-tuning with LoRA
- Training and evaluation on CPU

## Technologies Used
- Python 3
- PyTorch
- Hugging Face Transformers & Datasets
- PEFT (LoRA)
- Pillow & Matplotlib

## Installation
```bash
pip install torch==2.9.0
pip install transformers==4.57.1
pip install datasets==3.6.0
pip install peft==0.17.1
pip install pillow==12.0.0
pip install matplotlib==3.10.7
