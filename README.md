#  Real Estate AI Pipeline

A production-style AI system built for real estate data — featuring a full scraping pipeline and a multi-agent orchestration system.

---

## Project 1: Real Estate Data Scraping Pipeline
**File:** `real_estate_scraper.ipynb`

### What it does:
- Scrapes real estate property listings
- Cleans and structures raw data
- Generates semantic embeddings using Sentence Transformers

### Architecture:Raw Data → Scraper → Data Cleaner → Semantic Structuring → Structured CSV
### Tools Used:
- `requests` + `BeautifulSoup` — data scraping
- `pandas` — data cleaning and structuring
- `sentence-transformers` — semantic embeddings (all-MiniLM-L6-v2)

---

## 🤖 Project 2: Multi-Agent Real Estate AI System
**File:** `real_estate_multi_agent.ipynb`

### What it does:
- Orchestrates 4 AI agents to collect, analyze, match, and report on properties
- Agents communicate through shared memory
- Produces buyer-property match scores with full reasoning

### Agent Architecture:

| Agent | Role |
|-------|------|
|  Data Collector Agent | Scrapes and collects property listings |
|  Analysis Agent | Analyzes market trends and pricing |
|  Matching Agent | Matches properties to buyer profiles |
|  Orchestrator Agent | Coordinates all agents end-to-end |

### System Workflow:Orchestrator
├── Data Collector Agent → collects properties
├── Analysis Agent → market analysis
└── Matching Agent → buyer matching → Final Report
### Tools Used:
- `pandas` — data processing
- `sentence-transformers` — semantic understanding
- Shared memory architecture for agent communication

---

##  How to Run

1. Open the notebooks in Google Colab
2. Run all cells in order
3. View the final output and agent logs

---

## Author
Ahmed | AI Solutions & Agentic Systems consultant
