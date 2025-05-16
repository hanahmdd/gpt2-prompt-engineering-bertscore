GPT-2 Prompt Engineering Benchmark
This repository provides a framework for evaluating different prompt engineering techniques for GPT-2 text generation using BERTScore metrics.
Overview
This project explores how different prompt types affect GPT-2's ability to generate motivational content about persistence and success in academic contexts. Six different prompt types are compared:

Direct Instruction
Scenario-Based
Persona-Based (two variants)
Keyword-Based
Conversational

Each prompt is evaluated using BERTScore against a human-written reference quote.
Features

Automated generation of text completions using GPT-2
Evaluation of outputs using BERTScore metrics
Visualization of results with detailed comparisons
Customizable prompt engineering framework

Results
The analysis reveals that Direct Instruction prompts tend to yield the highest BERTScore F1 values, followed by Persona-Based approaches. The results demonstrate how prompt engineering can significantly impact language model output quality.


Requirements

Python 3.7+
PyTorch
transformers
bert_score
pandas
matplotlib
seaborn

