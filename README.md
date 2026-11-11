```text
╔══════════════════════════════════════════════════════════════════════════════╗
║ ARMAND PISTOL // SYSTEMS & AI ENGINEERING ARCHITECTURE                       ║
╠══════════════════════════════════════════════════════════════════════════════╣
║ > BACKGROUND  : Former Law Enforcement Officer -> Systems & AI Engineer      ║
║ > CORE DOMAIN : Tri-Modal AI, Hybrid RAG, Agentic Graphs & Geospatial SQL    ║
║ > STACK IRON  : Python · PostgreSQL (pgvector/PostGIS) · dbt · Airflow       ║
║ > AI / RAG    : LangGraph · LlamaIndex · Qwen-VL · Whisper · LiteLLM         ║
║ > TERMINAL    : https://armandpistol.dev                                     ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

### 📡 Architectural Focus
Applying a law enforcement investigator's rigor to systems architecture, I design and deploy end-to-end data and AI pipelines. I specialize in transforming chaotic, unstructured archives (declassified microfilm, FOIA PDFs, audio recordings, and motion video) into strict, queryable forensic intelligence matrices.

- **Multimodal Extraction & Contracts:** In-memory vision, audio, and video pipelines (`Qwen 2.5-VL`, `Whisper`, `OpenCV`) wrapped in `LiteLLM` and enforced by strict `Pydantic v2` data contracts.
- **Hybrid Vector & Spatial Storage:** Unified `PostgreSQL` (`Supabase`) architectures combining `pgvector` HNSW semantic search (`nomic-embed-text`) with native `PostGIS` (`SRID-4326`) geospatial indexing.
- **Analytical Engineering & Orchestration:** Idempotent incremental pipelines via `Apache Airflow` (`Docker Compose`) paired with `dbt Core` (`dbt-postgres`) for `JSONB` unpacking, SQL window healing, and automated schema testing.
- **Agentic Workflows & Advanced RAG:** Multi-agent state machines (`LangGraph`) integrated with `LlamaIndex` sentence-window parsing and hybrid reranking.

---

### 📂 Flagship Operation: [The Black-Budget Cemetery // R.E.A.P.E.R. [MOD-0]](https://github.com/armandpistol/the-black-budget-cemetery)
> **Retrieval Engine for Autonomous Processing & Entity Resolution**  
> *Live Clandestine Terminal:* **[armandpistol.dev](https://armandpistol.dev)** · *Source Repository:* **[github.com/armandpistol/the-black-budget-cemetery](https://github.com/armandpistol/the-black-budget-cemetery)**

An automated Tri-Modal AI and Geospatial Intelligence platform continuously sweeping declassified U.S. government archives (`NARA Catalog API / RG-615`, `FBI Vault`, `CIA CREST`) across three specialized intelligence domains:
1. **Agent Alpha (`DRACO`):** Aerospace kinematics, radar-visual corroboration & spatial telemetry.
2. **Agent Beta (`DR. SAPELLI`):** Psychoenergetic operations, pharmacology, & witness psychometric stress load.
3. **Agent Gamma (`CALLISTA`):** Counterintelligence routing lineage & FOIA censorship/redaction forensics.
