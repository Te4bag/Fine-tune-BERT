# Emotion Classification - Fine-Tuning BERT

This repository contains a Jupyter Notebook for fine-tuning a base BERT model using the [`dair-ai/emotion`](https://huggingface.co/datasets/dair-ai/emotion) dataset.

## Overview

The notebook fine-tunes a `bert-base-uncased` model to classify emotions from text using LoRA (Low-Rank Adaptation) and bitsandbytes for efficient training.

### Key Features:
- Instruction-style format for input text.
- Efficient fine-tuning using Hugging Face `transformers`, `datasets`, `trl`, and `peft`.
- 8-bit quantization with selective training via LoRA.
- Evaluates model using standard metrics.

## Test Metrics 

| Metric           | Value      |
|------------------|------------|
| Accuracy         | 92.05%     |
| Precision        | 92.18%     |
| Recall           | 92.05%     |
| F1 Score         | 92.10%     |
| Eval Loss        | 0.222      |
