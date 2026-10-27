<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1F3A,100:2563EB&height=170&section=header&text=Akaash%20Tripathee&fontColor=ffffff&fontSize=44&fontAlignY=38&desc=AI%20Systems%20Engineer&descSize=20&descAlignY=60" width="100%" alt="Akaash Tripathee, AI Systems Engineer"/>

**LLM Applications  |  RAG  |  Document AI  |  Conversational and Voice AI  |  Agentic Workflows**

Production AI that is accurate, auditable and fast, from first prototype to deployment.

<a href="mailto:tripathiakaash@gmail.com"><img src="https://img.shields.io/badge/Email-tripathiakaash%40gmail.com-0B1F3A?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/akaash-t-bb9211212"><img src="https://img.shields.io/badge/LinkedIn-Connect-2563EB?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://medium.com/@tripathiakaash"><img src="https://img.shields.io/badge/Medium-Articles-0B1F3A?style=for-the-badge&logo=medium&logoColor=white"/></a>

Delhi NCR, India  |  **Open to AI / GenAI Engineer roles** (full-time, contract, remote)

<br/>

<a href="#profile"><img src="https://img.shields.io/badge/Profile-1F2937?style=flat-square"/></a>
<a href="#services"><img src="https://img.shields.io/badge/Services-1F2937?style=flat-square"/></a>
<a href="#case-studies"><img src="https://img.shields.io/badge/Case%20Studies-1F2937?style=flat-square"/></a>
<a href="#featured-projects"><img src="https://img.shields.io/badge/Projects-1F2937?style=flat-square"/></a>
<a href="#experience"><img src="https://img.shields.io/badge/Experience-1F2937?style=flat-square"/></a>
<a href="#technical-skills"><img src="https://img.shields.io/badge/Skills-1F2937?style=flat-square"/></a>
<a href="#community-and-achievements"><img src="https://img.shields.io/badge/Community-1F2937?style=flat-square"/></a>
<a href="#github-statistics"><img src="https://img.shields.io/badge/Statistics-1F2937?style=flat-square"/></a>
<a href="#work-with-me"><img src="https://img.shields.io/badge/Work%20With%20Me-2563EB?style=flat-square"/></a>

</div>

---

## Profile

AI Systems Engineer building production LLM applications: RAG pipelines, agentic workflows, real-time voice agents and OCR / document intelligence. Strong in Python and FastAPI, with a focus on **guardrails, structured-output validation and production reliability**. Previously at OnGraph Technologies, Head-Field Solutions and Paytm; currently working as a freelance AI Engineer delivering systems for clients.

<div align="center">

| 95% | 87% | 9,271 | 500+ | 9,000+ |
|:---:|:---:|:---:|:---:|:---:|
| RAG retrieval precision | OCR benchmark accuracy | pages processed | AI evaluation tasks authored | TFUG community members |

</div>

---

## Services

Available for remote contract and freelance engagements. Click a service to email me about it.

| Service | What you get | Evidence |
|---|---|---|
| **[RAG and Knowledge Assistants](mailto:tripathiakaash@gmail.com?subject=Project%20enquiry%3A%20RAG%20and%20Knowledge%20Assistant)** | Retrieval pipelines on your documents and data: vector search, grounding, citations | **95%** domain-specific retrieval precision in production |
| **[Document AI and OCR](mailto:tripathiakaash@gmail.com?subject=Project%20enquiry%3A%20Document%20AI%20and%20OCR)** | Extraction and validation for scanned or handwritten documents, including fully offline and on-premise setups | **78% to 87%** accuracy across **9,271 pages**, zero silent errors |
| **[Voice and Conversational AI](mailto:tripathiakaash@gmail.com?subject=Project%20enquiry%3A%20Voice%20and%20Conversational%20AI)** | Real-time voice agents and calling assistants with interruption handling and tool calling | Gemini Live, Telnyx, Ollama; public repos with **80+ stars** |
| **[LLM Apps and Agentic Workflows](mailto:tripathiakaash@gmail.com?subject=Project%20enquiry%3A%20LLM%20Application%20or%20Agent)** | Multi-step agents with guardrails and audit trails; Dify and n8n automation into CRM and knowledge bases | PRD-to-QA pipeline cut test creation effort by **60%** |
| **[AI Evaluation and Benchmarks](mailto:tripathiakaash@gmail.com?subject=Project%20enquiry%3A%20AI%20Evaluation)** | Test harnesses, reference solutions and structured-output validation to measure model and agent quality | **500+** agent-evaluation tasks authored |
| **[Backend and Deployment](mailto:tripathiakaash@gmail.com?subject=Project%20enquiry%3A%20Backend%20and%20Deployment)** | FastAPI services, Docker, Kubernetes, CI/CD | Containerized services scaled in production |

---

## Case Studies

