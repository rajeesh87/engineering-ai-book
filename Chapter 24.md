# Retrieval-Augmented Generation (RAG)

## What RAG Solves

RAG combines retrieval and generation so an LLM can answer using external, up-to-date knowledge instead of only pretraining memory.

## Standard RAG Pipeline

1. Ingest and chunk content.
2. Create embeddings and index vectors.
3. Retrieve relevant chunks per question.
4. Compose prompt with context.
5. Generate answer with citations.

## RAG Quality Levers

- retrieval precision and recall,
- prompt template quality,
- citation enforcement,
- reranking and filtering,
- freshness strategy for index updates.

## Security and Safety in RAG

- sanitize retrieved text,
- defend against prompt injection in documents,
- apply access controls at retrieval stage,
- enforce source-aware redaction.

## Evaluation Basics

Track:
- answer correctness,
- citation faithfulness,
- retrieval hit rate,
- latency and cost per request.

## Beginner Project

Build a "policy assistant" for internal docs with:
- role-based access,
- cited responses,
- fallback when evidence is insufficient.

## Chapter Summary

RAG is the most practical way for beginners to build useful, trustworthy LLM applications on private data.
