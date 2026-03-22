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
🔭  Current focus  →  Aviation & OTA data analytics — financial, payments & reconciliation
🧠  Learning       →  RAG (Retrieval-Augmented Generation) and applied LLM architectures
⚡  Principle      →  Data without context is noise. Context without data is opinion.
📍  Location       →  Brazil
```

---

## 🚀 Projetos em Destaque

<table>
<tr>
<td width="50%" valign="top">

### ✈️ OTA Aviation Sales Report
Pipeline de consolidação de dados de vendas de voos de múltiplas plataformas em um único relatório Excel estilizado — permitindo comparação cruzada de precificação, volume e tendências de mercado.

**O que foi construído:**
- Extração de dados de múltiplas fontes heterogêneas
- Normalização e cruzamento de schemas diferentes
- Relatório Excel com formatação condicional e visual profissional

`Python` · `Pandas` · `openpyxl` · `ETL` · `AWS Athena`

</td>
<td width="50%" valign="top">

### 🗄️ SQL Knowledge Base — Travel Data Engineering
Base de conhecimento técnico estruturada com **+1.900 linhas** cobrindo todos os sistemas de dados do ecossistema de travel OTA: queries prontas, dicionários de status, mapeamentos de schemas, padrões de performance e arquitetura do Data Lake (Bronze → Silver → Gold).

**25 domínios cobertos:** Financeiro, Pagamentos, Conciliação, Vouchers, NFSe, Netsuite, Delta Lake, e mais.

`AWS Athena` · `MySQL` · `SQL Server` · `Delta Lake`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 RAG Pipeline (em desenvolvimento)
Aplicação de **Retrieval-Augmented Generation** para consulta inteligente sobre bases de conhecimento técnico — conectando LLMs com contexto específico de domínio para respostas precisas sobre sistemas de dados.

`Python` · `LangChain / LlamaIndex` · `Vector DB` · `LLM`

</td>
<td width="50%" valign="top">
</td>
</tr>
</table>

---

## 🏗️ Arquitetura que trabalho no dia a dia / Daily Architecture

> 🇧🇷 Trabalho com uma arquitetura Medallion sobre AWS Athena, integrando múltiplas fontes transacionais heterogêneas num Data Lake centralizado — do dado bruto até o insight analítico pronto para consumo.
>
> 🇺🇸 I work with a Medallion architecture on AWS Athena, integrating multiple heterogeneous transactional sources into a centralized Data Lake — from raw ingestion all the way to analytics-ready consumption.

```
  TRANSACTIONAL SOURCES          DATA LAKE (AWS Athena)         CONSUMPTION
  ─────────────────────    ──────────────────────────────    ─────────────────
                           │                              │
  ┌──────────────────┐     │  ┌────────┐  ┌──────────┐  │   Dashboards
  │  Relational DBs  │────▶│  │ BRONZE │─▶│  SILVER  │  │   Ad-hoc queries
  │  MySQL / MSSQL   │     │  │  raw + │  │normalized│  │   Financial reports
  └──────────────────┘     │  │  PII   │  │& joined  │  │   Reconciliation
                           │  └────────┘  └────┬─────┘  │
  ┌──────────────────┐     │                   │         │
  │   Delta Lake     │────▶│               ┌───▼──────┐  │
  │  (event-driven)  │     │               │   GOLD   │  │
  └──────────────────┘     │               │aggregated│  │
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

**Ferramentas de dados:** `Pandas` · `openpyxl` · `python-docx` · `ETL pipelines`

### Cloud & Infraestrutura
<p>
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/aws-colored-dark.svg" width="36" height="36" alt="AWS" title="AWS"/>
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/azure-colored.svg" width="36" height="36" alt="Azure" title="Azure"/>
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/linux-colored.svg" width="36" height="36" alt="Linux" title="Linux"/>
</p>

**AWS:** `Athena` · `S3 (Data Lake)` · `Glue`

### IA / ML & Ferramentas
<p>
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/tensorflow-colored.svg" width="36" height="36" alt="TensorFlow" title="TensorFlow"/>
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/visualstudiocode-colored.svg" width="36" height="36" alt="VS Code" title="VS Code"/>
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/figma-colored.svg" width="36" height="36" alt="Figma" title="Figma"/>
<img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/arduino-colored.svg" width="36" height="36" alt="Arduino" title="Arduino"/>
</p>

**Em aprendizado ativo:** `RAG` · `LangChain` · `Vector Databases` · `LLM fine-tuning`

---

## 📊 GitHub Stats

<p align="center">
  <img height="160em" src="https://github-readme-stats.vercel.app/api?username=JosafaSants&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
  <img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=JosafaSants&layout=compact&langs_count=8&theme=tokyonight"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=JosafaSants&theme=tokyonight" alt="streak stats"/>
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
