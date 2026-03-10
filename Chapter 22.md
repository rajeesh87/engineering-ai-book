# LLM Fundamentals and Prompt Engineering

## What an LLM Is

A Large Language Model (LLM) is a transformer trained on large-scale text and code. It can generate, summarize, classify, extract, and reason over input with probabilistic output.

## The Beginner Mental Model

- Input prompt in tokens.
- Model predicts likely next tokens.
- System and tool instructions shape behavior.
- Output quality depends on context quality.

## Prompting Patterns That Actually Work

- **Instruction + constraints + output format**
- **Few-shot examples for style and consistency**
- **Step-by-step decomposition for complex tasks**
- **Schema-first output (JSON) for reliable downstream use**

## Model Selection Basics

Choose models by:
- task quality requirements,
- latency limits,
- cost target,
- privacy and deployment constraints.

## Guardrails at Prompt Layer

- Define disallowed outputs.
- Require citations for factual answers.
- Reject or escalate unknown queries.
- Use structured output validation.

## Beginner Project

Create a support triage assistant that:
1. classifies support tickets,
2. extracts priority and product area,
3. produces structured JSON for a queueing system.

## Chapter Summary

Prompting is engineering, not magic. Good prompts and clear contracts are the fastest path from demo to production utility.
