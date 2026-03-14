# BART Text Generation Project – Phase 4

## Project Overview
This project demonstrates the deployment of the BART (Bidirectional and Auto-Regressive Transformer) model for text generation using Google Colab. The model can generate summaries, continuations, or responses based on input text.

## Phase Objective
- Deploy BART for text generation in a production-like environment.
- Demonstrate end-to-end usage: dataset preparation → fine-tuning → generation → deployment.

## Features
- Load and fine-tune BART on a dataset (e.g., news summaries)
- Generate text summaries or continuations from input text
- Interactive web interface using Gradio
- Save the fine-tuned model for future use

## Requirements
- torch
- transformers
- datasets
- sentencepiece
- gradio
- numpy
- pandas
- tqdm

Install with:
```bash
pip install -r requirements.txt# BART_Text_Generation
