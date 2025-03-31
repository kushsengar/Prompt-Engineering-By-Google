# Prompt-Engineering-By-Google


# Day 1: Prompt Engineering

## Introduction
Prompt engineering is the art of designing effective prompts to guide AI models in generating desired responses. Adjusting parameters such as temperature, top-P, and top-K can significantly influence the creativity, coherence, and accuracy of model outputs.

## Parameter Tuning
To fine-tune the model's response, consider the following settings:

- **Balanced Output:**
  - Temperature: `0.2`
  - Top-P: `0.95`
  - Top-K: `30`
  - Yields coherent and moderately creative results.

- **Highly Creative Output:**
  - Temperature: `0.9`
  - Top-P: `0.99`
  - Top-K: `40`
  - Generates more imaginative responses but may introduce hallucinations.

- **Less Creative (More Deterministic) Output:**
  - Temperature: `0.1`
  - Top-P: `0.9`
  - Top-K: `20`
  - Ideal for structured and predictable outputs.

- **Single Correct Answer (e.g., Math Problems):**
  - Temperature: `0.0`
  - Ensures consistency by eliminating randomness.

## Types of Prompting
1. **Zero-Shot Prompting**: Providing a prompt without examples.
2. **Single-Shot Prompting**: Providing a single example to guide the model.
3. **Few-Shot Prompting**: Providing 3 to 5 examples to improve response accuracy.

## Chain of Thought (CoT) Prompting
Chain-of-Thought (CoT) prompting instructs the model to generate intermediate reasoning steps before delivering a final answer. This approach enhances logical coherence and improves performance on complex reasoning tasks.

### Key Points about CoT:
- Works best when combined with few-shot examples.
- Helps the model produce more structured reasoning.
- Increases token usage, leading to higher computational costs.
- Does not fully eliminate hallucinations but improves reliability.


Feel free to contribute by sharing insights and improvements!

🚀 Happy Prompting!


