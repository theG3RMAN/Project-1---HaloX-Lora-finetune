# Project-1---HaloX-Lora-finetune
Domain-specialized LoRA fine-tuned LLM for HaloX/Black Halo security workflows, trained on security docs and red team knowledge.

# HaloX LoRA Fine-Tune — Domain Security Assistant

This project fine-tunes a small open-source LLM with LoRA on HaloX/Black Halo
security documentation and red-team knowledge.

The goal is to turn a generic base model into a **domain specialist** that can:

- Explain HaloX and Black Halo scan results in clear language
- Suggest follow-up tests and remediation steps for common vulnerabilities
- Act as a security Q&A assistant for red-team workflows

Instead of building yet another toy chatbot, this repo shows how to:

- Prepare a focused instruction dataset from real security content
- Fine-tune a 7B-class LLM with LoRA/QLoRA using HuggingFace + PEFT
- Evaluate base vs fine-tuned behavior on domain-specific prompts
- Package the result with a model card, inference script, and clean documentation
