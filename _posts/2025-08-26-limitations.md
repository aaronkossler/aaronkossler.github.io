---
title: "Limitations of Large Language Models"
date: 2024-06-21 12:00:00 +0200
categories: [Research, Seminar]
tags: [clustering, classification]
description: "Seminar project analyzing the limitations of LLMs through literature review, LLM-based classification, and clustering of 90k+ research papers."
author: aaron
image:
  path: /assets/img/limitations.jpg
  alt: Pipeline
pin: false
---

### 🎯 Goals

**Systematically analyze and categorize the limitations of Large Language Models (LLMs)** by combining literature review with LLM-based classification and clustering.  

Focus:
1. **Identify recurring limitation categories** in academic research  
2. **Evaluate LLMs for meta-analysis tasks** (classification, clustering)  
3. **Highlight research trends** on LLM weaknesses over time  

---

### 🚀 Key Contributions

1. **Dataset creation** — crawled **~90k papers** from ACL Anthology & arXiv (2022–2024).  
2. **Classification pipeline** — applied GPT-4 Turbo and Mistral 7B Instruct to identify papers explicitly discussing LLM limitations.  
3. **Prompt engineering** — improved classification accuracy on smaller models (+9% F1 score for Mistral).  
4. **Clustering** — tested standalone LLM, BERTopic, and ClusterLLM approaches to group limitation themes.  
5. **Topic analysis** — derived clusters such as **bias, hallucination, reasoning, long-input handling, safety/privacy**.  

---

### 📊 Results

- **Mistral 7B Instruct** achieved the best classification performance (F1 = **0.82**), outperforming GPT-4 Turbo in balanced accuracy.  
- **BERTopic** proved **most reliable for clustering**, surfacing consistent limitation domains such as **bias, hallucination, reasoning gaps, and safety/privacy risks**.  
- **Trend analysis** showed a **doubling** of papers on LLM limitations between 2023–2024, reflecting rising awareness in the research community.  
- Confirmed that **LLMs can support meta-analysis tasks** (classification & clustering), but outputs require **human validation** for reliability.  

---

### 🛠 Tech Stack

| Area               | Tools & Frameworks                                 |
| ------------------ | -------------------------------------------------- |
| **Languages**      | Python, Bash                                       |
| **ML Frameworks**  | Hugging Face Transformers, BERTopic, scikit-learn  |
| **Infrastructure** | Slurm                                              |
| **Models**         | GPT-4 Turbo, Mistral 7B Instruct                   |
| **Data**           | ~90k research abstracts from ACL Anthology & arXiv |

---

> **Takeaway:** This study demonstrated how LLMs can be used not just for NLP tasks, but also as tools for *meta-research* — helping to classify and map the very limitations they themselves face.
{: .prompt-tip }
