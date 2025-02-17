## LoRA Fine-Tuning Demo: Dialogue Summarization
This demo fine-tunes a Flan-T5-small model using LoRA on the Samsum dataset to perform dialogue summarization. It leverages Hugging Face’s Transformers, Datasets, and PEFT libraries for an efficient fine-tuning process.

## Overview
### Data Preparation:
Load a subset of the Samsum dataset, convert dialogues into summarization tasks (instruction-response pairs), and tokenize the text.

### Model Fine-Tuning:
Adapt the Flan-T5-small model using LoRA, then fine-tune it on the prepared dataset with support for mixed precision.

### Inference:
After training, generate summaries for new dialogues using the fine-tuned model.

## Setup
Ensure you have Python 3.8+ installed. Required libraries include:

Transformers
Datasets
PEFT
Accelerate
SentencePiece
PyTorch
(Optionally, install wandb for logging.)

## License
This project is licensed under the MIT License.
