<div align="center">

## Hi there, I’m Manuele-T.

First-Class Computing Graduate specializing in Generative AI, RAG, Agentic Systems, and Cloud-Native Solutions.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/manueletacchetti)

</div>

---

### Latest Release: Agent Troops — Secure Agent Teams for Claude Code

| **Least Privilege & Human Approval for Agentic AI** | **Tech Stack** |
| :--- | :--- |
| <img src="https://github.com/Manuele-T/agent-troops/blob/main/docs/screenshots/3-leak-warning-and-blocked-robot.jpg?raw=true" width="80%" /> | **Core:** Python, Claude Code (hooks, subagents, plugin)<br>**Security:** Least privilege, data loss prevention, policy-as-code<br>**Interface:** Live approval dashboard, CI-ready audit<br>Builds a task-specific agent team where each agent gets only the permissions its job needs. Every outward call (web, `curl`, `git push`) waits for a human Allow or Deny, and after a sensitive file is read nothing more can leave. Smuggled keys are flagged and every decision is logged with secrets redacted. Includes a replayable five-attack demo.<br><br>[**View Repository →**](https://github.com/Manuele-T/agent-troops) |

---

### Featured: Hermes Autonomous Builder — Agentic Web-App Pipeline

| **Discord-Controlled Autonomous Deployment** | **Tech Stack** |
| :--- | :--- |
| <img src="https://github.com/Manuele-T/Autonomous-Builder/blob/main/screenshots/02.png?raw=true" width="80%" /> | **Core:** Hermes Agent, DeepSeek V4 (OpenRouter)<br>**Interface:** Discord gateway<br>**Deploy:** Vercel, GitHub CLI, Neon<br>Turns a plain-language request into a deployed web app — planning, building, security-reviewing, and shipping to production. Built on AgentOps principles: human-in-the-loop approval gates and a code-review subagent that halts deployment on any security violation.<br><br>[**View Repository →**](https://github.com/Manuele-T/Autonomous-Builder) |

---

### Featured: Slack Summariser — Local RAG

| **On-Device Retrieval-Augmented Generation** | **Tech Stack** |
| :--- | :--- |
| <img src="https://github.com/Manuele-T/slack-summariser-local-rag/blob/main/screenshots/pic01.jpg?raw=true" width="80%" /> | **Core:** Python, Haystack, Ollama (local LLM)<br>**Retrieval:** Persistent **ChromaDB** vector store<br>**Pattern:** Retrieval-Augmented Generation (RAG)<br>Embeds Slack messages locally, summarises the day into five bullets, and answers semantic queries across full history — no cloud, no API keys.<br><br>[**View Repository →**](https://github.com/Manuele-T/slack-summariser-local-rag) |

---

### Featured: CodeWise — Prompt-Injection-Hardened AI Code Reviewer

| **Defense-in-Depth LLM Security** | **Tech Stack** |
| :--- | :--- |
| <img src="https://github.com/Manuele-T/codewise-ai-reviewer/blob/main/screenshots/03.jpg?raw=true" width="80%" /> | **Core:** React, Vite, Tailwind CSS<br>**Backend:** Vercel Serverless Functions, OpenAI (gpt-4o-mini)<br>**Security:** Input sanitisation, system-prompt hardening, output validation<br>Returns structured senior-engineer code reviews (summary, strengths, weaknesses, advice) as strict JSON. Blocks tag-breakout and jailbreak attempts, intercepts injected outputs server-side, checks magic bytes on uploads, and keeps the API key off the client.<br><br>[**View Repository →**](https://github.com/Manuele-T/codewise-ai-reviewer) |

---

### Active Projects

| **Agent Tooling** | **Agents & Automation** |
| :--- | :--- |
| **[Hermes Agent Control Surface](https://github.com/Manuele-T/hermes-agent-control-surface)**<br>Live PixiJS "room" of Hermes agents you can watch and act on — reassign, cancel, approve dangerous commands remotely.<br><br>![Stack](https://img.shields.io/badge/FastAPI-React-black) | **[AI Marketing Assistant](https://github.com/Manuele-T/AI_Marketing_Agent)**<br>Multi-agent system that automates social media content creation using LangGraph.<br><br>![Stack](https://img.shields.io/badge/Python-LangGraph-black) |
| **[AI File Analysis Agent](https://github.com/Manuele-T/Local-MCP-File-Analysis-Server)**<br>Agent-Tool system using Model Context Protocol (MCP) for local file I/O.<br><br>![Stack](https://img.shields.io/badge/Python-MCP-black) | **[AI News Digest](https://github.com/Manuele-T/N8N_AI_News)**<br>Self-hosted n8n workflow summarizing headlines via Azure OpenAI to Discord.<br><br>![Stack](https://img.shields.io/badge/n8n-Docker-black) |

---

### Archive

| Project | Description | Stack |
| :--- | :--- | :--- |
| **[Neon Breacher](https://github.com/Manuele-T/neon-breacher)** | Zero-asset retro arcade shooter with the React UI decoupled from the Canvas game loop. | `React` `TypeScript` `Canvas` |
| **[Slack Summariser (AWS)](https://github.com/Manuele-T/SlackSummariser)** | Cloud/serverless sibling of the local RAG version — daily summaries via Anthropic Claude 3 Sonnet on Bedrock. | `Lambda` `Bedrock` `EventBridge` |
| **[Recipes Chatbot](https://github.com/Manuele-T/Recipes_Chatbot)** | Conversational NLP interface exploring 500k+ recipes via Vertex AI. | `Python` `FastAPI` `React` |
| **[Java Task Tracker](https://github.com/Manuele-T/Java-Spring-Task-Tracker)** | Containerized backend demonstrating Spring Boot principles. | `Java` `Spring Boot` `Docker` |
| **[AgriLearn](https://github.com/Manuele-T/AgriLearn)** | Crop species & health classification using MobileNetV3 for Image Classification. | `Python` `TensorFlow` `Flask` |