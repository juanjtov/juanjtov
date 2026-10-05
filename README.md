# Hi, I'm JJ (Juan José)

**AI Solutions Architect · Forward Deployed Engineer** — Greater Vancouver, BC

I design and ship production AI systems: multi-agent orchestration, hybrid-search RAG, and the evaluation harnesses that make them trustworthy. Chemical engineer by training, MBA, and founder of Toruk Technologies, where I build AI products for the construction industry while running a general-contracting practice — so the systems I build get used by real operators on real jobs.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-juanjtov-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/juanjtov)
[![Email](https://img.shields.io/badge/Email-contact-D14836?logo=gmail&logoColor=white)](mailto:juanjosetmontana@gmail.com)

---

### Featured work

| Project | What it is | Stack |
|---|---|---|
| [**FINAQ**](https://github.com/juanjtov/finaq) | Multi-agent equity research analyst. Parallel agents over SEC filings, fundamentals and news; hybrid BM25 + cosine + RRF retrieval; 10,000-sample Monte Carlo valuation; three-tier RAG evaluation; every claim cited. | LangGraph · Pinecone · OpenRouter · Streamlit · Pydantic |
| [**ADLC Pipeline**](https://github.com/juanjtov/adlc-pipeline) | Portable agentic software-delivery pipeline as a Claude Code plugin. Four role agents with two human gates, deterministic unit-tested guardrails, a self-improving retro loop, and per-agent cost/latency telemetry. | Claude Code · GitHub Actions · Bash · OpenTelemetry |
| **Remodly** *(private)* | AI in-home estimator for general contractors. Learns a contractor's pricing from past estimates and contracts, turns iOS LiDAR room scans into on-the-spot estimates, and exports branded documents for e-signature. Hybrid retrieval (pgvector + full-text, weighted RRF), deterministic pricing guardrails, golden-set retrieval and generation evals. | React · FastAPI · Supabase (pgvector) · Google Cloud · Swift |
| **Proesphere** *(private)* | AI-native construction project management platform. Agentic assistant with tool-based orchestration and streaming, human confirmation before high-risk actions, role-based access, a client portal, and CI on ephemeral database branches. Delivered through the ADLC pipeline above. | React · TypeScript · FastAPI · PostgreSQL (Neon) · Google Cloud |

*Private repos: walkthrough available on request.*

---

### How I build

- **Reliability comes from system design, not from trusting the model.** Deterministic rules first, LLMs for the residual, and promote to rules once stable.
- **Evals before features.** Golden sets, LLM-as-judge with categorical labels, and faithfulness checks wired into CI.
- **Humans at the irreversible steps.** Agents move work up to a gate, never through it.
- **Cost and latency are design inputs**, measured per agent, not discovered on the invoice.

### Toolbox

**AI / ML:** LangGraph · RAG (hybrid retrieval, RRF) · LLM evaluation (RAGAS, LLM-as-judge) · Claude Code · OpenRouter · Pinecone · pgvector
**Backend & data:** Python · FastAPI · PostgreSQL · Supabase · SQL · Pydantic
**Frontend:** React · Vite · Tailwind · Streamlit
**Cloud & ops:** Google Cloud · GitHub Actions · Docker · Vercel
