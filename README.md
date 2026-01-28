

# 📊 Tech Salary Intelligence — Brasil & Global (2021–2024)

> **Sistema de inteligência salarial para o mercado de tecnologia**, combinando **Data Engineering, NLP e Analytics** para extrair insights acionáveis a partir de dados reais do Brasil e do mundo.

Este projeto analisa dados do **State of Data Brazil** e do **Stack Overflow Developer Survey** (2021–2024), explorando **salários, senioridade, regiões, trabalho remoto e tecnologias** por meio de um **pipeline completo de dados com motor de busca inteligente em NLP**.

---

## 🔍 Visão Geral

<img width="1155" height="344" alt="image" src="https://github.com/user-attachments/assets/4fc7b6c8-32b2-4632-add1-545d32bfc606" />

💡 **Insight-chave**
A região Sudeste apresenta a maior média salarial no Brasil, indicando forte concentração de oportunidades e maior remuneração.

---

<p align="center">
  <img 
    src="https://github.com/user-attachments/assets/241236c9-42a0-45e8-81d9-12048be55e6a"
    alt="Dashboard de análise salarial Dark Neon"
    width="1155"
  />
</p>

### Principais leituras do dashboard:

1. **Hegemonia Americana** — O piso salarial (25º percentil) dos EUA supera o teto da maioria dos países.
2. **O “sonho da vaga remota”** — Brasileiros com salários muito altos são outliers que trabalham remotamente para o exterior.
3. **Brasil vs Índia** — O Brasil apresenta mediana salarial superior à Índia na exportação de trabalho em tecnologia.

---

<img width="1155" height="590" alt="image" src="https://github.com/user-attachments/assets/8f798d41-ab80-4871-9f81-8b0ae1fe9734" />

---

<img width="1155" height="590" alt="image" src="https://github.com/user-attachments/assets/fac98d2d-b650-4140-891c-a28c6e852669" />

---

## 🧠 O que este projeto entrega (em termos de engenharia)

Este repositório **não é apenas um notebook de análise**. Ele implementa um **pipeline completo de inteligência de dados**, composto por:

* 📦 **Ingestão automatizada de dados** (Kaggle API)
* 🧹 **ETL robusto e padronização entre múltiplos anos**
* 📊 **Análise estatística e exploratória**
* 🧠 **Motor de busca inteligente com NLP**
* 🎨 **Dashboards interativos em Dark Neon (Cyberpunk Theme)**

---

## 🧱 Arquitetura do Projeto

```
📦 Data Ingestion (Kaggle API)
        ↓
🧹 ETL & Padronização
        ↓
📊 Análise Estatística
        ↓
🧠 NLP Search Engine (TF-IDF + BM25)
        ↓
🎨 Visualizações Dark Neon
```

---

## 🚀 Objetivos do Projeto

* Entender a **dinâmica salarial** no mercado de tecnologia
* Comparar **Brasil vs mercado global**
* Avaliar impactos de:

  * Senioridade
  * Região
  * Trabalho remoto vs presencial
  * Gênero
  * Escolaridade
  * Linguagens e tecnologias
* Demonstrar habilidades práticas em:

  * **Data Engineering**
  * **Data Science**
  * **Analytics**
  * **NLP aplicado**

---

## 🔎 Funcionalidades Principais

### ✅ ETL Automatizado

* Unificação de schemas inconsistentes entre anos
* Conversão de faixas salariais em valores numéricos
* Padronização de:

  * cargos
  * senioridade
  * regiões
  * modelo de trabalho

### 🔎 Motor de Busca com NLP

Busca inteligente por cargos e perfis usando:

* **TF-IDF**
* **BM25**
* Ranking híbrido de relevância

Exemplos de consultas:

* `"data scientist"`
* `"engenheiro de dados"`
* `"machine learning"`

---

## 📊 Análises Disponíveis

* Média salarial por região
* Distribuição salarial por senioridade
* Comparativo global (EUA, Brasil, Índia, Europa)
* Impacto do trabalho remoto
* Arbitragem salarial regional
* Diferença salarial por gênero
* Retorno financeiro por tecnologia (Python, Go, Rust, etc.)
* Educação vs salário (*o diploma realmente paga?*)

---

## 💡 Principais Insights

* 🇺🇸 **EUA dominam o mercado global** — o piso salarial americano supera o teto da maioria dos países.
* 🌎 **Trabalho remoto reduz desigualdade regional** no Brasil.
* 💰 **Arbitragem salarial** — profissionais do Norte/Nordeste podem ganhar até o dobro no modelo remoto.
* 📈 **Senioridade pesa mais que diploma** após certo nível.
* ⚖️ **Gap salarial de gênero** ainda é relevante.
* 🧪 **Go e Rust pagam mais**, enquanto Python domina em volume de vagas.

---

## 🎨 Design System — Dark Neon

* Tema inspirado em **Cyberpunk / Dark Tech**
* Paleta Neon personalizada
* Plotly, Matplotlib e Seaborn ajustados
* Alta legibilidade para dashboards analíticos

---

## 🗂️ Fontes de Dados

### 🇧🇷 State of Data Brazil

* 2021
* 2022
* 2023
* 2024/2025

### 🌍 Stack Overflow Developer Survey

* 2021
* 2022
* 2023
* 2024

📌 Todos os datasets são obtidos automaticamente via **Kaggle API**.

---

## 🛠️ Tecnologias Utilizadas

* **Python**
* Pandas, NumPy
* Matplotlib, Seaborn, Plotly
* Scikit-learn
* NLTK
* Rank-BM25
* Kaggle API

---

## ▶️ Como Executar

### 1️⃣ Pré-requisitos

* Python 3.9+
* Conta no Kaggle
* Arquivo `kaggle.json` configurado

### 2️⃣ Instalar dependências

```bash
pip install pandas numpy kaggle matplotlib seaborn scikit-learn nltk rank-bm25 plotly wordcloud
```

### 3️⃣ Execução

O projeto pode ser executado localmente ou diretamente no **Google Colab**.

---

## 📌 Observações

* Dados salariais são **auto-reportados**
* Valores foram normalizados para análise comparativa
* Projeto com foco **analítico, educacional e demonstrativo de engenharia**

---

## 👤 Autor

Desenvolvido por **Sávio** — Ciência de Dados, IA e NLP
em colaboração com o grupo do **CEUB**

📊 Data • Python • Analytics • NLP
