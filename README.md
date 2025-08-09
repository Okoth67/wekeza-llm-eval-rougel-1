# Learning LLM Evaluation with ROUGE-L

This is **my personal learning notebook** where I explore how to evaluate a fine-tuned Large Language Model (LLM) using **ROUGE-L** metrics.  
It is not a full project — just an experiment to help me understand the basics of LLM evaluation.

---

## What I’m Doing Here
- Loading my **local fine-tuned LLM** (distilled GPT-2 with LoRA)
- Generating predictions for a few Kenyan finance-related questions
- Using **ROUGE-L** to measure:
  - F1 (via `evaluate`)
  - Recall, Precision, and F1 (via `rouge_score`)
- Running everything on **CPU** so it’s easy to test anywhere

---
