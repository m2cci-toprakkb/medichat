# MediChat: LoRA Fine-Tuning of LLaMA 3.1 (8B) on ChatDoctor Dataset

## Overview
This repository contains a notebook that demonstrates how to fine-tune the LLaMA 3.1 (8B) model using the [LoRA (Low-Rank Adaptation)](https://arxiv.org/abs/2106.09685) method. The fine-tuning process leverages the [lavita/ChatDoctor-HealthCareMagic-100k](https://huggingface.co/datasets/lavita/ChatDoctor-HealthCareMagic-100k) dataset, specifically curated for medical conversational AI tasks. The final model is saved in **GGUF format** for optimal deployment.

## Features
- **Model:** LLaMA 3.1 (8B)
- **Fine-Tuning Framework:** LoRA
- **Dataset:** [ChatDoctor-HealthCareMagic-100k](https://huggingface.co/datasets/lavita/ChatDoctor-HealthCareMagic-100k)
- **Output Format:** GGUF for efficient inference
- **Notebook:** Step-by-step instructions for fine-tuning and saving the model

## Contents
- `finetune_llama.ipynb`: A notebook detailing the fine-tuning process, including:
  - Dataset preprocessing
  - Application of a chat template for medical consultations
  - LoRA fine-tuning pipeline
  - Exporting the fine-tuned model in GGUF format
