---
layout: page
title: Week 6 - RAG & Agents Tutorial
permalink: /lectures/week-6
parent: Lectures
nav_order: 6
---

## Topics Covered
- Zero-shot, in-context learning (ICL), and chain-of-thought (COT) prompting.  
- ReAct prompting and its applications in AI agents.  
- Differences between LLMs, RAG, and AI agents.  
- CrewAI for building structured AI workflows.  
- RAG fundamentals: indexing, retrieval, and generation.  

---

## Key Discussions

### Prompting Techniques  
The session covered various prompting techniques to enhance LLM performance, including:  
- **Zero-shot prompting**: Sensitivity to minor changes in prompts.  
- **In-context learning (ICL)**: Importance of example selection and ordering.  
- **Chain-of-thought (COT) prompting**: Teaching models to generate reasoning steps.  
- **ReAct prompting**: Combining reasoning and action to improve task execution.  

### AI Agents and Architectures  
- **AI agents** can be specialized for tasks by tuning dependencies.  
- **LLMs vs. RAG vs. Agents**: LLMs generate text, RAG retrieves and generates, but neither can autonomously execute tasks.  
- **CrewAI framework**: Enables structured, event-driven workflows with AI agents.  
- **Potential downsides**: Increased complexity, latency, resource overhead, and security concerns.  

### Retrieval-Augmented Generation (RAG)  
- **Indexing**: Converting external data into searchable embeddings.  
- **Retrieval**: Finding relevant data using vector representations.  
- **Generation**: Passing retrieved data to LLMs for response formulation.  
- **Vector storage**: Storing document embeddings in databases like Chroma, FAISS, or Pinecone.  

---

## Resources

1. **RAG Slides**  
   [download from here](https://github.com/ApplicationsOfLanguageModels/course-website-S2025/blob/main/assets/%20slides/RAG_basics_tutorial.pdf)

2. **LLM & Agents Slides**  
   [download from here](https://github.com/ApplicationsOfLanguageModels/course-website-S2025/blob/main/assets/%20slides/LLMs_and_Agents.pdf)

3. **Tutorials**  
   - [RAG with Langchain, Chroma and Cosine Similarity](https://colab.research.google.com/drive/197zdFaOZrHtu0FC9OaxNjm8Qw-4phI78?usp=sharing)
   - [CoT and React Prompting](https://colab.research.google.com/drive/1RP8oO-wNlKWAAY35aY3zLtkCkiT3jgg6?usp=sharing)
   - [Agents using Langchain](https://colab.research.google.com/drive/1BNKwhdD3-kXCa65oF4eZe_SBav7BKyGU?usp=sharing)

