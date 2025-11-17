📘 English-to-German Machine Translation using Transformer

A complete ML/NLP pipeline using HuggingFace Transformers

📌 Overview

This project implements English → German Machine Translation using a Transformer-based Seq2Seq model.
You fine-tune the Helsinki-NLP/opus-mt-en-de model on 50k parallel EN–DE sentences, evaluate using BLEU score, perform inference, compare results with a previous LSTM translation model, and visualize self-attention & cross-attention heatmaps.

🚀 Features

✔ Fine-tuning Transformer (Seq2Seq)
✔ Custom dataset preprocessing (tokenization + padding)
✔ BLEU evaluation
✔ Inference pipeline
✔ Comparison with LSTM-based translation model
✔ Encoder self-attention heatmap
✔ Encoder–decoder cross-attention visualization
✔ Saved fine-tuned model for reuse

🧠 Model Architecture

Encoder–Decoder Transformer

Self-Attention in encoder

Cross-Attention in decoder

Tokenizer: SentencePiece

HuggingFace AutoModelForSeq2SeqLM

📂 Project Structure
