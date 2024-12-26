# emotion-classification-roberta-peft

This project leverages **Parameter-Efficient Fine-Tuning (PEFT)** techniques to classify emotions using the pre-trained **RoBERTa** model. The goal is to explore lightweight fine-tuning methods for text classification tasks.

## Overview
This repository implements and evaluates the following:
1. **Out-of-the-Box Model**: RoBERTa model used without any fine-tuning.
2. **Fine-Tuned Model**: Fully fine-tuned RoBERTa model.
3. **QLoRA**: Quantized Low Rank Adaptation for efficient fine-tuning.
4. **Prefix Tuning**: Lightweight fine-tuning by adding trainable prefix tokens.

## Dataset
- **Emotion Dataset**: Contains text samples labeled with six emotions: `sadness`, `joy`, `love`, `anger`, `fear`, and `surprise`.
- Dataset link: [Emotion Dataset](https://huggingface.co/datasets/dair-ai/emotion)

## License
This project is licensed under the MIT License. 
