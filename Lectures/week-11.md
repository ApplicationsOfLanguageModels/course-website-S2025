---
layout: page
title: Week 11 - Responsible AI
permalink: /lectures/week-11
parent: Lectures
nav_order: 11
---

## Topics Covered  
- Key concepts of fairness, accountability, transparency, and ethics (FATE) in AI.  
- Challenges of bias, hallucination, and content safety in LLMs.  
- Evaluation frameworks for safe and responsible AI.  
- Social and systemic issues in model behavior, especially in multimodal and conversational models.  

---

## Key Discussions  

### Motivating Examples and Historical Lessons  
The session opened with real-world failures from AI systems:  
- **Microsoft Tay**: The chatbot quickly adopted harmful behavior through user interaction.  
- **Amazon’s Recruiting Tool**: Showed bias against women, leading to its discontinuation.  
- **Chatbot-assisted Suicide Case**: Raised serious ethical concerns about unsupervised AI use.

These examples underscored the need for careful design and monitoring of AI systems.

### Core Responsible AI Challenges  
- **Content Harm**: Including hate, sexual content, violence, and self-harm.  
- **Hallucination**: AI confidently generating false or misleading information.  
- **Stereotyping**: Models revealing bias in language and visual interpretation tasks.  
- **Multimodal Risks**: Increased complexity and vulnerability when models handle both text and images.  

### Fairness, Accountability, Transparency, Ethics (FATE)  
A framework to evaluate and mitigate AI risks:  
- **Fairness**: Avoiding discrimination, especially in protected variables (e.g., gender, race).  
- **Accountability**: Determining responsibility for AI decisions (e.g., websites, algorithms).  
- **Transparency**: Ensuring traceability of answers and citations.  
- **Explainability**: Being able to justify and communicate model decisions clearly.

### Evaluation Frameworks  
- **SAGE System**: Generates adversarial prompts to test model behavior across personality types and task complexity.  
- **Model Performance**:  
  - Llama-2 family was found to be safest.  
  - Mistral and Phi-3 models showed more unsafe behavior.  
  - Defects increase with conversation length and vary across model types.

### Detecting and Measuring Bias  
- **LLM Stereotype Index (LSI)**: Framework using demographics, prompts, and response metrics like:  
  - **Choice Refusal Percentage (CRP)**  
  - **Stereotype Polarity (SP)**  
- Found that **bias worsens with increasing task complexity**, indicating a need for dynamic, task-aware evaluations.

### Systemic Considerations  
- **Data Transparency**: Source visibility and citation inclusion are essential.  
- **Evaluation Gaps**: Current tests often miss nuanced harms.  
- **Beyond English**: Broader linguistic and cultural scope needed for global AI models.

---

## Key Takeaways  
- Responsible AI involves more than model tuning—it requires robust, multi-layered evaluation systems.  
- Tools like **SAGE** and metrics like **LSI** help quantify and mitigate AI harms.  
- FATE dimensions (Fairness, Accountability, Transparency, Explainability) offer a foundational lens.  
- The interplay of model behavior, user traits, and prompt complexity reveals hidden challenges in LLM safety.  

---

## Project Discussions  
Group project discussions focused on how students can incorporate responsible AI practices in their final deliverables. Topics included bias testing, safety considerations, and transparent result presentation.

## Resources

1. **Slides by Sandipan Dandapat**  
   [download from here](https://github.com/ApplicationsOfLanguageModels/course-website-S2025/blob/main/assets/%20slides/ResponsibleAI.pdf)
