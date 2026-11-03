Hi, I'm Aniket 👋

AI Engineer focused on LLM agents, RAG pipelines and the APIs around them. I recently finished an AI/ML internship at Atlys, where I authored 28 PRs across an internal AI assistant and an agent-testing platform. I like turning a vague problem into a small working prototype and checking it honestly.

Open to AI/ML, agent and forward-deployed engineering roles and internships. Based in Delhi / Gurugram, India.

Experience

AI/ML Intern, Atlys (Aug 2026 – Oct 2026)

Gideon Employees: persistent AI workers on top of Atlys's internal AI assistant. 6 PRs, about 17k lines, all merged, open to every Atlys employee.
Instrumentation agent: turns Figma + a PRD into an analytics event spec. Merged after review, with 70 tests; it caught 3 of 3 split cases, and I cut its warnings from 32 to 10.
Agent-testing environment (team of 4): a simulated business backend (7-table schema, availability, booking and cancellation, simulated clock, CI and staging) covering 10 business types.
Reliability fixes: a 500 error caused by a transaction held open during a Slack call, and overlapping scheduler runs behind 456 cancellation errors in 24 hours.
Featured projects
Project	What it does	Stack
ResearchMind	A tool-calling agent that chooses between searching uploaded PDFs (FAISS) and the live web (Tavily) and cites page numbers or URLs. Includes an iteration cap and duplicate-query detection to stop tool-call loops.	LangChain · FastAPI · FAISS · FastEmbed · Groq (LLaMA 3.1) · Tavily · React · Docker
SHL Assessment Recommender	A stateless API that turns a vague hiring request into a grounded shortlist from a 370-item catalog. Time-budget checks run in plain code after the LLM was found to miscount. A replay harness runs 10 sample conversations.	Python · FastAPI · scikit-learn (TF-IDF) · Groq (LLaMA 3.3)
AWS Customer Agreement RAG	Q&A over a legal document. Paragraph-aware chunks (500 tokens, 100 overlap) and a refusal path that returns ANSWER_NOT_IN_DOCUMENT when the context is insufficient. Analytics endpoint over 35 seeded test queries.	FastAPI · FAISS · FastEmbed · Groq · PyMuPDF · pdfplumber · SQLite · Streamlit
Credit card fraud detection	284,807 transactions, 0.17% fraud. SMOTE on the training split only to avoid leakage. XGBoost reached 0.9792 AUC-ROC, and SHAP showed V14, V17 and V10 as the top signals.	XGBoost · Random Forest · SMOTE · SHAP · FastAPI
App Compiler	A staged LLM pipeline: intent extraction, architecture, schema generation, a code-based validator, and one repair pass. Turns a plain-English app idea into DB, API, UI and auth schemas.	Next.js · TypeScript · Groq (LLaMA 3.3 70B)
Stack
Languages    Python · TypeScript / JavaScript · SQL
AI / LLM     LangChain · RAG · FAISS · FastEmbed · Groq (LLaMA 3.x) · Tavily · Claude Code
ML           XGBoost · Random Forest · scikit-learn · SMOTE · SHAP · pandas · numpy
Backend      FastAPI · REST APIs · PostgreSQL · ClickHouse · SQLite · pytest
Platform     Docker · Kubernetes (manifests) · GitHub Actions · Grafana · Loki
Frontend     React · Next.js · Streamlit
Certifications
Certification Program in Agentic Systems and Design: iHUB DivyaSampark, IIT Roorkee
Generative AI and LLMs: IBM (Coursera, Jul 2026)
Foundations of AI and Machine Learning: Coursera (Jul 2026)
Cloud Computing: NPTEL, IIT Kharagpur
Problem Solving (Intermediate): HackerRank · Verify ↗
Scientific Computing with Python: freeCodeCamp · Verify ↗
Live demos
ResearchMind → researchmind-sigma.vercel.app (web search; PDF upload needs a larger server, see the repo README)
Sakshi Interiors (freelance) → sakshiinteriors.in

📬 aniketjaiswal112002@gmail.com · LinkedIn
