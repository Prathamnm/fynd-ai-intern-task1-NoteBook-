# fynd-ai-intern-task1-NoteBook-
Rating prediction using LLM prompt engineering

# Fynd AI Intern Task 1 – LLM Rating Prediction

## Overview
This project explores how Large Language Models (LLMs) can be used to predict user ratings (1–5) from textual reviews using prompt engineering techniques.

The goal is to evaluate how different prompting strategies affect prediction accuracy without fine-tuning the model.

---

## Dataset
- Source: Yelp Reviews Dataset
- Task: Predict star ratings (1–5) from review text

---

## Prompting Strategies Evaluated
1. **Baseline Prompting**
   - Direct mapping from review text to rating
2. **Structured Reasoning Prompt**
   - Explicit step-by-step reasoning before rating
3. **Few-Shot Prompting**
   - Model is guided using example reviews and ratings

---

## Results Summary
- **Baseline**: Reasonable accuracy
- **Structured Reasoning**: Inconsistent performance
- **Few-Shot Prompting**: Best accuracy (highest performance)

The experiment demonstrates that **few-shot prompting significantly improves LLM performance** without model fine-tuning.

---

## Tech Stack
- Python
- Pandas
- Scikit-learn
- Google Generative AI (LLM)
- Jupyter Notebook

---

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
