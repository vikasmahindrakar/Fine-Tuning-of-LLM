# Fine-Tune a Generative AI Model for Dialogue Summarization

This repository demonstrates fine-tuning Hugging Face's **FLAN-T5** model for dialogue summarization using two approaches: **Full Fine-Tuning** and **Parameter Efficient Fine-Tuning (PEFT)**. The performance is evaluated using ROUGE metrics.

## Features

- Implements Full Fine-Tuning and PEFT.
- Uses ROUGE metrics for evaluation.
- Prepares and processes dialogue-summary datasets.

## Results

| Method              | ROUGE-1 | ROUGE-2 | ROUGE-L |
|---------------------|---------|---------|---------|
| Full Fine-Tuning    | 0.85    | 0.78    | 0.80    |
| PEFT                | 0.82    | 0.75    | 0.78    |
