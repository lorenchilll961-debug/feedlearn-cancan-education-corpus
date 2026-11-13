# Feedlearb · 灿灿教育智能体语料库

> A curated implementation corpus for an AI-assisted learning platform built around retrieval, knowledge organization and personalized learning workflows.

## Purpose

This repository preserves the project’s iterative design and implementation notes for **Feedlearb / 灿灿 AI 4.0**. It is useful as a Chinese-language reference corpus for education-agent prototyping, product decomposition, and RAG application design.

The material documents a proposed system that combines document ingestion, semantic retrieval, knowledge-graph views, learning-path generation, question generation, summaries and a conversational interface.

## Corpus scope

| Module | Coverage |
| --- | --- |
| Product foundation | Flask application structure, front-end pages and upgrade notes |
| Resource intelligence | Document parsing, chunking, vector retrieval and resource management |
| Learning experience | Chat, learning center, path planning, question generation and summaries |
| Knowledge organization | Knowledge-graph page and graph-construction modules |
| Project narrative | Team, milestones, help, news and contact-page drafts |

## Dataset card

- **Language:** Simplified Chinese, with technical English terms.
- **Format:** Plain-text implementation notes, prompts and code-generation drafts.
- **Intended use:** Educational reference, prototyping analysis and non-production experimentation.
- **Not included:** User learning records, API credentials, uploaded learner documents or production deployment configuration.
- **Caveat:** These files capture an evolving implementation process. They are not a validated production system or a benchmark dataset.

## Structure

```text
corpus/
  4.0后端.step1.txt
  4.0文档处理模块.step14.txt
  4.0向量数据模块.step15.txt
  4.0知识图谱构建模块.step17.txt
  ...
```

## Safety and privacy

Secret-like demo values have been replaced with environment-variable examples. If you turn these drafts into an application, use secret management, authentication, access controls, data-retention policies and an appropriate privacy review before accepting learner content.

## Suggested citation

`Feedlearb · 灿灿教育智能体语料库, implementation corpus, 2026.`
