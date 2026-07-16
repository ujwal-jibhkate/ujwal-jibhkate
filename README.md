# Ujwal Jibhkate

AI/ML Engineer working across agentic systems, applied ML, and biomedical research.

[LinkedIn](https://www.linkedin.com/in/ujwal-jibhkate/) · [Portfolio](https://ujwal-jibhkate.github.io/) · [Email](mailto:ujwaljibhkate06@gmail.com)

---

## About

M.S. Data Science, Indiana University Bloomington (GPA 3.86). Two years at IBM building GenAI applications on Azure OpenAI and IBM Watsonx. Currently a Research Assistant at the IU School of Medicine's Shen Lab, working on AI-driven drug repurposing for pediatric brain tumors (DIPG/DMG).

I split my time between production-oriented agent systems and research - mostly retrieval-augmented generation, representation learning, and applying ML to biomedical problems.

## Projects

**[AESOP](https://aesop.live)** - Agentic Evidence Synthesis & Orchestration Platform
A multi-agent system for biomedical literature review, built with LangGraph orchestration and a corrective RAG pipeline. Backed by a hybrid Redis/PostgreSQL memory layer for persistent conversation history. Built with Saksham Dahake; I own the backend architecture, retrieval, and evaluation framework.
`LangGraph` `Corrective RAG` `AWS Bedrock` `pgvector` `FastAPI` `Redis` `PostgreSQL`

**[Fraud Risk Scoring](https://live-fraud-model.vercel.app)** - Tabular ML with explainability
A LightGBM fraud model trained on the IEEE-CIS dataset (590K transactions), with a SHAP-to-LLM layer that turns per-transaction feature attributions into plain-language explanations.
`LightGBM` `SHAP` `LLM explainability`

**[Multi-Modal Recommender](https://live-movie-recs.vercel.app)** - Cold-start recommendation
A movie recommender over 44K titles that fuses Sentence-BERT text and CLIP visual embeddings so new items are recommendable without interaction history, with a two-stage FAISS retrieval pipeline and MMR re-ranking for diversity.
`Sentence-BERT` `CLIP` `FAISS` `Contrastive learning`

**[Radiology Report Generation](https://radiology-ai-demo.vercel.app)** - Chest X-ray AI
A system for generating clinical-style reports from chest X-ray images, built with an emphasis on auditability.
`PyTorch` `FastAPI` `Docker`

**Self-Supervised Learning for Chest X-rays** - Ongoing research
Comparing JEPA and MAE pretraining on NIH ChestX-ray14 (~120K images), currently in a rigorous pre-publication audit for leakage, statistical validity, and fair baseline comparison.
`JEPA` `MAE` `Self-supervised learning`

**Drug Repurposing Research** - IU School of Medicine, Shen Lab
Two research tracks: pathway-reversal scoring of ~12K compounds against a DIPG disease signature, and a drug-response model built on harmonized efficacy data across multiple pan-cancer and DIPG-specific screens.
`GSEA` `Drug response modeling` `JEPA`

## Stack

**Languages & ML** - Python · PyTorch · scikit-learn · Hugging Face
**LLM / Agents** - LangChain · LangGraph · AWS Bedrock · Azure OpenAI · IBM Watsonx
**Infra** - FastAPI · Docker · Redis · PostgreSQL · GCP

---

Open to AI/ML engineering roles.
