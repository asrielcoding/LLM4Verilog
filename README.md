# LLM4Verilog
Fine-tuned LLM for Verilog code generator

- Dataset collection
- Description generatation
- Fine tuning
- Validation

## Dataset collection
Use GPT API for verilog code generation and collect verilog code on GitHub.
- Including Verilog and System Verilog
- Each data has prompt and code

## Description generation
Different layers of description to help LLM learn how the codes work.
- Use GPT API
- Including Detailed Description and line-by-line comment

## Fine tuning
Train my model with my dataset on Google Colab.
- Llama3
- unsloth

