<div align="center">

```
╔══════════════════════════════════════════════════════╗
║          J O S A F A   B A R B O S A                 ║
║    Control & Automation Engineer  ·  Data Engineer   ║
╚══════════════════════════════════════════════════════╝
```

[![Profile Views](https://komarev.com/ghpvc/?username=JosafaSants&label=Profile%20views&color=0e75b6&style=flat)](https://github.com/JosafaSants)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-josafa--barbosa--dos--santos-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/josafa-barbosa-dos-santos/)
[![Email](https://img.shields.io/badge/Email-josafabarbosa.santos%40hotmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:josafabarbosa.santos@hotmail.com)

*Engenheiro de automação que migrou para dados — e nunca mais olhou para trás.*  
*Automation engineer who moved into data — and never looked back.*

</div>

---

## 👨‍💻 Sobre mim / About Me

🇧🇷 Formado em **Engenharia de Controle e Automação** pela PUC Minas, hoje trabalho na interseção entre **Engenharia de Dados, Analytics e IA aplicada** — construindo desde pipelines de ETL até sistemas de análise financeira em escala para o setor de viagens. Trabalho diariamente com dados da indústria de **aviação e OTA (Online Travel Agency)**, navegando entre múltiplas fontes heterogêneas e orquestrando camadas de um Data Lake — do dado bruto até o insight pronto para consumo.

🇺🇸 Control & Automation Engineer (PUC Minas) working at the intersection of **Data Engineering, Analytics, and Applied AI** — building everything from ETL pipelines to large-scale financial analytics for the travel industry. I work daily with **aviation and OTA (Online Travel Agency)** data, navigating heterogeneous multi-source environments and orchestrating Data Lake layers from raw ingestion to analytics-ready delivery.

```
🔭  Current focus  →  MCP Servers · LLM-powered apps · Financial reconciliation at scale
🧠  Learning       →  RAG (Retrieval-Augmented Generation) and applied LLM architectures
⚡  Principle      →  Data without context is noise. Context without data is opinion.
📍  Location       →  Brazil
```

---

## 🚀 Projetos em Destaque / Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🔌 Financial Reconciliation MCP Server
🇧🇷 Servidor MCP (Model Context Protocol) em Python rodando em VPS, que expõe dados financeiros reais via linguagem natural para o Claude.ai. Permite que colegas sem conhecimento técnico consultem conciliações, NSUs e relatórios diretamente no chat.

🇺🇸 MCP (Model Context Protocol) server in Python running on a VPS, exposing real financial data via natural language through Claude.ai. Enables non-technical colleagues to query reconciliations, NSUs, and reports directly in chat.

**O que foi construído / What was built:**
- 🇧🇷 Servidor SSE/MCP com FastAPI + Python / 🇺🇸 SSE/MCP server with FastAPI + Python
- 🇧🇷 Ferramentas de consulta a AWS Athena e MySQL em tempo real / 🇺🇸 Real-time query tools for AWS Athena and MySQL
- 🇧🇷 Integração com Claude.ai via MCP remoto / 🇺🇸 Claude.ai integration via remote MCP
- 🇧🇷 Autenticação e controle de acesso por ambiente / 🇺🇸 Authentication and environment-based access control

`Python` · `FastAPI` · `MCP Protocol` · `AWS Athena` · `MySQL` · `Claude API`

</td>
<td width="50%" valign="top">

### 🧠 IntelliDoc RAG Multimodal
🇧🇷 Sistema completo de *Retrieval-Augmented Generation* que ingere PDFs e imagens, transforma em embeddings semânticos e responde perguntas em linguagem natural — com avaliação automática de fidelidade via RAGAS (score médio 0.81).

🇺🇸 Full *Retrieval-Augmented Generation* system that ingests PDFs and images, converts them into semantic embeddings, and answers questions in natural language — with automatic faithfulness evaluation via RAGAS (average score 0.81).

**O que foi construído / What was built:**
- 🇧🇷 Pipeline RAG end-to-end com LangChain + Pinecone + GPT-4o-mini / 🇺🇸 End-to-end RAG pipeline with LangChain + Pinecone + GPT-4o-mini
- 🇧🇷 OCR de imagens com Tesseract 5.5 integrado ao mesmo pipeline / 🇺🇸 Image OCR with Tesseract 5.5 integrated into the same pipeline
- 🇧🇷 Ingestão incremental por hash MD5 — zero re-processamento / 🇺🇸 Incremental ingestion via MD5 hash — zero reprocessing
- 🇧🇷 Interface Streamlit com upload, chat e scores RAGAS em tempo real / 🇺🇸 Streamlit interface with upload, chat, and live RAGAS scores

`Python` · `LangChain` · `Pinecone` · `OpenAI` · `Tesseract` · `Streamlit` · `RAGAS`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 Autonomous Multi-Agent Orchestrator
🇧🇷 Sistema de 3 agentes em pipeline (LangGraph) que responde perguntas em linguagem natural sobre dados reais do Olist — traduz para SQL, executa, analisa padrões e devolve relatório narrativo executivo. Cada decisão é auditável via trilha de debug.

🇺🇸 3-agent pipeline (LangGraph) that answers natural language questions about real Olist data — translates to SQL, executes, analyzes patterns, and returns an executive narrative report. Every decision is auditable via a debug trail.

**O que foi construído / What was built:**
- 🇧🇷 3 agentes especializados com estado tipado via TypedDict / 🇺🇸 3 specialized agents with typed state via TypedDict
- 🇧🇷 Agente SQL com auto-correção em até 3 tentativas / 🇺🇸 SQL Agent with auto-correction up to 3 retries
- 🇧🇷 Edge condicional no grafo LangGraph para tratamento de erros / 🇺🇸 Conditional edge in LangGraph for error handling
- 🇧🇷 Trilha de debug completa: SQL, JSON de insights e log de tentativas / 🇺🇸 Full debug trail: SQL, insights JSON, and retry log

`Python` · `LangGraph` · `GPT-4o-mini` · `DuckDB` · `Streamlit` · `Pydantic`

</td>
<td width="50%" valign="top">

### 📊 E-commerce Strategic Dashboard
🇧🇷 Dashboard executivo construído sobre 96k pedidos reais do Olist — EDA em Python, modelagem semântica com dbt e visualização em Power BI. Crescimento de 20x em 24 meses documentado com insights estratégicos por região.

🇺🇸 Executive dashboard built on 96k real Olist orders — Python EDA, semantic modeling with dbt, and Power BI visualization. 20x growth in 24 months documented with strategic regional insights.

**O que foi construído / What was built:**
- 🇧🇷 EDA documentada em notebooks públicos com identificação de anomalia crítica / 🇺🇸 EDA documented in public notebooks with critical anomaly detection
- 🇧🇷 Camada semântica dbt + DuckDB: 3 modelos, 4/4 testes passando / 🇺🇸 dbt + DuckDB semantic layer: 3 models, 4/4 tests passing
- 🇧🇷 Dashboard com 3 páginas orientadas a decisão / 🇺🇸 3-page decision-oriented dashboard
- 🇧🇷 Ticket médio Norte 50% superior ao de SP — oportunidade identificada / 🇺🇸 Northern states ticket 50% above SP average — opportunity identified

`Python` · `dbt-core` · `DuckDB` · `Power BI` · `pandas` · `seaborn`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🚀 RideStream Analytics Lakehouse
🇧🇷 Pipeline de streaming em tempo real inspirado nos desafios de empresas como Uber e 99 — eventos de corridas ingeridos via Redpanda, processados com Spark Structured Streaming e organizados em arquitetura Medalhão (Bronze → Silver → Gold).

🇺🇸 Real-time streaming pipeline inspired by challenges at companies like Uber and 99 — ride events ingested via Redpanda, processed with Spark Structured Streaming, and organized in a Medallion architecture (Bronze → Silver → Gold).

**O que foi construído / What was built:**
- 🇧🇷 Stack cloud-agnostic local: Redpanda + MinIO + Prometheus + Grafana / 🇺🇸 Local cloud-agnostic stack: Redpanda + MinIO + Prometheus + Grafana
- 🇧🇷 Camada Gold com dbt-duckdb: 6 modelos SQL, 15 testes de qualidade / 🇺🇸 Gold layer with dbt-duckdb: 6 SQL models, 15 quality tests
- 🇧🇷 DataSentinel: catálogo inteligente com geração de docs via GPT-4o-mini / 🇺🇸 DataSentinel: intelligent catalog with auto-docs via GPT-4o-mini
- 🇧🇷 Pipeline validado end-to-end: Producer → Redpanda → Spark → MinIO / 🇺🇸 End-to-end validated pipeline: Producer → Redpanda → Spark → MinIO

`Python` · `Redpanda` · `Apache Spark` · `Delta Lake` · `MinIO` · `dbt` · `Docker` · `Grafana`

</td>
<td width="50%" valign="top">

### 🗂️ Obsidian Knowledge Base Updater
🇧🇷 Sistema CLI para manter um vault Obsidian atualizado com documentações técnicas oficiais — busca, classifica e reorganiza arquivos `.md` usando IA local (Ollama) em 6 domínios técnicos. Ferramenta de produtividade para engenheiros de dados.

🇺🇸 CLI system to keep an Obsidian vault up to date with official technical documentation — fetches, classifies, and reorganizes `.md` files using local AI (Ollama) across 6 technical domains. Productivity tool built for data engineers.

**O que foi construído / What was built:**
- 🇧🇷 4 comandos CLI: `fetch`, `reorganize`, `status`, `update` / 🇺🇸 4 CLI commands: `fetch`, `reorganize`, `status`, `update`
- 🇧🇷 Classificação de arquivos com Ollama (qwen2.5-coder) com threshold configurável / 🇺🇸 File classification with Ollama (qwen2.5-coder) with configurable threshold
- 🇧🇷 Dry-run por padrão — nenhum arquivo movido sem confirmação / 🇺🇸 Dry-run by default — no files moved without confirmation
- 🇧🇷 Domínios cobertos: SQL/Athena, DAX/Power BI, Python, Claude Code/MCP, Security / 🇺🇸 Domains covered: SQL/Athena, DAX/Power BI, Python, Claude Code/MCP, Security

`Python` · `Ollama` · `Obsidian` · `CLI` · `Markdown`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧾 Reconciliação Financeira Automatizada / Automated Financial Reconciliation
🇧🇷 Script Python de conciliação cruzando dados do AWS Athena com arquivos Excel — matching por NSU e código de autorização para relatórios de pagamentos em escala.

🇺🇸 Python reconciliation script crossing AWS Athena data with Excel files — NSU and authorization code matching for large-scale payment reports.

**O que foi construído / What was built:**
- 🇧🇷 Arquitetura com dataclasses imutáveis e funções puras / 🇺🇸 Architecture with immutable dataclasses and pure functions
- 🇧🇷 Conexão Athena via SQLAlchemy (`awsathena://` dialect) / 🇺🇸 Athena connection via SQLAlchemy (`awsathena://` dialect)
- 🇧🇷 Cross-reference MySQL ↔ Athena em escala / 🇺🇸 MySQL ↔ Athena cross-reference at scale

`Python` · `SQLAlchemy` · `AWS Athena` · `MySQL` · `Pandas` · `openpyxl`

</td>
<td width="50%" valign="top">

### 📊 GMV Forecasting — LSTM Neural Network
🇧🇷 Sistema de previsão de GMV com rede neural LSTM conectada ao AWS Athena, com ensemble adaptativo e análise de sazonalidade histórica.

🇺🇸 GMV forecasting system with an LSTM neural network connected to AWS Athena, featuring adaptive ensemble and historical seasonality analysis.

**O que foi construído / What was built:**
- 🇧🇷 Pipeline de features com EWMA e sazonalidade por perfil de mês/dia / 🇺🇸 Feature pipeline with EWMA and month/weekday seasonality profiles
- 🇧🇷 Ensemble adaptativo para projeções futuras / 🇺🇸 Adaptive ensemble for future projections
- 🇧🇷 Relatórios com intervalos de confiança / 🇺🇸 Reports with confidence intervals

`Python` · `TensorFlow/Keras` · `AWS Athena` · `Pandas` · `LSTM`

</td>
</tr>
</table>

---

## 🏗️ Arquitetura que trabalho no dia a dia / Daily Architecture

> 🇧🇷 Trabalho com uma arquitetura Medallion sobre AWS Athena, integrando múltiplas fontes transacionais heterogêneas num Data Lake centralizado — do dado bruto até o insight analítico pronto para consumo. Camada de IA sobre os dados via MCP Servers e LLMs.
>
> 🇺🇸 I work with a Medallion architecture on AWS Athena, integrating multiple heterogeneous transactional sources into a centralized Data Lake — from raw ingestion to analytics-ready delivery. AI layer on top via MCP Servers and LLMs.

```
  TRANSACTIONAL SOURCES          DATA LAKE (AWS Athena)         CONSUMPTION
  ─────────────────────    ──────────────────────────────    ─────────────────
                           │                              │
  ┌──────────────────┐     │  ┌────────┐  ┌──────────┐  │   Power BI
  │  Relational DBs  │────▶│  │ BRONZE │─▶│  SILVER  │  │   Ad-hoc queries
  │  MySQL / MSSQL   │     │  │  raw + │  │normalized│  │   Financial reports
  └──────────────────┘     │  │  PII   │  │& joined  │  │   Reconciliation
                           │  └────────┘  └────┬─────┘  │
  ┌──────────────────┐     │                   │         │   ┌─────────────┐
  │   Delta Lake     │────▶│               ┌───▼──────┐  │──▶│  MCP Server │
  │  (event-driven)  │     │               │   GOLD   │  │   │  (Claude AI)│
  └──────────────────┘     │               │aggregated│  │   └─────────────┘
                           │               │& curated │  │
  ┌──────────────────┐     │               └──────────┘  │
  │  Legacy systems  │────▶│                              │
  │  + ERP adapters  │     └──────────────────────────────┘
  └──────────────────┘
```

---

## 🛠️ Stack Técnica / Tech Stack

### Linguagens / Languages
<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=amazondynamodb&logoColor=white"/>
<img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white"/>
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white"/>
</p>

### Dados & Bancos / Data & Databases
<p>
<img src="https://img.shields.io/badge/AWS_Athena-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white"/>
<img src="https://img.shields.io/badge/Delta_Lake-003366?style=for-the-badge&logo=databricks&logoColor=white"/>
<img src="https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black"/>
<img src="https://img.shields.io/badge/Pinecone-00BFA5?style=for-the-badge&logoColor=white"/>
</p>
<p>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/dbt--core-FF694B?style=for-the-badge&logo=dbt&logoColor=white"/>
<img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white"/>
<img src="https://img.shields.io/badge/openpyxl-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white"/>
</p>

### Streaming & Observabilidade / Streaming & Observability
<p>
<img src="https://img.shields.io/badge/Redpanda-E6363A?style=for-the-badge&logo=redpanda&logoColor=white"/>
<img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white"/>
<img src="https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white"/>
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"/>
<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
</p>

### BI & Visualização / BI & Visualization
<p>
<img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/Power_Query_M-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Seaborn-4C9BE8?style=for-the-badge&logo=python&logoColor=white"/>
</p>

### Cloud & Infraestrutura / Cloud & Infrastructure
<p>
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Amazon_Athena-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Amazon_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS_Glue-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/MCP_Protocol-6B57FF?style=for-the-badge&logoColor=white"/>
</p>

### Frontend & Web
<p>
<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"/>
</p>

### IA / ML & LLMs
<p>
<img src="https://img.shields.io/badge/Claude_API-6B57FF?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
<img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/MCP_Servers-6B57FF?style=for-the-badge&logoColor=white"/>
</p>
<p>
<img src="https://img.shields.io/badge/RAG-00BFA5?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Pinecone-00BFA5?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/RAGAS-412991?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Tesseract_OCR-0077B5?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Vector_Databases-6B57FF?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Claude_Code-6B57FF?style=for-the-badge&logoColor=white"/>
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://img.shields.io/badge/Linguagem_Principal-Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Contribuições-71+-0e75b6?style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-JosafaSants-181717?style=for-the-badge&logo=github&logoColor=white"/>
</p>

---

## 🌐 Redes / Connect

<p align="left">
<a href="https://www.github.com/JosafaSants" target="_blank" rel="noreferrer">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" />
    <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" width="32" height="32" alt="GitHub" title="GitHub" />
  </picture>
</a>
&nbsp;&nbsp;
<a href="https://www.linkedin.com/in/josafa-barbosa-dos-santos/" target="_blank" rel="noreferrer">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin.svg" />
    <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin.svg" width="32" height="32" alt="LinkedIn" title="LinkedIn" />
  </picture>
</a>
</p>

---

<div align="center">

*"Engenharia de dados é sobre transformar caos em estrutura — um pipeline de cada vez."*  
*"Data engineering is about turning chaos into structure — one pipeline at a time."*

</div>
