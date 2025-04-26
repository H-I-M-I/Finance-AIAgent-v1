# Finance-AI-Agent-1

This project builds a **basic AI Finance Research Agent** capable of handling financial research tasks via tool-based searching and summarizing. It sets up an AI agent with tool-calling functionality using DuckDuckGo and Newspaper4k APIs for financial news scraping.

## Methodology
- **Tool-Enhanced LLM Agent**: LLM enhanced with web-search and scraping capabilities.
- **Structured Research Phases**: Research, Analysis, Writing, and Quality Control phases.
- **Markdown-Formatted Outputs**: Financial report-style summaries.

## Tools & Libraries
- **Agno Framework** (Agent Management)
- **Groq API** (Fast LLM inference)
- **DuckDuckGo Search** (for fresh web results)
- **Newspaper4k** (for article scraping)
- **Python (Colab)** environment

## Implementation Steps
1. Install necessary packages (Agno, Groq, DuckDuckGo, Newspaper4k).
2. Set environment variables (`GROQ_API_KEY`, `PHI_API_KEY`).
3. Initialize an **Agent** with:
   - Groq model (`llama3-70b-8192`).
   - Tools: DuckDuckGo and Newspaper4k.
4. User provides financial research queries.
5. Agent outputs detailed structured reports.
