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




# Fine-Tune FLAN-T5 with Reinforcement Learning (PPO) and PEFT to Generate Less-Toxic Summaries
Overview
This project fine-tunes the FLAN-T5 model using reinforcement learning with the Proximal Policy Optimization (PPO) algorithm and Parameter-Efficient Fine-Tuning (PEFT) techniques. The goal is to generate text summaries that are less toxic while maintaining coherence and relevance.

## Features
Model: Utilizes the FLAN-T5 architecture for text summarization.
Reinforcement Learning: Applies PPO for optimizing the model's text generation capabilities.
PEFT: Leverages parameter-efficient methods for fine-tuning large language models.
Toxicity Reduction: Integrates a toxicity classifier to minimize harmful content in generated summaries.
Use Cases
Creating safe and responsible content summaries.
Fine-tuning large language models for specific text-generation tasks.
Enhancing NLP models with reinforcement learning and PEFT techniques.

## Acknowledgments
Hugging Face Transformers Library
OpenAI's RLHF Research
Perspective API for Toxicity Detection
