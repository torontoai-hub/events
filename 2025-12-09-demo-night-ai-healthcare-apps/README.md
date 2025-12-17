# Demo Night Recap: From Fear Detection to Production-Ready AI Agents

**Demo Night – Build AI Healthcare Apps**

* **Date:** December 9, 2025
* **Location:** ShyftLabs, Toronto
* **Community:** TorontoAI

---

## 📂 Slides & Recordings

### Slide Decks

* [MoorchehAI Demo](Moorcheh.ai_demo_Dec_9_2025.pdf)

* [FalconsAI FearSense App](Falcons.ai_demo_Dec_9_2025.pdf)

### Full Recordings

* 🎥 **Demo 1 – FearSense:** [https://youtu.be/cqzwpBPW83s](https://youtu.be/cqzwpBPW83s)
* 🎥 **Demo 2 – Moorcheh.ai:** [https://youtu.be/HWs4XAO75XA](https://youtu.be/HWs4XAO75XA)

---

## 🌐 About TorontoAI

TorontoAI is a community built to bridge the gap between **developers, startups, and applied AI use cases**.

With **6,000+ members across platforms**, TorontoAI focuses on:

* Hands-on demo nights
* Technical panels
* Applied learning for people **building and deploying AI systems**, not just discussing them

Special thanks to **ShyftLabs** for hosting and supporting the local AI ecosystem.

---

## 🧪 Demo #1: FearSense — Fear-Mongering Detection with Falcons AI

### Problem Statement

Fear-driven content is pervasive across:

* News media
* Political speech
* Social media
* Children’s content

While sentiment analysis is common, **fear detection** is a more nuanced and under-explored problem—especially when evaluated for societal and healthcare impact.

**Core question explored:**

> Can fear in media content be quantified—and used responsibly in healthcare and research contexts?

---

### 🔬 About Falcons AI

**Falcons AI** is a developer-focused AI company whose models consistently rank among the **most downloaded on Hugging Face**, despite being built by a small, bootstrapped team.

* Focus on **specific, real-world problems**
* Avoids generic AGI hype

🔗 Hugging Face: [https://huggingface.co/Falconsai](https://huggingface.co/Falconsai)

---

### 🧠 Model & Architecture

The FearSense demo uses a **DistilBERT-based model**, fine-tuned specifically for fear-mongering detection.

**Key characteristics:**

* CPU-only inference (no GPU required)
* Lightweight and efficient
* Local or small-cloud deployable
* Deterministic and explainable outputs

This makes it well-suited for **regulated, research, and healthcare-adjacent environments**.

---

### 🛠 Live Demo Overview

The FearSense application is built using **Streamlit**.

🔗 GitHub Repo: [https://github.com/torontoai-hub/fear-monger-detector](https://github.com/torontoai-hub/fear-monger-detector)

**Features demonstrated:**

* Accepts YouTube URLs or raw text
* Automatically extracts transcripts
* Chunks text for analysis
* Scores fear intensity per chunk
* Visualizes fear peaks and distributions

The demo included real-world friction—cloud tunnels, missing dependencies, and live debugging—offering an honest view of **production AI development**.

---

### 🏥 Healthcare & Research Use Cases

Potential applications discussed:

* Correlating fear-heavy content with wearable data (heart rate, stress)
* Studying impacts on vulnerable populations (seniors, children)
* Providing **research tools**, not medical diagnoses

> This is a research-enabling prototype—not a clinical decision system.

---

## 🤖 Demo #2: Moorcheh.ai — Building Scalable AI Assistants & Agents

The second half of the event focused on **production-grade AI systems**, moving beyond prototypes.

---

### Problem Moorcheh.ai Addresses

Many teams struggle to move from:

* Prototype chatbots

to:

* Scalable, accurate, and cost-efficient AI assistants

**Common challenges:**

* Complex RAG pipelines
* High latency
* Hallucinations
* Expensive vector databases
* Difficulty deploying beyond notebooks

Moorcheh.ai acts as an **infrastructure abstraction layer** for AI assistants.

---

### 🩺 Case Study: DoctorPal AI (Healthcare)

DoctorPal AI is a healthcare assistant built on thousands of pages of medical and nutrition documents.

Using Moorcheh.ai, the team:

* Uploaded large document sets (PDFs, websites, structured data)
* Automatically chunked, embedded, summarized, and indexed content
* Enforced relevance thresholds to reduce hallucinations
* Returned citation-backed responses
* Restricted allowed queries via kiosk mode

**Outcome:**
A domain-specific assistant that answers strictly from verified sources.

---

### ⚙️ Key Technical Capabilities

* Namespace-based knowledge isolation
* Built-in re-ranking & relevance scoring
* Toggleable kiosk mode
* Multi-model support (Claude, LLaMA, Bedrock-native)
* API-first design
* Serverless, cloud-native architecture

A key differentiator: **assistants can be exported into real production apps**.

---

### 🧩 From Chatbots to AI Agents

The demo concluded with an example of a **dynamic AI agent**, not just a Q&A bot.

**Example shown:**

* Legal intake AI agent
* Adaptive questioning based on user responses
* RAG used for decision rules, not documents
* Structured summaries for human review

**End-to-end build time:** hours, not weeks.

---

## 🔗 Moorcheh.ai Resources & Integrations

* GitHub SDKs: [https://github.com/moorcheh-ai/moorcheh-python-sdk](https://github.com/moorcheh-ai/moorcheh-python-sdk)
* LangChain Integration: [https://docs.langchain.com/oss/python/integrations/vectorstores/moorcheh](https://docs.langchain.com/oss/python/integrations/vectorstores/moorcheh)
* LlamaIndex Integration: [https://developers.llamaindex.ai/python/examples/vector_stores/moorchehdemo/](https://developers.llamaindex.ai/python/examples/vector_stores/moorchehdemo/)
* MCP Server: [https://github.com/moorcheh-ai/moorcheh-mcp](https://github.com/moorcheh-ai/moorcheh-mcp)
* n8n Integration (Verified): [https://n8n.io/integrations/moorcheh/](https://n8n.io/integrations/moorcheh/)

---

## ✅ Key Takeaways

* Small, focused models still matter
* Real AI demos include debugging and trade-offs
* RAG is mandatory for serious AI products
* The future is **task-driven, context-aware AI agents**
* Community-driven learning accelerates innovation

---

## 🙏 Thank You

Thanks to:

* **Falcons AI**
* **Moorcheh.ai**
* **ShyftLabs**
* Everyone who attended and participated

TorontoAI will continue hosting demo nights, panels, and hands-on sessions focused on **applied AI and platform engineering**.

If you’re building something in AI, **TorontoAI is your platform**.

---

If you want, I can also:

* Split this into `/demo1-fearsense` and `/demo2-moorcheh` READMEs
* Convert it into a repo landing page + `/docs` structure
* Add architecture diagrams (Mermaid)
* Optimize it for GitHub SEO and stars
