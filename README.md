<div align="center">

![Arush Sharma banner](https://capsule-render.vercel.app/api?type=waving&color=0:020617,35:1D4ED8,70:0F766E,100:020617&height=230&section=header&text=Arush%20Sharma&fontColor=FFFFFF&fontSize=56&animation=fadeIn&fontAlignY=38&desc=AI%20Systems%20%7C%20Agentic%20Workflows%20%7C%20Applied%20Machine%20Learning&descAlignY=58&descSize=18)

### Building AI systems that move from notebook experiments to usable products.

[![GitHub](https://img.shields.io/badge/GitHub-Arush777-0D1117?style=for-the-badge&logo=github)](https://github.com/Arush777)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Arush%20Sharma-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arush-sharma-44a796288)
[![Focus](https://img.shields.io/badge/Focus-LLMs%20%7C%20Agents%20%7C%20ML%20Systems-14B8A6?style=for-the-badge)](#current-signal)

</div>

---

## Current Signal

```text
role        : ML/AI builder, researcher, and systems tinkerer
focus       : agentic AI, LLM evaluation, model alignment, applied ML products
currently   : building testable LLM workflows, AI assistants, and research-grade ML pipelines
style       : ship useful systems, document the reasoning, keep experiments reproducible
```

I like projects where the model is only one part of the system: retrieval, data quality, evaluation, user workflow, infrastructure, and failure handling all matter. My work moves across agentic systems, language-model fine-tuning, physics-informed deep learning, reinforcement learning, and product-oriented AI.

---

## Portfolio Map

| Track | What I Build | Strongest Evidence |
|---|---|---|
| Agentic AI | structured LLM workflows, ReAct-style agents, evaluator loops, MCP demos | [mellea-IBM](https://github.com/Arush777/mellea-IBM) |
| Applied AI Products | end-to-end AI apps with backend, frontend, storage, and deployment | [ReVival](https://github.com/Arush777/ReVival), [AtomMail](https://github.com/Arush777/my-hackfest-atom-mail) |
| Research ML | PyTorch experiments, scientific ML, model evaluation, public artifacts | [Deeplense_GSoC](https://github.com/Arush777/Deeplense_GSoC) |
| LLM Training | QLoRA, LoRA, DPO, summarization, preference optimization | [DPO Alignment](https://github.com/Arush777/High-Performance-Language-Model-Alignment-via-Direct-Preference-Optimization), [Mistral Summarization](https://github.com/Arush777/Finetuned-mistral-summartization-model) |
| Foundations | language modeling, RL agents, implementation-first learning | [CS336 Study Repo](https://github.com/Arush777/Language_Modeling-stanford-cs336), [DQN Space Invaders](https://github.com/Arush777/Deep-Q-Learning-Agent-Space-Invaders-) |

---

## Featured Builds

### ReVival - AI-Powered Circular Commerce

[Repository](https://github.com/Arush777/ReVival) | [Live Demo](https://revival-rose.vercel.app)

ReVival is an end-to-end circular-commerce system for routing returned and seller-listed products back into the market instead of landfill. The system uses a 7-agent pipeline for product grading, resale routing, pricing, buyer matching, trust passport generation, sustainability credits, and listing-error prevention.

**What I owned**

- Supply-side AI and AWS backend.
- FastAPI pipeline for product returns and community listings.
- AWS Bedrock vision-based condition grading.
- Photo/video defect detection, confidence buckets, mismatch detection, and grading guardrails.
- DynamoDB and S3 data layer with `boto3`.
- Titan multimodal embedding cache to reduce repeated AI calls on visually similar products.

**Stack:** FastAPI, Python, AWS Bedrock, DynamoDB, S3, boto3, Next.js, TypeScript

---

### DeepLense - Physics-Informed Gravitational Lens ML

[Repository](https://github.com/Arush777/Deeplense_GSoC)

DeepLense contains my ML4Sci/GSoC evaluation work across gravitational-lens classification, observational lens finding, and physics-guided modeling. The focus is not just training a classifier, but building robust baselines, testing physics-aware structure, and releasing reusable model artifacts.

**Highlights**

- PyTorch pipelines for gravitational lens classification and finding.
- ROC-AUC based evaluation.
- Physics-guided modeling experiments.
- Public Hugging Face model artifacts.
- Research-style notebooks with reproducible setup notes.

**Stack:** Python, PyTorch, scientific ML, computer vision, ROC-AUC evaluation, Hugging Face

---

### Mellea IBM Workspace - Testable Generative Programs

[Repository](https://github.com/Arush777/mellea-IBM)

This workspace explores IBM Research's Mellea generative-programming ideas for structured, testable LLM workflows. I use it to prototype agent loops, MCP demos, evaluator patterns, and more controlled LLM application design.

**Focus areas**

- Structured LLM calls instead of one-off prompts.
- ReAct-style workflows and tool-use loops.
- MCP-oriented agent demos.
- Evaluation loops for checking LLM behavior.
- Small, inspectable examples that can grow into production workflows.

**Stack:** Python, Mellea, LLM agents, MCP, evaluators, generative programming

---

### AtomMail - AI Email Assistant

[Repository](https://github.com/Arush777/my-hackfest-atom-mail)

AtomMail is a Hackfest 2nd-prize AI email assistant built around retrieval, OCR, user-history memory, and LLM response generation. It helps users search email context, understand attachments/screenshots, and draft personalized replies.

**What it combines**

- Retrieval-augmented generation over email context.
- OCR for images and attachments.
- User-history retrieval for personalized responses.
- LLM-based reply drafting.
- Product-oriented workflow for inbox assistance.

**Stack:** JavaScript, RAG, OCR, LLM APIs, retrieval, email automation

---

### DPO / QLoRA Alignment Pipeline

[Repository](https://github.com/Arush777/High-Performance-Language-Model-Alignment-via-Direct-Preference-Optimization)

A compact alignment pipeline for preference optimization under limited hardware constraints. The repo explores Direct Preference Optimization with LoRA/QLoRA so alignment experiments can be run without large training infrastructure.

**Core ideas**

- Preference optimization with DPO.
- Parameter-efficient fine-tuning with LoRA.
- 4-bit quantized loading with QLoRA.
- Modular training and evaluation utilities.
- Hardware-aware experimentation.

**Stack:** PyTorch, Transformers, PEFT, TRL, bitsandbytes, LoRA, QLoRA, DPO

---

## Learning Labs

These repositories are implementation-first study projects. They are intentionally lower-level and help me sharpen fundamentals.

| Repo | What It Covers |
|---|---|
| [Mistral Summarization](https://github.com/Arush777/Finetuned-mistral-summartization-model) | QLoRA/LoRA fine-tuning for abstractive summarization |
| [Language Modeling CS336](https://github.com/Arush777/Language_Modeling-stanford-cs336) | tokenizer, transformer, training-loop, and language-modeling fundamentals |
| [DQN Space Invaders](https://github.com/Arush777/Deep-Q-Learning-Agent-Space-Invaders-) | convolutional Deep Q-Network agent for Atari Space Invaders |

---

## Technical Toolbox

<div align="center">

![Skills](https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,fastapi,react,nextjs,ts,js,nodejs,aws,docker,git,github,vscode)

</div>

| Area | Tools and Concepts |
|---|---|
| ML / DL | PyTorch, TensorFlow, scikit-learn, CNNs, transformers, evaluation metrics |
| LLMs | RAG, LoRA, QLoRA, DPO, summarization, agent workflows, prompt/evaluator loops |
| Backend | FastAPI, Python services, REST APIs, data pipelines |
| Cloud / Data | AWS Bedrock, DynamoDB, S3, boto3, Hugging Face artifacts |
| Frontend | Next.js, React, TypeScript, JavaScript |
| Research Workflow | notebooks, reproducible experiments, metric reporting, artifact release |




## Open To

- AI/ML internships and research engineering opportunities.
- Applied LLM systems, agentic AI, and ML infrastructure work.
- Collaborations around scientific ML, evaluation, RAG, and model fine-tuning.
- Projects that need both experimental depth and product sense.

---

<div align="center">

### If the repo has a model, it should have metrics. If it has agents, it should have traces. If it has a demo, it should have a reason to exist.

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:020617,35:0F766E,70:1D4ED8,100:020617&height=120&section=footer)

</div>
