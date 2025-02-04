---
layout: page
title: Week 4 - RAG
permalink: /lectures/week-4
parent: Lectures
nav_order: 4
---

## Topics Covered
- **RAG**: A powerful method for enhancing LLMs with external knowledge, improving accuracy and reducing hallucinations.
- **Different retrieval strategies** (document vs. token-level) which cater to varying application needs.
- APIs like **Groq** which enable real-time AI interactions with minimal setup.
- **Fine-tuning** (with Qwen2.5 (7B)) helps tailor LLMs for domain-specific tasks while optimizing memory usage.
-  **Llama3.2 (11B) Vision** supports multi-modal processing: handles both text and images.

---

## Key Discussions

1. **Retrieval-Augmented Generation (RAG)**
    - Concept: RAG combines retrieval systems with LLMs to integrate external knowledge dynamically.
    - Workflow:
        - Query Understanding – LLM interprets the user’s input.
        - Information Retrieval – The query is matched against a document repository.
        - Contextual Generation – Retrieved data is used to generate accurate responses.
    - Advantages:
        - Improved accuracy by incorporating real-time external data.
        - Adaptability to domain-specific datasets (healthcare, legal, etc.).
        - Reduction in hallucinations by grounding responses in retrieved content.
    - Types of Retrieval in RAG
        - Blackbox Retrieval
        - Sparse Retrieval
        - Dense Retrieval: Embeddings-based techniques using BERT or DPR.
        - Document-Level Dense Retrieval: Retrieving entire documents based on embeddings.
        - Token-Level Dense Retrieval: Fine-grained retrieval at the token level.
2. **RAG Applications**
    - Education: Adaptive learning and interactive tutoring.
    - Healthcare: Clinical decision support and research assistance.
    - Customer Support: Automated responses with real-time updates.
3. **Talk with Vishnu Ramesh from subtl.ai**
    - Enabling users to query vast document repositories in everyday language and receive precise, context-aware answers within seconds.
    - 92% accuracy rate in AI-driven document retrieval.
    - Successfully reduced search time for State Bank of India (SBI), saving over 56,570 minutes in document lookup.
    - Core Technical Innovations:
        - Enhanced Retrieval-Augmented Generation with semantic search, hierarchical chunking and domain-specific finetuning.
        - Advanced Query Parsing using NER with multimodal supprt and RLHF.
        - Latency optimization using Faiss and ElasticSearch for 2-second response times.
4. **Tutorial**
    - API Integration with Groq
    - Fine-Tuning with Qwen2.5 (7B) – Alpaca with HF Unsloth
        - Using 4-bit quantization for memory efficiency.
    - LLaMa3.2 Vision 11B
        - Supports multi-modal AI tasks, including medical imaging analysis.
    
---

## Resources

1. **Lecture Slides**  
   [download from here](https://github.com/ApplicationsOfLanguageModels/course-website-S2025/blob/main/assets/%20slides/2025-01-20.pdf)

2. **API Calling/Unsloth AI Finetuning Resources**  
    - [Groq and Gemini API Use](https://colab.research.google.com/drive/1nSSBQC364cSlsrGT9va-6ogMiURFX8jX?usp=sharing)
    - [Text-to-Text Model Finetuning](https://colab.research.google.com/github/unslothai/notebooks/blob/main/nb/Qwen2.5_(7B)-Alpaca.ipynb)
    - [Vision-to-Text Model Finetuning](https://colab.research.google.com/github/unslothai/notebooks/blob/main/nb/Llama3.2_(11B)-Vision.ipynb)

