# Awesome Multilingual LLM Literature Analysis

This repository serves as a curated collection of research papers, datasets, software tools, and learning materials centered on Evaluating Multilingual Reliability of Large Language Models in Scientific Literature Analysis. The goal of this project is to organize current advancements in cross-lingual transfer, multilingual pre-training, and evaluation benchmarks for under-represented languages. Researchers and developers can use this repository as a comprehensive reference guide to navigate the rapidly growing literature in multilingual natural language processing.

---

## Table of Contents
* [Topic Overview](#topic-overview)
* [AI-Assisted Research Paper](#ai-assisted-research-paper)
* [Citation Integrity Audit](#citation-integrity-audit)
* [Curated Research Papers](#curated-research-papers)
* [Datasets](#datasets)
* [Tools and Libraries](#tools-and-libraries)
* [GitHub Implementations](#github-implementations)
* [Tutorials and Learning Resources](#tutorials-and-learning-resources)
* [License](#license)

---

## Topic Overview
Multilingual Large Language Models (LLMs) have transformed natural language processing by enabling a single architecture to understand, generate, and reason across hundreds of human languages. Despite remarkable capabilities in high-resource languages such as English and Mandarin, cross-lingual transfer efficiency remains an active research challenge. Core problems in this domain include cross-lingual vocabulary construction, catastrophic forgetting during secondary pre-training, language contamination, and alignment across diverse linguistic typologies.
---

## AI-Assisted Research Paper
* **Title:** *Evaluating Multilingual Reliability of Large Language Models in Scientific Literature Analysis*
* **Abstract / Description:** This paper presents a systematic review of contemporary strategies for multilingual pre-training, cross-lingual alignment mechanisms, and evaluation paradigms across low-resource language regimes.
* **Repository Link:** [View Paper / Manuscript Document](AI_Assisted_Research_Paper) 
---

## Citation Integrity Audit
All references and research claims listed in the AI assisted Research Paper have been cross-checked against primary sources, original author releases, and verified database indexes (e.g., arXiv, ACL Anthology). 

* **Audit Report:** [View Citation Integrity Audit Report](citation-audit/citation_integrity_audit.pdf) 
---

## Curated Research Papers

### 1. Survey / Review Papers

1. **A Survey of Multilingual Large Language Models**  
   DOI: `10.1016/j.patter.2024.101118`

2. **A Survey on Multilingual Large Language Models: Corpora, Alignment, and Bias**  
   DOI: `10.1007/s11704-024-40579-4`

3. **Multilingual Large Language Models: A Systematic Survey**  
   DOI: `10.48550/arXiv.2411.11072`

4. **Multilingual Large Language Model: A Survey of Resources, Taxonomy and Frontiers**  
   DOI: `10.48550/arXiv.2404.04925`

5. **Large Language Models Hallucination: A Comprehensive Survey**  
   DOI: `10.1016/j.cosrev.2026.100970`

6. **Hallucination to Truth: A Review of Fact-Checking and Factuality Evaluation in Large Language Models**  
   DOI: `10.1007/s10462-025-11454-w`

### 2. Foundational Papers

1. **XTREME: A Massively Multilingual Multi-task Benchmark for Evaluating Cross-lingual Generalization**  
   DOI: `10.48550/arXiv.2003.11080`

2. **XTREME-R: Towards More Challenging and Nuanced Multilingual Evaluation**  
   DOI: `10.18653/v1/2021.emnlp-main.802`

3. **No Language Left Behind: Scaling Human-Centered Machine Translation**  
   DOI: `10.48550/arXiv.2207.04672`

4. **SelfCheckGPT: Zero-Resource Black-Box Hallucination Detection for Generative Large Language Models**  
   DOI: `10.18653/v1/2023.emnlp-main.557`

5. **The FLORES-101 Evaluation Benchmark for Low-Resource and Multilingual Machine Translation**  
   DOI: `10.1162/tacl_a_00474`

### 3. Methods / Algorithms

1. **MlingConf: A Comprehensive Study of Multilingual Confidence Estimation on Large Language Models**  
   DOI: `10.18653/v1/2025.findings-acl.129`

2. **CrossIn: An Efficient Instruction Tuning Approach for Cross-Lingual Knowledge Alignment**  
   DOI: `10.48550/arXiv.2404.11932`

3. **Improving Cross-Lingual Factual Recall via Consistency-Driven Reinforcement Learning (PolyFact)**  
   DOI: `10.48550/arXiv.2606.06586`

4. **ECLeKTic: A Novel Challenge Set for Evaluation of Cross-Lingual Knowledge Transfer**  
   DOI: `10.48550/arXiv.2502.21228`

5. **Inference-Time Steering for Cross-Lingual Factual Consistency in LLMs**  
   DOI: `10.48550/arXiv.2607.19243`

### 4. Applications (Scientific Literature Specific)

1. **Reducing Hallucinations in LLM-based Scientific Literature Analysis Using Peer Context Outlier Detection**  
   DOI: `10.48550/arXiv.2604.01461`

2. **ArxEval: Evaluating Retrieval and Generation in Language Models for Scientific Literature**  
   DOI: `10.48550/arXiv.2501.10483`

3. **Cross-lingual Extreme Summarization of Scholarly Documents (X-SciTLDR)**  
   DOI: `10.1007/s00799-023-00373-2`

4. **Challenges in Guardrailing Large Language Models for Science**  
   DOI: `10.48550/arXiv.2411.08181`

---

# Datasets

| Dataset | Source | Description | Use | Link |
|---|---|---|---|---|
| **FLORES-200 / FLORES+** | Meta AI | Multilingual translation benchmark covering approximately 200 languages. | Evaluates multilingual and cross-lingual machine translation. | [Hugging Face](https://huggingface.co/datasets/openlanguagedata/flores_plus) |
| **Belebele** | Meta AI | Multilingual reading comprehension dataset covering 122 languages. | Evaluates multilingual reading comprehension and language understanding. | [Hugging Face](https://huggingface.co/datasets/facebook/belebele) |
| **SEAHORSE** | Google Research | Multilingual dataset for evaluating generated summaries. | Evaluates multilingual summarization quality and factuality. | [Paper](https://arxiv.org/pdf/2305.13194) |

---

# Tools

| Tool | Purpose | Link |
|---|---|---|
| **mT5** | Multilingual text-to-text model supporting 101 languages. | [Hugging Face](https://huggingface.co/docs/transformers/en/model_doc/mt5) |
| **XLM-RoBERTa** | Multilingual language model trained across 100 languages for cross-lingual NLP tasks. | [Hugging Face](https://huggingface.co/docs/transformers/en/model_doc/xlm-roberta) |
| **NLLB-200** | Multilingual translation model supporting direct translation across 200 languages. | [Meta AI](https://ai.meta.com/research/no-language-left-behind/) |
| **SelfCheckGPT** | Black-box method for detecting hallucinations in LLM-generated text. | [GitHub](https://github.com/potsawee/selfcheckgpt) |
| **spaCy** | NLP library for text processing, linguistic analysis, and multilingual language tasks. | [GitHub](https://github.com/explosion/spacy) |
---

## GitHub Implementations

* https://github.com/google-research/xtreme - Official XTREME benchmark implementation and evaluation baselines for cross-lingual language understanding.
* https://github.com/potsawee/selfcheckgpt - Implements SelfCheckGPT for black-box hallucination detection in LLM-generated text.
* https://github.com/vibrantlabsai/ragas - RAG evaluation framework for measuring retrieval and generation quality.
* https://github.com/EdinburghNLP/awesome-hallucination-detection - Curated collection of hallucination detection papers, metrics, and datasets.
* https://github.com/tjunlp-lab/Awesome-Multilingual-LLMs-Papers - Organized collection of multilingual LLM papers and resources by research topic.
---

## Tutorials

* https://huggingface.co/blog/dhuynh95/automatic-hallucination-detection - Hands-on guide to using SelfCheckGPT with NLI models for hallucination detection.
* https://research.google/blog/xtreme-a-massively-multilingual-multi-task-benchmark-for-evaluating-cross-lingual-generalization/ - Overview of the XTREME benchmark for evaluating cross-lingual generalization.
* https://ai.meta.com/blog/nllb-200-high-quality-machine-translation/ - Introduction to NLLB-200 and its multilingual machine translation capabilities.
* https://gist.github.com/donbr/a6e0fd539c1288b5ab3d88bb42f75a40 - Practical walkthrough for evaluating RAG systems using metrics such as faithfulness and consistency.
* https://huggingface.co/datasets/facebook/belebele - Dataset resource for exploring and using the Belebele multilingual reading-comprehension benchmark.
---
