# Generative AI (GenAI) 🤖✨

Welcome to the **GenAI** repository! This repository is dedicated to hands-on implementations, practical experiments, and production-grade architectures across the modern Generative AI landscape.

---

## 📂 Repository Structure

```text
GenAI/
│
├── Model Context Protocol/                 # Anthropic's Model Context Protocol (MCP) implementations
│   ├── README.md                           # MCP overview, architecture & documentation
│   └── my-first-mcp-server/                # Document Management MCP Server (FastMCP)
│
├── .gitignore                              # Global gitignore rules
└── README.md                               # Root repository overview (this file)
```

---

## 🚀 Modules & Topics

### 1. [Model Context Protocol (MCP)](./Model%20Context%20Protocol/)
The **Model Context Protocol (MCP)** is an open standard developed by Anthropic allowing AI systems to seamlessly interact with external data sources, tools, and services in a unified way.

* **Documentation & Overview:** [Model Context Protocol README](./Model%20Context%20Protocol/README.md)
* **Projects:**
  * **[`my-first-mcp-server`](./Model%20Context%20Protocol/my-first-mcp-server/)**: A custom MCP server built using Python & FastMCP SDK that exposes tools for reading and editing documents with MCP Inspector testing support.

---

## 🛠️ Tech Stack & Tooling

* **Languages:** Python 3.12+
* **Frameworks & SDKs:** FastMCP (`mcp[cli]`), LangChain, LlamaIndex, OpenAI / Anthropic SDKs
* **Package Managers:** `uv`, `pip`
* **Development & Debugging:** `@modelcontextprotocol/inspector`

---

## 🗺️ Roadmap & Upcoming Explorations

- [x] **Model Context Protocol (MCP)**
  - [x] FastMCP Document Management Server
  - [ ] Multi-tool MCP Servers & SQLite database integrations
  - [ ] Custom MCP Clients
- [ ] **AI Agents & Orchestration** (LangGraph, CrewAI, AutoGen)
- [ ] **Retrieval Augmented Generation (RAG)** & Vector Databases (Chroma, Qdrant, Pinecone)
- [ ] **Function Calling & Structured Outputs**
- [ ] **Fine-Tuning & Evaluation**

---

## 👤 Author

Developed and maintained by **[aniketgoyal12](https://github.com/aniketgoyal12)**.
