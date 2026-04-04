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
Servidor MCP (Model Context Protocol) em Python rodando em VPS, que expõe dados financeiros reais via linguagem natural para o Claude.ai. Permite que colegas sem conhecimento técnico consultem conciliações, NSUs e relatórios diretamente no chat.

**O que foi construído:**
- Servidor SSE/MCP com FastAPI + Python
- Ferramentas de consulta a AWS Athena e MySQL em tempo real
- Integração com Claude.ai via MCP remoto (ngrok/VPS)
- Autenticação e controle de acesso por ambiente

`Python` · `FastAPI` · `MCP Protocol` · `AWS Athena` · `MySQL` · `Claude API`

</td>
<td width="50%" valign="top">

### 🧠 IntelliDoc RAG Multimodal
Sistema completo de *Retrieval-Augmented Generation* que ingere PDFs e imagens, transforma em embeddings semânticos e responde perguntas em linguagem natural — com avaliação automática de fidelidade via RAGAS (score médio 0.81).

**O que foi construído:**
- Pipeline RAG end-to-end com LangChain + Pinecone + GPT-4o-mini
- OCR de imagens com Tesseract 5.5 integrado ao mesmo pipeline
- Ingestão incremental por hash MD5 — zero re-processamento desnecessário
- Interface Streamlit com upload, chat e scores RAGAS em tempo real

`Python` · `LangChain` · `Pinecone` · `OpenAI` · `Tesseract` · `Streamlit` · `RAGAS`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 LinkedIn Profile Analyzer (Claude-powered)
Aplicação web em React que utiliza a API do Claude para analisar perfis do LinkedIn, pontuar seções e gerar recomendações de melhoria personalizadas em tempo real.

**O que foi construído:**
- Interface React com análise por seção (headline, sobre, experiência, skills)
- Score estruturado com sugestões acionáveis
- Integração direta com a API Anthropic (claude-sonnet)
- UX orientada a resultados práticos para profissionais

`React` · `Claude API` · `Anthropic SDK` · `JavaScript`

</td>
<td width="50%" valign="top">

### 📊 GMV Forecasting — LSTM Neural Network
Sistema de previsão de GMV (Gross Merchandise Value) com rede neural LSTM conectada ao AWS Athena, com ensemble adaptativo e análise de sazonalidade histórica.

**O que foi construído:**
- Pipeline de features com EWMA (Exponential Weighted Moving Average)
- Sazonalidade histórica por perfil de mês/dia da semana
- Ensemble adaptativo para projeções futuras
- Geração de relatórios com intervalos de confiança

`Python` · `TensorFlow/Keras` · `AWS Athena` · `Pandas` · `LSTM`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧾 Reconciliação Financeira Automatizada
Script Python de conciliação cruzando dados do AWS Athena com arquivos Excel locais — matching por NSU e código de autorização para relatórios de pagamentos.

**O que foi construído:**
- Arquitetura refatorada com dataclasses imutáveis e funções puras
- Conexão Athena via SQLAlchemy (`awsathena://` dialect)
- Cross-reference MySQL ↔ Athena em escala
- Tratamento de certificados SSL corporativos (Zscaler/proxy)

`Python` · `SQLAlchemy` · `AWS Athena` · `MySQL` · `Pandas` · `openpyxl`

</td>
<td width="50%" valign="top">

### 📈 Power BI — Voucher Lifecycle Query (Power Query / M)
Otimização de queries complexas em M Language para rastreamento do ciclo de vida de vouchers em quatro tipos de produto, com lógica de incrementalidade e particionamento mensal.

**O que foi construído:**
- Queries particionadas por mês em arquivos `.m` separados
- Eventos rastreados: Gerado, Tentativa, Utilizado, Expirado, Cancelado
- Incremental refresh com filtro por parâmetro de data
- Padrão de código com task-tags `MDD-000` e sem alinhamentos longos

`Power Query (M)` · `AWS Athena` · `Power BI` · `Presto/Trino SQL`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ✈️ OTA Aviation Sales Report
Pipeline de consolidação de dados de vendas de voos de múltiplas plataformas (123Milhas + MaxMilhas) em um único relatório Excel estilizado com comparação cruzada de precificação e volume.

**O que foi construído:**
- Extração de múltiplas fontes heterogêneas (Athena + MySQL)
- Normalização e cruzamento de schemas distintos
- Relatório Excel com formatação condicional e visual profissional

`Python` · `Pandas` · `openpyxl` · `ETL` · `AWS Athena`

</td>
<td width="50%" valign="top">

### 🗄️ SQL Knowledge Base — Travel Data Engineering
Base de conhecimento técnico estruturada com **+1.900 linhas** cobrindo todos os sistemas de dados do ecossistema de travel OTA: queries prontas, dicionários de status, mapeamentos de schemas, padrões de performance e arquitetura Medallion.

**25 domínios cobertos:** Financeiro, Pagamentos, Conciliação, Vouchers, NFSe, Netsuite, Delta Lake, e mais.

`AWS Athena` · `MySQL` · `SQL Server` · `Delta Lake`

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

## 🛠️ Stack Técnica

### Linguagens
<p>
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/python-colored.svg" width="36" height="36" alt="Python" title="Python"/>
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/javascript-colored.svg" width="36" height="36" alt="JavaScript" title="JavaScript"/>
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/c-colored.svg" width="36" height="36" alt="C" title="C"/>
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/cplusplus-colored.svg" width="36" height="36" alt="C++" title="C++"/>
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/csharp-colored.svg" width="36" height="36" alt="C#" title="C#"/>
</p>

### Dados & Bancos
<p>
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/mysql-colored.svg" width="36" height="36" alt="MySQL" title="MySQL"/>
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/postgresql-colored.svg" width="36" height="36" alt="PostgreSQL" title="PostgreSQL"/>
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/oracle-colored.svg" width="36" height="36" alt="Oracle" title="Oracle"/>
</p>

**SQL avançado em:** `AWS Athena (Presto/Trino)` · `MySQL` · `SQL Server` · `Delta Lake`

**Ferramentas de dados:** `Pandas` · `openpyxl` · `SQLAlchemy` · `python-docx` · `ETL pipelines`

### Frontend & Web
<p>
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/react-colored.svg" width="36" height="36" alt="React" title="React"/>
</p>

`React` · `Vite` · `REST APIs` · `Claude API (Anthropic SDK)`

### Cloud & Infraestrutura
<p>
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/aws-colored-dark.svg" width="36" height="36" alt="AWS" title="AWS"/>
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/linux-colored.svg" width="36" height="36" alt="Linux" title="Linux"/>
</p>

**AWS:** `Athena` · `S3 (Data Lake)` · `Glue` · `IAM`

**Infra:** `VPS` · `ngrok` · `FastAPI` · `MCP Protocol (SSE)`

### IA / ML & LLMs
<p>
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/tensorflow-colored.svg" width="36" height="36" alt="TensorFlow" title="TensorFlow"/>
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/visualstudiocode-colored.svg" width="36" height="36" alt="VS Code" title="VS Code"/>
</p>

**Produção:** `Claude API` · `MCP Servers` · `LSTM (TensorFlow/Keras)`

**Aprendizado ativo:** `RAG` · `LangChain` · `LlamaIndex` · `Vector Databases` · `Claude Code`

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://img.shields.io/badge/Linguagem_Principal-Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Contribuições-71+-0e75b6?style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-JosafaSants-181717?style=for-the-badge&logo=github&logoColor=white"/>
</p>

---

## 🌐 Redes

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
