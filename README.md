# Spring AI

Spring AI is an application framework for AI engineering. Its goal is to apply to the AI domain
Spring ecosystem design principles such as portability and modular design and promote using POJOs as
the building blocks of an application to the AI domain.

## Features

Spring AI provides the following features:

* Support for all major AI Model providers such as Anthropic, OpenAI, Microsoft, Amazon, Google, and
  Ollama. Supported model types include:
    * Chat Completion
    * Embedding
    * Text to Image
    * Audio Transcription
    * Text to Speech
    * Moderation
* Portable API support across AI providers for both synchronous and streaming API options are
  supported. Access to model-specific features is also available.
* Structured Outputs - Mapping of AI Model output to POJOs.
* Support for all major Vector Database providers such as Apache Cassandra, Azure Vector Search,
  Chroma, Milvus, MongoDB Atlas, Neo4j, Oracle, PostgreSQL/PGVector, PineCone, Qdrant, Redis, and
  Weaviate.
* Portable API across Vector Store providers, including a novel SQL-like metadata filter API.
* Tools/Function Calling - permits the model to request the execution of client-side tools and
  functions, thereby accessing necessary real-time information as required.
* Observability - Provides insights into AI-related operations.
* Document injection ETL framework for Data Engineering.
* AI Model Evaluation - Utilities to help evaluate generated content and protect against
  hallucinated response.
* ChatClient API - Fluent API for communicating with AI Chat Models, idiomatically similar to the
  WebClient and RestClient APIs.
* Advisors API - Encapsulates recurring Generative AI patterns, transforms data sent to and from
  Language Models (LLMs), and provides portability across various models and use cases.
* Support for Chat Conversation Memory and Retrieval Augmented Generation (RAG).
* Spring Boot Auto Configuration and Starters for all AI Models and Vector Stores - use the
  start.spring.io to select the Model or Vector-store of choice.