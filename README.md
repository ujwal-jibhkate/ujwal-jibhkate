<div align="center">

<!-- WIRED-style thick top bar -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:000000,100:000000&height=14"/>

<br/>

<!-- Magazine masthead -->
<sub>ISSUE NO. 2024 &nbsp;·&nbsp; ENGINEERING &amp; RESEARCH EDITION</sub>

<br/><br/>

<!-- Massive editorial title -->
# THE AI ENGINEER<br/>HUNTING A CURE

<br/>

### *How Ujwal Jibhkate went from building enterprise LLMs at IBM<br/>to using machine learning to fight pediatric brain cancer*

<br/>

<img width="60%" src="https://capsule-render.vercel.app/api?type=rect&color=0:000000,100:000000&height=4"/>

<br/>

<!-- Byline -->
**by Ujwal Jibhkate** &nbsp;·&nbsp; M.S. Data Science, Indiana University &nbsp;·&nbsp; GPA 3.844

<br/>

<!-- Social links styled as magazine section tabs -->
<a href="https://www.linkedin.com/in/ujwal-jibhkate/">
  <img src="https://img.shields.io/badge/LINKEDIN-000000?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>
&nbsp;
<a href="https://www.ujwal.technology/">
  <img src="https://img.shields.io/badge/PORTFOLIO-000000?style=for-the-badge&logo=firefox-browser&logoColor=white"/>
</a>
&nbsp;
<a href="mailto:ujwaljibhkate06@gmail.com">
  <img src="https://img.shields.io/badge/EMAIL-000000?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

<br/><br/>

