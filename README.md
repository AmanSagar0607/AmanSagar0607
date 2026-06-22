<h1 align="left">Hi, I’m Aman Sagar</h1>

<p align="left">
  Software Dev from India building AI agents, RAG pipelines, and GenAI products.
</p>

<p align="left">
  I like shipping the full stack: UI, backend, APIs, and the AI pieces that make a product actually useful.
  Right now I’m focused on <strong>Context-OS</strong>, my open-source project for memory, search, crawl, and knowledge workflows for AI agents.
</p>

## What I’m working on

- Context-OS — open-source infrastructure for AI agent memory and retrieval
- OpenKai — AI-powered project management and team collaboration workspace
- Aman Agent Lab — experiments with agents, workflows, and AI product ideas

## Context-OS architecture

```mermaid
flowchart LR
  U[User / App Input] --> I[Ingestion Layer]
  I --> P[Processing Layer]
  P --> S[Storage Layer]

  S --> R[Retrieval Layer]
  R --> C[Context Builder]
  C --> A[LLM / Agent]

  W[Crawl Sources] --> I
  K[Knowledge Sources] --> I
  Q[Search Queries] --> R

  A --> O[Response / Action]
  O --> M[Memory Update]
  M --> S
