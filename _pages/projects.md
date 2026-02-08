---
permalink: /projects/
title: "Projects"
excerpt: "Selected projects and research work"
author_profile: true
---

## Projects

**Regime-Switching Factor ETF Allocator**  
Technologies: Python, HMM, Random Forest, cuML (GPU), PyTorch, Streamlit  
[GitHub Repository](https://github.com/GaganVM/regime_factor_allocator)  
- Production-ready regime-switching factor ETF allocator using Hidden Markov Models (HMM), supervised learning, and threshold baselines
- Achieved **13.1% CAGR** with **1.18 Sharpe ratio** using GPU-accelerated supervised learning model
- Built with walk-forward testing, realistic transaction costs, GPU acceleration, and bootstrap uncertainty quantification
- Implemented three regime detection methods: threshold rules, Gaussian HMM, and Random Forest (GPU-accelerated)
- Features include regime-conditioned portfolio allocation, monthly rebalancing, and comprehensive backtesting framework

**PaperPal: AI-Powered Research Assistant**  
Technologies: Go, Gin, gRPC, FAISS, LangChain, Next.js  
- Engineered academic QA backend, doubling PDF throughput and cutting latency by **40%**
- Implemented LangChain RAG agent with **85% top-3 recall** and Next.js frontend

**Insider Threat Detection**  
Technologies: SeqGAN, LSTM, Multi-Head Attention, PyTorch, PostgreSQL  
- Enabled proactive insider-threat detection with SeqGAN+PostgreSQL, rebalancing **3 threat classes**
- Trained LSTM with multi-head attention for sequential classification, achieving **80% accuracy**
