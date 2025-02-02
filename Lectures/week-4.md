---
layout: page
title: Week 4 - RAG
permalink: /lectures/week-4
parent: Lectures
nav_order: 4
---

## Topics Covered
- RAG: A powerful method for enhancing LLMs with external knowledge, improving accuracy and reducing hallucinations.
- Different retrieval strategies (document vs. token-level) which cater to varying application needs.
- APIs like Groq which enable real-time AI interactions with minimal setup.
- Fine-tuning (with Qwen2.5 (7B)) helps tailor LLMs for domain-specific tasks while optimizing memory usage.
-  Llama3.2 (11B) Vision supports multi-modal processing: handles both text and images.

---

## Key Discussions

1. Retrieval-Augmented Generation (RAG)
    - Concept: RAG combines retrieval systems with LLMs to integrate external knowledge dynamically.
    - Workflow:
        - Query Understanding – LLM interprets the user’s input.
        - Information Retrieval – The query is matched against a document repository.
        - Contextual Generation – Retrieved data is used to generate accurate responses.
    - Advantages:
        - Improved accuracy by incorporating real-time external data.
        - Adaptability to domain-specific datasets (healthcare, legal, etc.).
        - Reduction in hallucinations by grounding responses in retrieved content.
2. Types of Retrieval in RAG
    - Blackbox Retrieval: Using external search engines (e.g., Google, Bing).
    - Sparse Retrieval: BM25 and TF-IDF methods.
    - Dense Retrieval: Embeddings-based techniques using BERT or DPR.
    - Document-Level Dense Retrieval: Retrieving entire documents based on embeddings.
    - Token-Level Dense Retrieval: Fine-grained retrieval at the token level.
3. Dense Retrieval: Document-Level vs. Token-Level
    - Document-Level:
        - Retrieves entire sections for response generation.
        - Used for FAQs and general knowledge applications.
    - Token-Level:
        - Retrieves specific tokens for precise answers.
        - Suitable for open-domain question answering in fields like medicine and law.
4. Triggering Retrieval
    - Token-Based Retrieval: Models generate special tokens that trigger searches.
    - Uncertainty-Based Retrieval: Retrieval is triggered when the model is unsure.
    - Continuous Retrieval: Retrieval occurs at every token generation step.
5. RAG Applications
    - Education: Adaptive learning and interactive tutoring.
    - Healthcare: Clinical decision support and research assistance.
    - Customer Support: Automated responses with real-time updates.
6. Talk with Vishnu Ramesh from subtl.ai
    - Enabling users to query vast document repositories in everyday language and receive precise, context-aware answers within seconds.
    - 92% accuracy rate in AI-driven document retrieval.
    - Successfully reduced search time for State Bank of India (SBI), saving over 56,570 minutes in document lookup.
    - Applicable across banking, legal, manufacturing, and education sectors, minimizing reliance on subject-matter experts.
    - Core Technical Innovations:
        - Enhanced Retrieval-Augmented Generation with semantic search, hierarchical chunking and domain-specific finetuning.
        - Advanced Query Parsing using NER with multimodal supprt and RLHF.
        - Latency optimization using Faiss and ElasticSearch for 2-second response times.
7. API Integration with Groq
    - Groq API Overview:
        - Installation and setup using pip install groq.
        - Instantiating a Groq client with an API key.
    - Example Use Case:
        - Sending prompts to an AI model via API calls.
        - Using the API for conversational AI applications.
    - Practical Example:
        - Generating simple explanations for complex topics like black holes.
        - Implementing chat-based applications with real-time inference.
8. Fine-Tuning with Qwen2.5 (7B) – Alpaca
    - Model Training with Unsloth:
        - Using 4-bit quantization for memory efficiency.
        - Loading models like Qwen2.5-7B.
    - Training Process:
        - Dataset Preparation: Using Alpaca-cleaned data.
        - Fine-tuning with SFTTrainer and LoRA adapters.
    - Performance Metrics:
        - Loss reduction during training.
        - Memory optimization techniques.
    - Inference:
        - Generating responses based on structured instructions.
        - Using Hugging Face and Unsloth for deployment.
9. LLaMa3.2 Vision 11B
    - Supports multi-modal AI tasks, including medical imaging analysis.
    - Efficient fine-tuning with 4-bit quantization and LoRA reduces memory usage.
    - Vision-language fine-tuning can improve radiology analysis, object detection, and captioning tasks.
    - Can be optimized for deployment with FP16 and Hugging Face Hub integration.

---

## Resources

1. **Lecture Slides**  
   [download from here](https://github.com/ApplicationsOfLanguageModels/course-website-S2025/blob/main/assets/%20slides/2025-01-20.pdf)

2. **API Calling/Unsloth AI Finetuning Resources**  
    - [Groq and Gemini API Use](https://colab.research.google.com/drive/1nSSBQC364cSlsrGT9va-6ogMiURFX8jX?usp=sharing)
    - [Text-to-Text Model Finetuning](https://colab.research.google.com/github/unslothai/notebooks/blob/main/nb/Qwen2.5_(7B)-Alpaca.ipynb)
    - [Vision-to-Text Model Finetuning](https://colab.research.google.com/github/unslothai/notebooks/blob/main/nb/Llama3.2_(11B)-Vision.ipynb)

