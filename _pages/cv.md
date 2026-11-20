---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.Tech in Artificial Intelligence, Indian Institute of Science, Bengaluru, 2023–2025 (CGPA 8.3/10)
* B.Tech in Electrical & Electronics Engineering, Maharaja Agrasen Institute of Technology, Delhi, 2016–2020

Work experience
======
* Jan – Jul 2026: AI Engineer (intern)
  * LatentForce Intelligence
  * CodeWiki: LLM and agent pipeline for hierarchical repository documentation, consumed by coding agents through RAG and MCP
  * Knowledge graphs from dependency graphs; RAG-based QA benchmark against DeepWiki

* Aug – Nov 2025: AI Research Scientist
  * Mobius by Gaian
  * OCR-based document parsing (PDF to HTML, Markdown, JSON)
  * Entity datasets with BERT-based NER, Wikipedia entity linking, grammar-based and LLM ontology extraction

* Aug 2024 – Jul 2025: Research
  * Indian Institute of Science
  * Linear denoisers (bilateral filtering, non-local means) for image restoration; ICML 2026 paper; contribution to deepinv

* Aug 2020 – Sep 2022: Electrical Design Engineer
  * Tasa Micro SPM, Faridabad
  * Plant electrical design; electrical commissioning at the Ordnance Factory, Ambernath

Skills
======
* Generative AI: agentic workflows, LangGraph, LangChain, Google ADK, RAG, Qdrant, ChromaDB, prompt engineering, instruction tuning, lm-evaluation-harness
* Machine learning: PyTorch, JAX, TensorFlow, scikit-learn, Hugging Face Transformers, OpenCV, spaCy
* MLOps and backend: FastAPI, FastMCP, Docker, AWS, Airflow, MLflow, Kubeflow, DVC
* Languages: Python, MATLAB, C, SQL

Awards
======
* All India Rank 33, GATE 2023 (Electrical Engineering)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Open source
======
* Contributor to [deepinv](https://github.com/deepinv/deepinv), a PyTorch library for inverse problems in imaging
