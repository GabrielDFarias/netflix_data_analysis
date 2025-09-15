# 🎬📊 Análise de Dados da Netflix com Polars

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Polars](https://img.shields.io/badge/Polars-Dataframe-orange)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow)
![License](https://img.shields.io/badge/License-MIT-green)


## ✨ Descrição

Este projeto foi desenvolvido para **explorar e aprender a biblioteca [Polars](https://www.pola.rs/)**, uma alternativa moderna e extremamente rápida ao Pandas para manipulação de dados.

A ideia é **começar simples** (carregando e limpando dados da Netflix) e **evoluir progressivamente** até análises mais avançadas, comparações de performance e geração de relatórios detalhados.

💡 É um projeto **didático**, mas estruturado para parecer **profissional**, servindo tanto como **portfólio** quanto como **aprendizado prático**.


## 🚀 O que você vai encontrar aqui

✔️ Estrutura organizada do projeto (data, notebooks, src, reports).
✔️ Limpeza e transformação de dados reais da Netflix.
✔️ Análises exploratórias e avançadas (tendências, diretores, países, etc.).
✔️ Visualizações gráficas (lançamentos por ano, distribuição de duração, etc.).
✔️ Relatórios exportáveis em Markdown e PDF.
✔️ Comparações de performance entre **Polars vs Pandas**.


## 📂 Estrutura do Projeto

```bash
polars-netflix-analysis/
│── data/                # Datasets (CSV, Parquet, etc.)
│── notebooks/           # Jupyter Notebooks para exploração
│── reports/             # Relatórios e visualizações finais
│── src/                 # Scripts organizados (ETL, análise, gráficos)
│── README.md            # Documentação principal
│── requirements.txt     # Dependências do projeto
```

---

## 📊 Dataset

* **Netflix Movies and TV Shows** → [Kaggle Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
* **IMDb Ratings** (opcional, para enriquecer as análises) → [IMDb Datasets](https://datasets.imdbws.com/)

---

## 🔎 Etapas do Projeto

### 1️⃣ **Setup e Carregamento de Dados**

* Instalação de dependências.
* Leitura inicial com Polars.

### 2️⃣ **Limpeza e Transformação**

* Ajuste de tipos de dados.
* Tratamento de valores nulos.
* Criação de colunas derivadas (ano, duração em minutos, etc.).

### 3️⃣ **Análises Exploratórias**

* Lançamentos por ano.
* Filmes vs Séries.
* Países que mais produzem conteúdo.
* Diretores mais frequentes.

### 4️⃣ **Análises Avançadas**

* Tendências temporais (crescimento de séries vs filmes).
* Relação entre ano de lançamento e volume de títulos.
* Cruzamento com dados do IMDb (qualidade x quantidade).

### 5️⃣ **Relatórios e Visualizações**

* Tabelas resumo.
* Gráficos (linha, boxplot, heatmap, etc.).
* Exportação de relatórios em Markdown/PDF.

### 6️⃣ **Extra: Performance e Comparações**

* Uso do **lazy mode** do Polars.
* Comparação com Pandas no mesmo dataset.
* Salvamento em Parquet e análise de velocidade.

---

## 📌 Perguntas que este projeto responde

* O número de lançamentos na Netflix aumentou ao longo dos anos?
* Filmes são mais longos que séries em média?
* Quais países mais produzem títulos para a Netflix?
* Quem são os diretores mais prolíficos?
* Existe relação entre popularidade (IMDb) e ano/país de produção?

---

## ⚡ Como Executar

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/polars-netflix-analysis.git
cd polars-netflix-analysis

# Instale as dependências
pip install -r requirements.txt

# Explore os notebooks
jupyter notebook
```

---

## 📑 Resultados Esperados

Ao final, você terá:
✅ Dataset limpo e pronto para análise.
✅ Relatórios claros e visualmente atrativos.
✅ Experiência prática com **Polars do básico ao avançado**.
✅ Um projeto bonito e bem documentado no seu portfólio.

---

💡 *Este projeto está em constante evolução. Contribuições, sugestões e melhorias são sempre bem-vindas!* 🚀