<details open>
<summary><b>Handwritten timesheets to Excel, fully offline</b> &nbsp;|&nbsp; Document AI</summary>
<br/>

- **Problem:** handwritten site timesheets had to be digitized for payroll with no cloud dependency and no silent mistakes.
- **Solution:** 3-stage OCR, extraction and validation pipeline (RapidOCR, FastAPI, multi-arch Docker) with benchmarking against Tesseract, EasyOCR and Qwen3-VL.
- **Result:** benchmark accuracy **78% to 87%** across **9,271 pages**, with zero silent errors. Part of an HRMS serving **~450 workers across 10+ sites**.

</details>

<details>
<summary><b>Enterprise RAG at 95% retrieval precision</b> &nbsp;|&nbsp; RAG and LLM Applications</summary>
<br/>

- **Problem:** domain-specific questions needed accurate, low-latency answers from enterprise knowledge.
- **Solution:** RAG pipelines on vector databases with concurrent search, behind a stateful microservice conversational engine, with multi-model routing (OpenAI, Amazon Nova).
- **Result:** **95%** domain-specific retrieval precision (OnGraph Technologies).

</details>

<details>
<summary><b>Real-time voice agent with barge-in</b> &nbsp;|&nbsp; Conversational AI</summary>
<br/>

- **Problem:** voice assistants feel slow and cannot be interrupted.
- **Solution:** bidirectional WebSocket streaming with an async audio pipeline, interrupt handling, concurrent sessions and tool calling.
- **Result:** sub-second conversational latency. Open source: [ai-calling-assistant](https://github.com/coder-irwin/ai-calling-assistant) and [NovaVoice AI](https://github.com/coder-irwin/voice_ai_agents_using-Gemini_live_api).

</details>

---

## Featured Projects

| Project | Description | Stack |
|---|---|---|
| [**voice-agent-workshop**](https://github.com/coder-irwin/voice-agent-workshop) (16 stars) | A fully local voice agent that hears you, talks back and acts (opens YouTube, searches, scrolls). No API keys, no cloud, no cost. | Whisper, Ollama, Kokoro, Playwright |
| [**voice_ai_agents_using-Gemini_live_api**](https://github.com/coder-irwin/voice_ai_agents_using-Gemini_live_api) (47 stars) | NovaVoice AI: production-style Gemini Live voice agent with Google Calendar scheduling and a secure Python gateway. | Gemini Live, FastAPI, WebSockets |
| [**ai-calling-assistant**](https://github.com/coder-irwin/ai-calling-assistant) (18 stars) | Real-time voice-to-voice calling assistant with function calling and interrupt handling. Zero backend. | Gemini Live API, Web Audio |
| [**novaflow-qa-agent**](https://github.com/coder-irwin/novaflow-qa-agent) (3 stars) | Turns a PRD into executable UI tests, runs them, and lets you talk to the report. Amazon Nova Hackathon 2026. | Amazon Nova, FastAPI, React |
| [**trueprice-cars24**](https://github.com/coder-irwin/trueprice-cars24) | Variant-aware, confidence-scored used-car price estimator that closes the estimate-to-final-price gap. | Python, open-source MVP |
| [**echosphere-ps5-voice-support**](https://github.com/coder-irwin/echosphere-ps5-voice-support) | Real-time multilingual voice support for e-commerce. Agora Conversational AI Hackathon. | Python, Agora |
| [**minimal-voice-ai-system**](https://github.com/coder-irwin/minimal-voice-ai-system) | Streaming STT, LLM and TTS backend with barge-in, memory layers and hardware-aware tuning. | FastAPI, Whisper, Ollama, Docker |

---

## Experience

<sub>Click a role to expand or collapse it.</sub>

<details open>
<summary><b>AI Engineer (Freelance)</b> &nbsp;|&nbsp; Jun 2026 to Present</summary>
<br/>

- Built an offline 3-stage OCR, extraction and validation pipeline (RapidOCR, FastAPI, multi-arch Docker) that digitizes handwritten timesheets into Excel: **78% to 87% benchmark accuracy across 9,271 pages, zero silent errors**.
- Architected an open-source HRMS for GCC construction operations: OCR digitization and payroll for **~450 workers across 10+ sites**, validated against **49 requirements** by automated test suites.
- Built a fully local, Dockerized OCR solution for certificate extraction and validation, plus an **OCR engine benchmark lab** (RapidOCR, Tesseract, EasyOCR, Qwen3-VL).
- Delivered a multi-agent document-processing platform (Prisma, PostgreSQL) and other client backends.

</details>

<details open>
<summary><b>AI Trainer (freelance), Handshake and Turing</b> &nbsp;|&nbsp; May 2025 to Present</summary>
<br/>

- Authored **500+ technical evaluation tasks** in Harbor-based environments and Terminal-Bench 2.0 setups: terminal workflows, coding tasks and multi-step AI-agent evaluations.
- Built reproducible task environments, reference solutions and tests to measure agent correctness.
- Reviewed hundreds of AI-generated and user-submitted tasks for technical accuracy, instruction adherence and benchmark compliance.

</details>

<details>
<summary><b>AI/ML Engineer, Head-Field Solutions</b> &nbsp;|&nbsp; Noida &nbsp;|&nbsp; May 2026 to Jun 2026</summary>
<br/>

- Built a production voice-to-voice agentic calling assistant with Ollama local LLMs, Telnyx and Claude Code.

</details>

<details>
<summary><b>AI Systems Engineer, OnGraph Technologies</b> &nbsp;|&nbsp; Aug 2025 to May 2026</summary>
<br/>

- Architected a low-latency conversational AI engine on stateful microservices; built enterprise RAG pipelines (vector DBs, concurrent search) at **95% domain-specific retrieval precision**.
- Orchestrated multi-model workflows (OpenAI, Amazon Nova) with deterministic routing; built async agentic workflows in Dify and n8n connected to CRM and knowledge bases.
- Built FastAPI backends for low-latency LLM interoperability; shipped with Docker and Kubernetes.

</details>

<details>
<summary><b>Software Engineer Intern, Paytm</b> &nbsp;|&nbsp; Jan 2025 to Aug 2025</summary>
<br/>

- Built FastAPI backend services for high-throughput IVR systems.

</details>

<details>
<summary><b>Earlier roles and education</b></summary>
<br/>

- **Machine Learning Intern, Energy Venture** (Jul 2024 to Oct 2024): IoT sensor data pipelines and computer-vision models for automated industrial inspection.
- **Community Growth Manager, Where U Elevate** (Oct 2023 to Apr 2024): market research and engagement work that doubled platform user adoption.
- **B.Tech, Computer Science (AI and ML)**, NITRA Technical Campus, Ghaziabad (2021 to 2025).

</details>

---

## Technical Skills

<details open>
<summary><b>Click to expand or collapse</b></summary>
<br/>

| Area | Technologies |
|---|---|
| **LLM and Agentic Systems** | RAG, agentic architectures, function calling and tool use, LangChain, LangGraph, Dify, n8n, Gemini Live API, Amazon Nova and Sonic, prompt engineering |
| **Document AI** | RapidOCR, Tesseract, EasyOCR, Qwen3-VL, extraction and validation pipelines |
| **Reliability and Evaluation** | Structured-output validation, guardrails, traceability, automated testing, Selenium, benchmark design |
| **Backend and Data** | Python, FastAPI, Flask, REST APIs, SQL, PostgreSQL, Pinecone, Weaviate, pgvector, vector embeddings |
| **Infrastructure** | Docker, Kubernetes, Git, CI/CD, Google Cloud and Vertex AI, AWS, system design |

</details>

---

## Community and Achievements

- **Lead Organizer, TensorFlow User Group Ghaziabad**: 9,000+ members; recognized by Google for Developers for community impact.
- Speaker and workshop host on Gemini, ADK, Vertex AI, agents and RAG.
- **AWS Community Builder**, AI Engineering (2026); **AWS Machine Learning Summer School Finalist**.
- **ICPC Regionalist** (2023 to 2024).

---

## GitHub Statistics

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=coder-irwin&show_icons=true&hide_border=true&theme=transparent&title_color=2563EB&icon_color=2563EB&text_color=808080&count_private=true"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=coder-irwin&layout=compact&hide_border=true&theme=transparent&title_color=2563EB&text_color=808080&langs_count=6"/>

<img src="https://streak-stats.demolab.com/?user=coder-irwin&theme=transparent&hide_border=true&ring=2563EB&fire=2563EB&currStreakLabel=2563EB&currStreakNum=808080&sideNums=808080&sideLabels=808080&dates=808080"/>

</div>

---

## Work With Me

<div align="center">

**Open to remote contract, freelance and full-time AI / GenAI engineering roles.**

How an engagement typically runs: **1.** short call to scope the problem and success metric  **2.** working prototype measured on your data  **3.** production hardening and deployment  **4.** handover with documentation.

<a href="mailto:tripathiakaash@gmail.com?subject=Project%20enquiry"><img src="https://img.shields.io/badge/Start%20a%20project-Email%20me-2563EB?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/akaash-t-bb9211212"><img src="https://img.shields.io/badge/LinkedIn-Message-0B1F3A?style=for-the-badge&logo=linkedin&logoColor=white"/></a>

[tripathiakaash@gmail.com](mailto:tripathiakaash@gmail.com)  |  [Medium](https://medium.com/@tripathiakaash)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1F3A,100:2563EB&height=90&section=footer" width="100%" alt=""/>

</div>
