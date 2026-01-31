# Priyadip Sau

**M.Tech in Artificial Intelligence** | Indian Institute of Technology Jodhpur  
*Research Focus: Parameter-Efficient Fine-Tuning, Large Language Models, Multi-Modal Representation Learning*

[![Website](https://img.shields.io/badge/Portfolio-priyadipsau.in-0A66C2?style=flat-square)](https://priyadipsau.in/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-priyadip--cs-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/priyadip-cs)
[![Google Scholar](https://img.shields.io/badge/Scholar-Profile-4285F4?style=flat-square&logo=googlescholar)](https://scholar.google.com/)
[![Twitter](https://img.shields.io/badge/X-@PriyadipSau-000000?style=flat-square&logo=x)](https://x.com/PriyadipSau)

---

## About

I am a graduate researcher at IIT Jodhpur specializing in efficient adaptation methods for large language models and multi-modal representation learning. My work sits at the intersection of **natural language understanding**, **parameter-efficient fine-tuning (PEFT)**, and **scalable ML systems**—with a particular emphasis on persona alignment, quantization-aware training, and contrastive learning frameworks.

Prior to my M.Tech, I completed my M.Sc. in Mathematics, which provides a rigorous foundation in optimization theory, linear algebra, and statistical inference that informs my approach to deep learning research.

**Current Interests:**
- Low-rank adaptation (LoRA/QLoRA) for LLM alignment and behavioral steering
- Multi-modal fusion architectures for large-scale clustering
- Efficient inference pipelines and serverless GPU deployment
- Evaluation frameworks for generative models (perplexity, similarity metrics)

---

## Selected Projects

### Sherlock-LLM: Persona Alignment via Parameter-Efficient Fine-Tuning
*Fine-tuning Qwen-2.5 for rigorous persona adoption using QLoRA (4-bit NF4 quantization)*

- Implemented low-rank adaptation (r=16) on Qwen-2.5-7B with BitsAndBytes quantization
- Designed dual-metric evaluation: Conditional Perplexity & Jaccard Similarity for persona steering
- Achieved perplexity reduction from 45.31 → 7.52; deployed via Modal serverless API

`Python` `PyTorch` `Hugging Face (PEFT, TRL)` `QLoRA` `BitsAndBytes` `Modal` `FastAPI`

---

### Advanced Multi-Modal Customer Segmentation
*End-to-end deep learning pipeline fusing demographic, textual (S-BERT), and behavioral (LSTM) modalities*

- Engineered multi-modal encoder with dual-loss training (Contrastive + Clustering)
- Processed 1.36M+ customer embeddings with GPU-accelerated HDBSCAN
- Achieved 0.901 Silhouette Score on large-scale segmentation benchmark

`Python` `PyTorch` `SentenceTransformers` `LSTM` `cuML (RAPIDS)` `HDBSCAN`

---

### Rice Dataset Classification
*ResNet-18 trained from scratch for fine-grained visual classification*

- Achieved 99.87% accuracy on 5-class rice species classification after 20 epochs
- Executed on Kaggle GPU runtime with efficient data augmentation pipeline

`Python` `PyTorch` `Pillow`

---

## Technical Proficiencies

| Domain | Tools & Frameworks |
|--------|-------------------|
| **Deep Learning** | PyTorch, Hugging Face (Transformers, TRL, Accelerate, PEFT), SentenceTransformers |
| **LLM & GenAI** | QLoRA, LoRA, BitsAndBytes, Qwen-2.5, Llama-3.1, Transformer Architectures |
| **ML & Optimization** | Scikit-learn, RAPIDS (cuML), HDBSCAN, PCA, UMAP, Convex Optimization |
| **Infrastructure** | Modal (Serverless GPU), FastAPI, Docker, Git, Linux |
| **Languages** | Python, C/C++, SQL, LaTeX |

---

## Education

| Degree | Institution | Performance | Year |
|--------|-------------|-------------|------|
| M.Tech (Artificial Intelligence) | IIT Jodhpur | 9.5 CGPA (Sem-1) | 2025–2027 |
| M.Sc. (Mathematics) | University of North Bengal | 6.46 CGPA | 2021–2023 |
| B.Sc. (Mathematics) | Vidyasagar University | 8.62 CGPA | 2018–2021 |

**GATE Data Science & AI 2025:** AIR 226 (Score: 717)

---

## Experience

**Teaching Assistant** — *IIT Jodhpur*  
Introduction to Machine Learning (July 2025 – December 2025)

---

## GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=priyadip&show_icons=true&theme=github_dark&hide_border=true&count_private=true" alt="GitHub Stats" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=priyadip&layout=compact&theme=github_dark&hide_border=true" alt="Top Languages" height="165"/>
</p>

---

## Contact

For research collaborations, discussions on LLM alignment, or PEFT methodologies:

- **Email:** [m25csa023@iitj.ac.in](mailto:m25csa023@iitj.ac.in) | [saupriyadip571@gmail.com](mailto:saupriyadip571@gmail.com)
- **Portfolio:** [priyadipsau.in](https://priyadipsau.in/)

---

<p align="center">
  <i>"The goal is not to build models that perform well, but models that generalize wisely."</i>
</p>

<!--
**priyadip/priyadip** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
