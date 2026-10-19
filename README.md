# Web Data Enrichment & Monitoring Pipeline

An automated data extraction and enrichment pipeline designed to collect unstructured company data from the web, parse it into structured formats using hybrid LLM inference (Local Ollama & Google Gemini API), and monitor content changes over time.

> **Status:** In active development 

---

### Key Features (Planned & In Progress)
- Automated web scraping and content extraction.
- Schema validation and structured outputs using Pydantic.
- Hybrid LLM processing: Local inference (Ollama / Llama 3) and Cloud inference (Google Gemini API).
- Content diff engine to track changes across data collection cycles.

### Tech Stack
- **Language:** Python
- **AI / LLMs:** Google Gemini API, Ollama (Llama 3)
- **Data & Tools:** BeautifulSoup, Pydantic, SQLite
