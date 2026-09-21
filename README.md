# Model Context Protocol (MCP) 🚀

Repository containing hands-on implementations, custom tools, and servers built while learning the **Model Context Protocol (MCP)** from **Claude Academy (Anthropic)**.

---

## 📌 About MCP (Model Context Protocol)

The **Model Context Protocol (MCP)** is an open standard developed by Anthropic that allows AI models (like Claude) to securely connect to external tools, data sources, and services. MCP replaces fragmented, one-off integrations with a clean, standardized client-server protocol.

---

## 📂 Projects in this Repository

### 1. [`my-first-mcp-server`](./my-first-mcp-server/) — Document Management MCP Server
A custom MCP server built using Python and the **FastMCP** SDK that exposes tools for reading and editing in-memory documents.

#### 🛠️ Features & Tools:
* **`read_doc_contents`**: Reads and retrieves document text given a `doc_id` (e.g., `deposition.md`, `report.pdf`, `plan.md`).
* **`edit_doc_contents`**: Modifies document content by performing a string replacement (`old_str` ➔ `new_str`) and returns the updated state.

#### 🚀 How to Run & Test:

1. **Navigate to the server directory:**
   ```bash
   cd my-first-mcp-server
   ```

2. **Activate Virtual Environment:**
   * **Windows (PowerShell):**
     ```powershell
     .\.venv\Scripts\Activate.ps1
     ```

3. **Launch MCP Inspector (Interactive Web UI):**
   ```bash
   .\dev.bat
   ```
   Or using Python directly:
   ```bash
   npx -y @modelcontextprotocol/inspector .venv\Scripts\python.exe server.py
   ```
   * Open the URL in your browser (defaults to `http://127.0.0.1:6274`).
   * Navigate to the **Tools** tab to test `read_doc_contents` and `edit_doc_contents`.

---

## 🛠️ Tech Stack & Prerequisites
* **Language:** Python 3.14+
* **Framework:** FastMCP (`mcp[cli]`)
* **Package / Environment Manager:** `uv` / `pip`
* **Inspector:** `@modelcontextprotocol/inspector` (Node.js / npx)

---

## 📚 Learning Reference
* **Course / Guide:** Claude Academy - Model Context Protocol
* **Official MCP Documentation:** [modelcontextprotocol.io](https://modelcontextprotocol.io)
* **Anthropic SDK:** [FastMCP for Python](https://github.com/modelcontextprotocol/python-sdk)
