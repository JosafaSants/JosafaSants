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

### 📊 E-commerce Strategic Dashboard
Dashboard executivo construído sobre 96k pedidos reais do marketplace Olist — EDA em Python, modelagem semântica com dbt e visualização em Power BI, seguindo o formato STAR para documentação de resultados de negócio.

**O que foi construído:**
- EDA documentada em notebooks públicos com identificação de anomalia crítica de dados
- Camada semântica com dbt + DuckDB: 3 modelos governados, 4/4 testes de qualidade passando
- Dashboard executivo com 3 páginas orientadas a decisão (receita, geografia, qualidade operacional)
- Insights: crescimento 20x em 24 meses, ticket médio Norte 50% superior ao de SP

`Python` · `dbt-core` · `DuckDB` · `Power BI` · `pandas` · `seaborn`

</td>
<td width="50%" valign="top">

### ✈️ OTA Aviation Sales Report
Pipeline de consolidação de dados de vendas de voos de múltiplas plataformas (123Milhas + MaxMilhas) em um único relatório Excel estilizado com comparação cruzada de precificação e volume.

**O que foi construído:**
- Extração de múltiplas fontes heterogêneas (Athena + MySQL)
- Normalização e cruzamento de schemas distintos
- Relatório Excel com formatação condicional e visual profissional

`Python` · `Pandas` · `openpyxl` · `ETL` · `AWS Athena`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🗄️ SQL Knowledge Base — Travel Data Engineering
Base de conhecimento técnico estruturada com **+1.900 linhas** cobrindo todos os sistemas de dados do ecossistema de travel OTA: queries prontas, dicionários de status, mapeamentos de schemas, padrões de performance e arquitetura Medallion.

**25 domínios cobertos:** Financeiro, Pagamentos, Conciliação, Vouchers, NFSe, Netsuite, Delta Lake, e mais.

`AWS Athena` · `MySQL` · `SQL Server` · `Delta Lake`

</td>
<td width="50%" valign="top">

### 📦 WorkFlow Repository — Dev Environment
Repositório privado estruturado como ambiente de desenvolvimento integrado com VS Code, DBeaver e AWS Athena — centralizando scripts SQL, arquivos de dados e automações.

**O que foi construído:**
- Configuração de VS Code como cliente de banco de dados
- Integração com extensão SQL Tools + driver Athena
- Organização de scripts por domínio de negócio

`VS Code` · `DBeaver` · `AWS Athena` · `Git`

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
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=amazondynamodb&logoColor=white"/>
<img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white"/>
<img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
<img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white"/>
</p>

### Dados & Bancos
<p>
<img src="https://img.shields.io/badge/AWS_Athena-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white"/>
<img src="https://img.shields.io/badge/Delta_Lake-003366?style=for-the-badge&logo=databricks&logoColor=white"/>
<img src="https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black"/>
<img src="https://img.shields.io/badge/Pinecone-00BFA5?style=for-the-badge&logoColor=white"/>
</p>

<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/dbt--core-FF694B?style=for-the-badge&logo=dbt&logoColor=white"/>
<img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white"/>
<img src="https://img.shields.io/badge/openpyxl-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white"/>

### Streaming & Observabilidade
<p>
<img src="https://img.shields.io/badge/Redpanda-E6363A?style=for-the-badge&logo=redpanda&logoColor=white"/>
<img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white"/>
<img src="https://img.shields.io/badge/MinIO-C72E49?style=for-the-badge&logo=minio&logoColor=white"/>
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white"/>
<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
</p>

### BI & Visualização
<p>
<img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/Power_Query_M-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Seaborn-4C9BE8?style=for-the-badge&logo=python&logoColor=white"/>
</p>

### Cloud & Infraestrutura
<p>
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/MCP_Protocol-6B57FF?style=for-the-badge&logoColor=white"/>
</p>

<img src="https://img.shields.io/badge/Amazon_Athena-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/Amazon_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS_Glue-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS_IAM-DD344C?style=for-the-badge&logo=amazonaws&logoColor=white"/>

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
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white"/>
<img src="https://img.shields.io/badge/MCP_Servers-6B57FF?style=for-the-badge&logoColor=white"/>
</p>

<img src="https://img.shields.io/badge/RAG-00BFA5?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Pinecone-00BFA5?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/RAGAS-412991?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Tesseract_OCR-0077B5?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Vector_Databases-6B57FF?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Claude_Code-6B57FF?style=for-the-badge&logoColor=white"/>

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
