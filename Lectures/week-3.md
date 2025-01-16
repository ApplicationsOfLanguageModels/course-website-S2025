---
layout: page
title: Week 3 - Small Language Models and Model Optimization
permalink: /lectures/week-3
parent: Lectures
nav_order: 3
---

## Topics Covered
- Introduction to SLMs and parameter sizes.  
- Techniques for model compression: quantization, pruning, and distillation.  
- Practical considerations for using high-dimensional embeddings.  
- Plans for future topics: RAG frameworks and agent frameworks.  

---

## Key Discussions

### Small Language Models (SLMs)
The session focused on understanding and optimizing small language models (SLMs), defined as models with fewer than 10 billion parameters. Key points included:  
- **Parameter Sizes**: Context was provided on the parameter scales of models like BERT and GPT-4.  
- **Practical Applications**: The importance of reducing model sizes to address memory management and inference latency.  

### Techniques for Model Optimization
- **Quantization**: Reducing memory requirements by lowering data representation precision.  
- **Pruning**: Differentiated between unstructured and structured pruning techniques.  
- **Distillation**: Building smaller models by transferring knowledge from larger ones.  
- **Matryoshka Embedding Models**: Highlighted for applications in search and recommendation systems.

---

## Resources

1. **What are Small Language Models?**  
   [IBM Article](https://www.ibm.com/think/topics/small-language-models)

2. **A Visual Guide to Quantization**  
   [by Marten Grootendorst](https://newsletter.maartengrootendorst.com/p/a-visual-guide-to-quantization)

3. **Binary and Scalar Embedding Quantization**  
   [for faster and cheaper retrieval](https://huggingface.co/blog/embedding-quantization)  

4. **Distiller**  
   [open-source Python package for neural network compression](https://github.com/IntelLabs/distiller/)

5. **Pruning and Distilling Llama-3.1**  
   [how to optimize Llama-3.1 8B to Minitron 4B](https://developer.nvidia.com/blog/how-to-prune-and-distill-llama-3-1-8b-to-an-nvidia-llama-3-1-minitron-4b-model)  

6. **Beyond Answers**  
   [transferring reasoning capabilities to smaller LLMs using multi-teacher knowledge distillation](https://arxiv.org/abs/2402.04616)  

7. **Lecture Recording**  
   [watch here](https://drive.google.com/file/d/16Zf5MfOhpW1kZRnH7ZGqeZfPdoEFnzH3/view)  

8. **Lecture Slides**  
   [download from here](https://github.com/ApplicationsOfLanguageModels/course-website-S2025/blob/main/assets/%20slides/2025-01-16.pdf)  

---

## Tutorials to cover based on post-class feedback
- **Fine-tuning with PEFT and Quantization**  
- **PyTorch Model Loading**  
- **LLM API Documentation and Usage**  
- **RAG Frameworks**  
- **Agent Frameworks**  
