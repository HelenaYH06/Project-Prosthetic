# Project-Prosthetic
A cognitive enhancement layer for readers of q9adg. A "clumsy replica" attempting to mimic human memory and association using RAG &amp; MoE architectures.
# 🦾 Project Prosthetic (义肢计划)

> "It is not a replacement, but a crutch for the carbon mind."

**Project Prosthetic** is a Computational Social Science (CSS) experiment and an open-source tool designed for deep readers of **@q9adg**.

## 🧩 Design Philosophy: The "Next Best" Choice (下下选)

**This project is NOT a replacement for "Sooon.ai" (素问), nor is it a silver bullet.**

It is, by definition, an **auxiliary tool**—a "clumsy replica" attempting to mimic human memory and association. Faced with the reality that carbon-based readers cannot instantly recall thousands of articles, this is the **"next best choice" (下下选)**: using silicon computing power to compensate for biological limitations.

**⚠️ Warning to Users:**
> "If you have a choice, please, **read the original articles**. Only your own brain can synthesize these thoughts in the most serendipitous ways. You cannot outsource your life to an AI. This tool is merely a prosthetic; do not let it atrophy your own cognitive muscles.
>
> Furthermore, recognize the limitations of AI: its potential for alienation, sycophancy, and hallucinations. **Know thyself.**"
> — *Helena, Project Author*

---

## 🏗 Architecture

The project evolves in two distinct biological metaphors:

### Phase 1: Prosthetic-Hippocampus (义肢-海马体)
* **Status**: 🚧 **In Development (Architecture Validated) MVP in 48 hours.**
* **Function**: Advanced Retrieval Augmented Generation (RAG).
* **Role**: The **Memory Center**. It solves the "Keyword Curse" by providing semantic search across the full corpus.
* **Privacy**: **BYOK (Bring Your Own Key)**. User data stays local or transmits directly to LLM providers.

### Phase 2: Prosthetic-Exocortex (义肢-外脑)
* **Status**: 🚧 **In Development (Architecture Validated)**
* **Function**: Dual-Layer MoE (Mixture of Experts) with Routing.
* **Role**: The **Logic Processor**.
    * **Brain A (The Empath)**: Large Context Model (e.g., Gemini 1.5 Pro) holds user context.
    * **Brain B (The Router)**: Fine-tuned Small Model (e.g., Gemma 2) routes queries to specific logical frameworks within the author's philosophy. **Crucially, Brain B creates indices, not content.**

---

## ⚖️ Copyright & Data Compliance

**STRICT POLICY:**
This repository contains **ONLY the logic infrastructure (Code)**.

1.  **No Data**: It does **NOT** contain any article data, JSON files, or model weights derived from @q9adg's content.
2.  **No Unauthorized Weights**: No LoRA adapters trained on the author's text are hosted here without explicit permission.
3.  **Usage**: To make this functional, users must obtain authorized data (e.g., from the author's open datasets) and place it in the `data/` directory locally.

---

## 🛠 Tech Stack

* **LLM Orchestration**: LangChain / LlamaIndex
* **Models**: Google Vertex AI (Gemini 2.5 Pro), Gemma 2
* **Vector Database**: Pinecone (Serverless) / Supabase
* **Backend**: FastAPI (Python)
* **Frontend**: Next.js / Streamlit

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
*Created by Helena, a reader.*