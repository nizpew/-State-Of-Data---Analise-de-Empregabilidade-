
# 📊 Tech Salary Intelligence BR & Global (2021–2024)

Análise avançada do mercado de tecnologia e dados no **Brasil e no mundo**, utilizando dados reais do **State of Data Brazil** e do **Stack Overflow Developer Survey** entre 2021 e 2024.


## Imagens
<img width="1155" height="344" alt="image" src="https://github.com/user-attachments/assets/4fc7b6c8-32b2-4632-add1-545d32bfc606" />


💡 Insight:
A região Sudeste apresenta a maior média de salários, indicando forte concentração de oportunidades e remuneração mais elevada.


---
<p align="center">
  <img 
    src="https://github.com/user-attachments/assets/241236c9-42a0-45e8-81d9-12048be55e6a"
    alt="Dashboard de análise salarial Dark Neon"
    width="1155"
  />
</p>


1. A Hegemonia Americana: O piso salarial (25º percentil) dos EUA é maior que o teto da maioria dos países.
2. O "Sonho da Vaga Remota": Outliers brasileiros com altos salários são minoria privilegiada que trabalha remotamente para o exterior.
3. Brasil vs. Índia: Brasil supera Índia em mediana salarial na área de tech exportação.

---

<img width="1155" height="590" alt="image" src="https://github.com/user-attachments/assets/8f798d41-ab80-4871-9f81-8b0ae1fe9734" />

---

<img width="1155" height="590" alt="image" src="https://github.com/user-attachments/assets/fac98d2d-b650-4140-891c-a28c6e852669" />


---


Este projeto implementa um **pipeline completo de dados**, passando por:
- Coleta automatizada (Kaggle API)
- Limpeza e unificação (ETL)
- Análise estatística e exploratória
- Motor de busca inteligente com NLP
- Visualizações interativas em **Dark Neon (Cyberpunk Theme)**

---

## 🚀 Objetivos do Projeto

- Entender a **dinâmica salarial** no mercado de tecnologia
- Comparar **Brasil vs mercado global**
- Avaliar impactos de:
  - Senioridade
  - Região
  - Trabalho remoto vs presencial
  - Gênero
  - Escolaridade
  - Linguagens e tecnologias
- Demonstrar habilidades práticas em **Data Engineering, Data Science e Analytics**

---

## 🗂️ Fontes de Dados

### 🇧🇷 Brasil — State of Data
- 2021: State of Data Brazil
- 2022: State of Data Brazil
- 2023: State of Data Brazil
- 2024/2025: State of Data Brazil

### 🌍 Global — Stack Overflow Developer Survey
- 2021
- 2022
- 2023
- 2024

Todos os datasets são obtidos automaticamente via **Kaggle API**.

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

````

---

## 🧠 Funcionalidades Principais

### ✅ ETL Automatizado
- Unificação de schemas diferentes entre anos
- Conversão de faixas salariais em valores numéricos
- Padronização de cargos, senioridade, regiões e modelo de trabalho

### 🔎 Motor de Busca NLP
- Busca inteligente por cargos usando:
  - TF-IDF
  - BM25
- Ranking híbrido de relevância
- Ideal para consultas como:
  - `"data scientist"`
  - `"engenheiro de dados"`
  - `"machine learning"`

### 📊 Dashboards e Análises

Alguns exemplos de análises geradas:

- Média salarial por região
- Distribuição salarial por senioridade
- Comparativo global (EUA, Brasil, Índia, Europa)
- Impacto do trabalho remoto
- Arbitragem salarial regional
- Diferença salarial por gênero
- Retorno financeiro por tecnologia (Python, Go, Rust, etc.)
- Educação vs salário (O diploma paga?)

---

## 💡 Principais Insights

- 🇺🇸 **EUA dominam o mercado global**: o piso salarial americano supera o teto da maioria dos países.
- 🌎 **Trabalho remoto reduz desigualdade regional** no Brasil.
- 💰 **Arbitragem salarial**: profissionais do Norte/Nordeste ganham até o dobro no remoto vs presencial.
- 📈 **Senioridade importa mais que diploma** após certo nível.
- ⚖️ **Gap salarial de gênero ainda é evidente**.
- 🧪 **Go e Rust pagam mais**, mas Python domina em volume de vagas.

---

## 🎨 Design System — Dark Neon

- Tema inspirado em **Cyberpunk / Dark Tech**
- Paleta Neon personalizada
- Plotly, Matplotlib e Seaborn ajustados
- Alta legibilidade para dashboards

---

## 🛠️ Tecnologias Utilizadas

- **Python**
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- Scikit-learn
- NLTK
- Rank-BM25
- Kaggle API

---

## ▶️ Como Executar

### 1️⃣ Pré-requisitos
- Python 3.9+
- Conta no Kaggle
- `kaggle.json` configurado

### 2️⃣ Instalar dependências
```bash
pip install pandas numpy kaggle matplotlib seaborn scikit-learn nltk rank-bm25 plotly wordcloud
````

### 3️⃣ Executar

O projeto está pronto para rodar localmente ou no **Google Colab**.

---

## 📌 Observações

* Os dados salariais são **auto-reportados**
* Valores foram normalizados para análise comparativa
* O projeto tem foco **analítico e educacional**

---

## 👤 Autor

Desenvolvido por **Savio** e grupo do CEUB


📊 Data • Python • Analytics • NLP