![Open to Work](https://img.shields.io/badge/%E2%96%BA%20OPEN%20TO%20AI%2FML%20ENGINEERING%20ROLES-000000?style=flat-square&labelColor=000000&color=000000)

<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:000000,100:000000&height=4"/>

</div>

---

<br/>

> *"The machine doesn't care about the patient. That's why the engineer has to."*

<br/>

At Indiana University's Shen Laboratory, **Ujwal Jibhkate** is doing something most engineers never attempt: pointing production-grade AI infrastructure directly at one of medicine's hardest problems. DIPG — Diffuse Intrinsic Pontine Glioma — is a pediatric brain tumor with a median survival of under a year and essentially no approved treatments. His weapon of choice is a heterogeneous knowledge graph backed by graph neural networks, cross-referencing drug sensitivity data from DepMap and genetic perturbation profiles from LINCS L1000, hunting for FDA-approved compounds that might be repurposed for children who've run out of options.

Before this, he was at **IBM** for two years, building enterprise LLM applications for UK clients using Azure OpenAI and IBM Watsonx — the kind of work that teaches you how fast AI systems break in production, and how to build ones that don't.

This is his file.

<br/>

---

<br/>

## COVER STORY &nbsp;·&nbsp; The Work

<br/>

### ◼ &nbsp; AESOP
#### *Agentic Evidence Synthesis & Orchestration Platform*
###### Research Preview · Built with Saksham Dahake

The scientific literature problem is simple to state and brutal in practice: there are more relevant papers than any researcher can read. AESOP is Ujwal's answer — a multi-agent system that reads, retrieves, and synthesizes biomedical literature automatically, built on LangGraph orchestration with Corrective RAG for self-healing retrieval. Under the hood: a hybrid Redis + PostgreSQL memory layer that gives the system persistent, conversation-aware context across sessions. Full LangSmith tracing means nothing runs unaudited.

`LangGraph` &nbsp;·&nbsp; `Corrective RAG` &nbsp;·&nbsp; `Redis` &nbsp;·&nbsp; `PostgreSQL` &nbsp;·&nbsp; `FastAPI` &nbsp;·&nbsp; `LangSmith`

<br/>

### ◼ &nbsp; DRUG REPURPOSING KG
#### *Heterogeneous Knowledge Graph for DIPG Treatment*
###### Active Research · Shen Laboratory

GNN-powered knowledge graph over DepMap and LINCS L1000 biological datasets, mapping FDA-approved drugs to pediatric DIPG targets. The goal: find existing drugs that might save lives, faster than traditional discovery timelines allow.

`PyTorch Geometric` &nbsp;·&nbsp; `GNN` &nbsp;·&nbsp; `DepMap` &nbsp;·&nbsp; `LINCS L1000`

<br/>

### ◼ &nbsp; NANOPORE PIPELINE
#### *HIV Drug Resistance · Real-Time · Edge Deployed*
###### Oxford Nanopore · NVIDIA Jetson AGX Orin

Real-time mutation detection for nanopore sequencing data, running on NVIDIA Jetson hardware at the edge. Processes thousands of reads in **21 seconds**. Wilson confidence intervals. FDR correction. No compromises.

`ONT` &nbsp;·&nbsp; `NVIDIA Jetson` &nbsp;·&nbsp; `FASTQ/BAM` &nbsp;·&nbsp; `Wilson CI` &nbsp;·&nbsp; `FDR`

<br/>

### ◼ &nbsp; AUDITABLE RADIOLOGY AI
#### *Clinical Reports from Chest X-Rays*

Full-stack medical AI with fairness constraints baked in. Because in healthcare, "it usually works" isn't good enough.

`PyTorch` &nbsp;·&nbsp; `Docker` &nbsp;·&nbsp; `FastAPI`

<br/>

### ◼ &nbsp; MULTI-MODAL RECOMMENDER
#### *Solving the Cold-Start Problem*

Unified CLIP + S-BERT embedding space with two-stage FAISS retrieval. Diverse, high-recall recommendations from day one.

`CLIP` &nbsp;·&nbsp; `S-BERT` &nbsp;·&nbsp; `FAISS`

<br/>

---

<br/>

## TECH SECTION &nbsp;·&nbsp; The Stack

<br/>

**ML / AI CORE**

![Python](https://img.shields.io/badge/Python-000000?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-000000?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-000000?style=flat-square&logo=huggingface&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-000000?style=flat-square&logo=scikit-learn&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-000000?style=flat-square&logo=langchain&logoColor=white)

**LLM PLATFORMS**

![Azure OpenAI](https://img.shields.io/badge/Azure_OpenAI-000000?style=flat-square&logo=microsoft-azure&logoColor=white)
![IBM Watsonx](https://img.shields.io/badge/IBM_Watsonx-000000?style=flat-square&logo=ibm&logoColor=white)
![AWS Bedrock](https://img.shields.io/badge/AWS_Bedrock-000000?style=flat-square&logo=amazonaws&logoColor=white)

**INFRASTRUCTURE**

![FastAPI](https://img.shields.io/badge/FastAPI-000000?style=flat-square&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-000000?style=flat-square&logo=docker&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-000000?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-000000?style=flat-square&logo=postgresql&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-000000?style=flat-square&logo=google-cloud&logoColor=white)

<br/>

---

<br/>

## DATA &nbsp;·&nbsp; Activity

<div align="center">

<img height="175em" src="https://github-readme-stats.vercel.app/api?username=ujwal-jibhkate&show_icons=true&theme=default&include_all_commits=true&count_private=true&hide_border=false&title_color=000000&icon_color=000000&border_color=000000"/>
&nbsp;
<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ujwal-jibhkate&layout=compact&theme=default&hide_border=false&title_color=000000&border_color=000000"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com?user=ujwal-jibhkate&theme=default&hide_border=false&ring=000000&fire=000000&currStreakLabel=000000"/>

</div>

<br/>

---

<br/>

## LAST PAGE &nbsp;·&nbsp; Contact

<br/>

*Ujwal is actively seeking AI/ML Engineering roles. If you're building something that matters — in biomedical AI, LLM infrastructure, or applied ML at scale — he wants to hear from it.*

**→** ujwaljibhkate06@gmail.com &nbsp;·&nbsp; [linkedin.com/in/ujwal-jibhkate](https://www.linkedin.com/in/ujwal-jibhkate/) &nbsp;·&nbsp; [ujwal.technology](https://www.ujwal.technology/)

<br/>

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:000000,100:000000&height=4"/>

<sub><b>ISSUE NO. 2024 &nbsp;·&nbsp; ALL RIGHTS RESERVED &nbsp;·&nbsp; UJWAL JIBHKATE</b></sub>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:000000,100:000000&height=14"/>

</div>
