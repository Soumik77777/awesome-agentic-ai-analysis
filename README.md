# Awesome Single-LLM Versus Multi-Agent Debate Systems for Scientific Hypothesis Generation

A curated collection of research papers, datasets, tools, GitHub implementations, and learning resources related to **Single-LLM Versus Multi-Agent Debate Systems for Scientific Hypothesis Generation**.

This repository brings together verified scholarly literature and practical resources for studying how single-LLM systems and multi-agent debate systems can generate, critique, evaluate, and refine scientific hypotheses.

## Contents

- [Overview](#overview)
- [AI-Assisted Research Paper](#ai-assisted-research-paper)
- [Survey Papers](#survey-papers)
- [Foundational Papers](#foundational-papers)
- [Recent Research Papers](#recent-research-papers)
- [Datasets](#datasets)
- [Tools and Libraries](#tools-and-libraries)
- [GitHub Implementations](#github-implementations)
- [Tutorials](#tutorials)
- [Citation Integrity Audit](#citation-integrity-audit)
- [License](#license)

---

## Overview

Scientific hypothesis generation involves developing explanations or predictions that are sufficiently novel, plausible, and testable to motivate further investigation. Large language models (LLMs) have introduced new approaches to this process by enabling the synthesis of scientific literature, generation of candidate explanations, comparison of alternatives, and iterative refinement. Earlier computational approaches to scientific discovery and literature-based discovery provide important foundations for this development.

A central question is whether scientific hypothesis generation benefits more from a single LLM using structured reasoning, retrieval, and self-refinement, or from multiple LLM-based agents that independently generate, critique, rank, and evolve hypotheses. Single-LLM systems can perform iterative generation and refinement with lower coordination complexity, while multi-agent systems can introduce role specialization, independent reasoning paths, and adversarial critique.

However, additional agents do not automatically guarantee better results. Multi-agent debate can introduce correlated errors, sycophancy, agreement collapse, and additional computational cost. For scientific discovery, the quality of a hypothesis ultimately depends on factors such as novelty, validity, diversity, factual grounding, testability, and experimental verification. Recent systems therefore increasingly combine LLM agents with scientific literature, computational tools, experimental workflows, and human oversight.

This repository collects resources for understanding and evaluating these approaches, with particular emphasis on the comparison between single-LLM reasoning and multi-agent debate architectures.

---

## AI-Assisted Research Paper

### Single-LLM Versus Multi-Agent Debate Systems for Scientific Hypothesis Generation

**Description:**  
This paper reviews and compares single-LLM and multi-agent approaches to scientific hypothesis generation, focusing on scientific novelty, validity, diversity, factual grounding, computational cost, and experimental verifiability. It argues that neither architecture is inherently superior and discusses hybrid architectures combining single-model ideation with selective multi-agent critique, evidence retrieval, novelty assessment, and experimental prioritization.

[View AI-Assisted Research Paper](paper/Single-LLM_Versus_Multi-Agent_Debate_Systems_for_Scientific_Hypothesis_Generation_G11_MDE2026005.pdf)

---

## Survey Papers

- **Undiscovered Public Knowledge — Swanson (1986)**  
  Foundational work on literature-based discovery and identifying previously disconnected relationships across scientific knowledge.  
  [View in References](references/references.md#1-undiscovered-public-knowledge)

- **Scientific Discovery: Computational Explorations of the Creative Processes — Langley et al. (1987)**  
  Foundational work on computational approaches to scientific discovery and automated hypothesis formation.  
  [View in References](references/references.md#2-scientific-discovery-computational-explorations-of-the-creative-processes)

---

## Foundational Papers

- **Self-Refine: Iterative Refinement with Self-Feedback — Madaan et al. (2023)**  
  Introduces iterative generation, feedback, and refinement using a language model.  
  [View in References](references/references.md#8-self-refine-iterative-refinement-with-self-feedback)

- **Reflexion: Language Agents with Verbal Reinforcement Learning — Shinn et al. (2023)**  
  Introduces reflection and memory mechanisms for improving language-agent performance.  
  [View in References](references/references.md#9-reflexion-language-agents-with-verbal-reinforcement-learning)

- **Improving Factuality and Reasoning in Language Models through Multiagent Debate — Du et al. (2024)**  
  Studies whether multiple LLM agents debating their answers can improve reasoning and factuality.  
  [View in References](references/references.md#7-improving-factuality-and-reasoning-in-language-models-through-multiagent-debate)

---

## Recent Research Papers

- **Hypothesis Generation with Large Language Models — Zhou et al. (2024)**  
  Investigates LLM-based scientific hypothesis generation and iterative hypothesis updating.  
  [View in References](references/references.md#3-hypothesis-generation-with-large-language-models)

- **Large Language Models for Automated Open-domain Scientific Hypotheses Discovery — Yang et al. (2024)**  
  Studies automated open-domain scientific hypothesis discovery using LLMs.  
  [View in References](references/references.md#4-large-language-models-for-automated-open-domain-scientific-hypotheses-discovery)

- **Can LLMs Generate Novel Research Ideas? — Si et al. (2025)**  
  Evaluates the novelty and feasibility of LLM-generated research ideas against ideas generated by human researchers.  
  [View in References](references/references.md#5-can-llms-generate-novel-research-ideas-a-large-scale-human-study-with-100-nlp-researchers)

- **The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery — Lu et al. (2024)**  
  Presents an automated system covering research-idea generation, experimentation, analysis, and paper generation.  
  [View in References](references/references.md#17-the-ai-scientist-towards-fully-automated-open-ended-scientific-discovery)

- **Towards an AI Co-Scientist — Gottweis et al. (2025)**  
  Describes an AI system designed to support scientific reasoning, hypothesis generation, and research workflows.  
  [View in References](references/references.md#14-towards-an-ai-co-scientist)

- **Scientific Hypothesis Generation by Large Language Models: Laboratory Validation in Breast Cancer Treatment (2025)**  
  Connects LLM-generated hypotheses with laboratory validation in a biomedical setting.  
  [View in References](references/references.md#6-scientific-hypothesis-generation-by-large-language-models-laboratory-validation-in-breast-cancer-treatment)

For the complete curated collection, see [References](references/references.md).

---

## Datasets

The following datasets and benchmarks support hypothesis generation, evaluation, scientific-literature retrieval, and evidence gathering.

- **ResearchBench** — Benchmark for scientific discovery, including inspiration retrieval, hypothesis composition, and hypothesis ranking.  
  [View Dataset](datasets/datasets.md#1-researchbench)

- **HypoBench** — Benchmark designed to evaluate AI hypothesis-generation capabilities across multiple domains and datasets.  
  [View Dataset](datasets/datasets.md#2-hypobench)

- **S2ORC — Semantic Scholar Open Research Corpus** — Large-scale scientific literature corpus useful for retrieving scientific papers and evidence.  
  [View Dataset](datasets/datasets.md#3-s2orc--semantic-scholar-open-research-corpus)

- **OpenAlex** — Open scholarly index containing scientific works, authors, institutions, topics, and citation information.  
  [View Dataset](datasets/datasets.md#4-openalex)

[View Complete Dataset Collection](datasets/datasets.md)

---

## Tools and Libraries

- **LangChain** — Framework for developing LLM applications and agent-based workflows.
- **Microsoft AutoGen** — Framework for building and coordinating multi-agent applications.
- **LlamaIndex** — Framework for connecting LLMs with external data and implementing retrieval-augmented generation.
- **DSPy** — Framework for programming and optimizing modular LLM-based systems.
- **Hugging Face Transformers** — Library providing pretrained transformer models and tools for LLM development.

[View Tools and Libraries](tools/tools.md)

---

## GitHub Implementations

- **ResearchBench** — Implementation and evaluation toolkit for scientific discovery and hypothesis generation.
- **Hypothesis Generation with LLMs** — Implementations for LLM-based scientific hypothesis generation.
- **The AI Scientist** — End-to-end implementation for automated scientific discovery.
- **Open Coscientist** — Multi-agent implementation for scientific hypothesis generation and refinement.
- **AI Co-Scientist** — Multi-agent implementation involving generation, reflection, ranking, and evolution of hypotheses.
- **Multi-Agent Debate System** — Implementation of structured debate between multiple LLM agents.
- **Open AI Co-Scientist** — Open-source implementation inspired by multi-agent scientific-discovery architectures.

[View Complete GitHub Implementations](implementations/github-repositories.md)

---

## Tutorials

- **LangChain Agents Documentation** — Introduction to building LLM-powered agents and tool-based workflows.
- **Microsoft AutoGen Documentation** — Practical guidance for creating and coordinating AI agents.
- **LlamaIndex RAG Guide** — Introduction to retrieval-augmented generation and connecting LLMs with external data.
- **Hugging Face LLM Course** — Covers transformer models, LLMs, datasets, inference, and fine-tuning.
- **DSPy Documentation** — Guidance for programming and optimizing modular LLM-based systems.

---

## Citation Integrity Audit

The original AI-assisted research paper contained 22 references. A citation-integrity audit was conducted to verify whether the cited publications existed and whether their bibliographic information and identifiers were accurate.

The audit examined publication existence, title, authors, year, venue, and identifiers such as DOI, ISBN, and arXiv IDs. The results showed that most audited references were valid, while some contained metadata or identifier issues. The audit demonstrates why AI-generated references must be independently verified before being included in a curated research collection.

[View Citation Integrity Audit](citation-audit/Citation_Integrity_Audit_MDE2026005.pdf)

---

## License

This repository is licensed under the [MIT License](LICENSE).

The license applies to the original material created for this repository. External papers, datasets, tools, and other resources remain subject to their respective licenses and copyright terms.