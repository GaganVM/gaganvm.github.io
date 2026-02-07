---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Welcome! I'm a Master's student in Computer Science at UC San Diego (Sep. 2024 – Mar. 2026), working on machine learning and deep learning research. My research interests include vision-language models, music intelligence, conversational AI, and their applications in recommendation systems.

I completed my Bachelor of Technology in Electronics Engineering from the Indian Institute of Technology (BHU) Varanasi (Nov. 2020 – Jun. 2024) with a GPA of 3.98/4.00.

## Education

**University of California San Diego**  
Master of Science in Computer Science (GPA: 3.95/4.00)  
San Diego, CA | Sep. 2024 – Mar. 2026

**Indian Institute of Technology (BHU) Varanasi**  
Bachelor of Technology in Electronics Engineering (GPA: 3.98/4.00)  
Varanasi, UP | Nov. 2020 – Jun. 2024

## Experience

**Machine Learning Intern** | McAuley Lab, UC San Diego  
San Diego, CA | Mar. 2025 – Present  
- Authored two music-intelligence benchmarks (**WildScore** - EMNLP 2025 accepted, **MusiCRS** - ICASSP submission in prep, involving **482 audio-query cases**) for evaluating vision/audio reasoning in MLLMs
- Developed an evaluation framework for LLM-based topic modeling and an AI-Agentic Benchmark, applying GRPO for variational inference

**Machine Learning Intern** | San Diego Supercomputer Center  
San Diego, CA | Jul. 2025 – Sep. 2025  
- Developed and optimized automated EEG preprocessing pipelines for **22 NEMAR datasets**, enhancing data quality and processing efficiency using MATLAB and PyTorch

**Machine Learning Intern** | Cosman Lab, UC San Diego  
San Diego, CA | Oct. 2024 – Jul. 2025  
- Developed a saliency-guided Vision Transformer codec in PyTorch, achieving **15-20% improvement** in perceptual quality metrics
- Containerized workflows with Docker/Kubernetes, achieving **50.6% preference rate** in human validation (research findings for CVPR 2026)

**Deep Learning Intern** | INRIA Morpheo  
Grenoble, France | May 2023 – Jul. 2023  
- Attained **85% accuracy** in General Movement Assessment
- Revamped Python pipeline (NumPy, OpenCV, Open3D, PyTorch) for SMIL extraction, reducing processing time by **10%**

## Selected Publications

<div class="publication-card">
  <img src="{{ '/images/WS_GRPO.png' | prepend: site.baseurl }}" alt="WS-GRPO" class="publication-card__image">
  <div class="publication-card__content">
    <p class="publication-card__title">
      <strong>WS-GRPO: Weakly-Supervised Group-Relative Policy Optimization</strong>
    </p>
    <p class="publication-card__authors">
      <strong>Gagan Mundada</strong> and co-authors
    </p>
    <p class="publication-card__venue">
      Under review at ICLR 2026
    </p>
  </div>
</div>

<div class="publication-card">
  <img src="{{ '/images/survey.png' | prepend: site.baseurl }}" alt="RLVR Survey" class="publication-card__image">
  <div class="publication-card__content">
    <p class="publication-card__title">
      <strong>From Verifiable Rewards to Policy Learning: A Survey of Reinforcement Learning from Verifiable Rewards</strong>
    </p>
    <p class="publication-card__authors">
      <strong>Gagan Mundada</strong> and co-authors
    </p>
    <p class="publication-card__venue">
      Under review at EACL
    </p>
  </div>
</div>

<div class="publication-card">
  <img src="{{ '/images/wildscore.png' | prepend: site.baseurl }}" alt="WildScore" class="publication-card__image">
  <div class="publication-card__content">
    <p class="publication-card__title">
      <strong>WildScore: Benchmarking MLLMs in-the-Wild Symbolic Music Reasoning</strong>
    </p>
    <p class="publication-card__authors">
      <strong>Gagan Mundada</strong> and co-authors
    </p>
    <p class="publication-card__venue">
      EMNLP 2025 - Main Conference
    </p>
  </div>
</div>

<div class="publication-card">
  <img src="{{ '/images/musiccrs.png' | prepend: site.baseurl }}" alt="MusiCRS" class="publication-card__image">
  <div class="publication-card__content">
    <p class="publication-card__title">
      <strong>MusiCRS: Benchmarking Music-Centric Conversational Recommendation</strong>
    </p>
    <p class="publication-card__authors">
      <strong>Gagan Mundada</strong> and co-authors
    </p>
    <p class="publication-card__venue">
      IEEE ICASSP 2026
    </p>
  </div>
</div>

<div class="publication-card">
  <img src="{{ '/images/SINR.png' | prepend: site.baseurl }}" alt="SINR-Delay" class="publication-card__image">
  <div class="publication-card__content">
    <p class="publication-card__title">
      <strong>SINR-Delay Constrained Node Localization in RIS-Assisted Time-Varying IoT Networks Using ML Frameworks</strong>
    </p>
    <p class="publication-card__authors">
      <strong>Gagan Mundada</strong> and co-authors
    </p>
    <p class="publication-card__venue">
      IEEE TNSM, 2025
    </p>
  </div>
</div>

<div class="publication-card">
  <img src="{{ '/images/cholangiocarcinoma.png' | prepend: site.baseurl }}" alt="Hyperspectral Imaging" class="publication-card__image">
  <div class="publication-card__content">
    <p class="publication-card__title">
      <strong>Deep learning-based hyperspectral microscopic imaging for cholangiocarcinoma detection and classification</strong>
    </p>
    <p class="publication-card__authors">
      <strong>Gagan Mundada</strong> and co-authors
    </p>
    <p class="publication-card__venue">
      Optics Continuum
    </p>
  </div>
</div>

## Projects

**PaperPal: AI-Powered Research Assistant**  
Technologies: Go, Gin, gRPC, FAISS, LangChain, Next.js  
- Engineered academic QA backend, doubling PDF throughput and cutting latency by **40%**
- Implemented LangChain RAG agent with **85% top-3 recall** and Next.js frontend

**Insider Threat Detection**  
Technologies: SeqGAN, LSTM, Multi-Head Attention, PyTorch, PostgreSQL  
- Enabled proactive insider-threat detection with SeqGAN+PostgreSQL, rebalancing **3 threat classes**
- Trained LSTM with multi-head attention for sequential classification, achieving **80% accuracy**
