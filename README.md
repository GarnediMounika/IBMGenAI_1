# IBMGenAI_1
# Text Generation with Decoding Strategies | IBM GenAI

This project demonstrates how different decoding techniques affect the text output from a pre-trained language model (GPT-2). It provides a comparative analysis of common decoding strategies such as greedy decoding, temperature sampling, top-k sampling, and nucleus (top-p) sampling.

## Objective

To understand and analyze how decoding strategies influence:
- Output diversity
- Coherence
- Creativity of generated text


## Setup

- Python 3.8+
- Hugging Face Transformers
- Jupyter Notebook or Google Colab


pip install transformers

# Tasks Overview
✅ Model Initialization
Load GPT-2 model and tokenizer.

✅ Prompt Handling
Use 2 unique prompts.

Generate baseline output using greedy decoding.

✅ Token Analysis
Display generated token IDs and decoded tokens.

✅ Decoding Strategy Evaluation
For Prompt 1:

Temperature Sampling (temperature = 0.7)

Top-k Sampling (k = 50)

Top-p Sampling (p = 0.9)

✅ Output Comparison
Compare and evaluate:

Repetitiveness

Originality

Sentence flow and logic

# Key Observations
Decoding Method	Characteristics
Greedy Decoding	Deterministic, often repetitive
Temperature	Controlled randomness, more diverse
Top-k Sampling	Random within fixed vocabulary size
Top-p Sampling	Balances coherence and creativity

# Repository Contents
task1_text_generation.ipynb – Implementation Notebook

outputs/ – Generated text samples and screenshots

🔗 Useful Links
Hugging Face Transformers Docs  https://huggingface.co/docs/transformers
