---
layout: home
---

# About Me

I am a Computer Science Ph.D. candidate at the University of Illinois at Urbana-Champaign (UIUC), advised by Prof. Arindam Banerjee. I also obtained my M.S. in Computer Science from UIUC and a B.S. in Computer Engineering from the ZJU-UIUC Institute.

My research interests lie broadly in generative AI, with a focus on diffusion and flow-matching models for fast, high-fidelity text-to-image generation and data-efficient image super-resolution.

I am also interested in large language models and retrieval-augmented generation (RAG). Recently, as a Machine Learning Research Intern at GE HealthCare, I worked on model-agnostic frameworks for temporal EHR modeling and RAG-style agents to improve downstream prediction performance.

Here is my CV.

# Publications

- **MSP-SR: Multi-Stage Probabilistic Generative Super-Resolution with Scarce High-Resolution Data**,  
  *Ruike Zhu*, Michael C. Weston, Arindam Banerjee, UAI 2025.  
  We propose MSP-SR, a three-stage generative super-resolution framework that transfers knowledge from natural images to the medical domain using ControlNet-style conditioning. Under few-shot settings, MSP-SR significantly improves PSNR and LPIPS on multiple medical datasets, including a 32.2% PSNR gain and 46.0% lower LPIPS on OASIS.

- **Beyond Parameters: Exploring Virtual Logic Depth for Scaling Laws**,  
  *Ruike Zhu*, submitted to ICLR 2026.  
  This work systematically studies parameter-reuse patterns in large language models, introducing a cyclic repetition scheme that substantially improves reasoning performance, with up to 52% accuracy gains on reasoning tasks and more than 100% improvement on the AIME benchmark for fixed parameter budgets.

- **Generative Graph Dictionary Learning**,  
  Zhiceng Zeng, *Ruike Zhu*, Yizhou Xia, Hao Zeng, Hanghang Tong, ICML 2023.  
  We developed a generative framework for learning graph dictionaries that capture latent structural patterns, enabling more expressive and compact representations for downstream graph learning tasks.

- **Weakly Supervised Two-Stage Training Scheme for Deep Video Fight Detection Model**,  
  *Ruike Zhu*, Zixu Qi, Zhenyang Fu, Wei Chai, Volodymyr Kindratenko, ICTAI 2022.  
  We designed a weakly supervised two-stage pipeline for violence detection in videos, combining coarse video-level supervision with refined frame-level modeling to improve robustness under limited labels.

## Experience

### Machine Learning Research Intern, GE HealthCare  
*May 2025 – Aug 2025*

- Developed a model-agnostic framework to predict patient mortality from temporal EHR sequences and historical ICD codes on a highly imbalanced dataset.
- Designed an AI-driven agent to optimize a retrieval-augmented generation (RAG) pipeline that retrieves similar patient cases in addition to external medical knowledge.
- Applied reinforcement learning to refine query generation with a custom reward based on prediction accuracy, achieving a 34% AUROC improvement over baseline models.
