# Previsão de Sobrevivência no Titanic — Desafio Kaggle

> Projeto de Machine Learning supervisionado, com foco em classificação preditiva e engenharia de atributos aplicada, desenvolvido e submetido na plataforma Kaggle.

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikit-learn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-yellow?logo=pandas)
![Kaggle](https://img.shields.io/badge/Kaggle-Competition-blue?logo=kaggle)
![Projeto Acadêmico](https://img.shields.io/badge/Projeto-Acadêmico-lightgrey)

---

## 📖 Sobre o projeto

Este projeto foi desenvolvido como desafio prático de Machine Learning supervisionado, utilizando dados históricos de passageiros do Titanic para prever sua sobrevivência.

A atividade foi baseada na competição clássica da plataforma **Kaggle — Titanic: Machine Learning from Disaster**, amplamente utilizada para avaliação de candidatos a cientistas de dados em processos seletivos e bootcamps.

O projeto envolveu o ciclo completo de ciência de dados, incluindo:

- Análise exploratória de dados (EDA);
- Tratamento e imputação de valores ausentes;
- Engenharia de atributos customizada;
- Seleção e transformação de variáveis;
- Modelagem supervisionada com **Random Forest**;
- Validação cruzada e submissão oficial na plataforma Kaggle.

---

## 🎯 Desafios técnicos enfrentados

- Análise de distribuição de sobrevivência baseada em sexo, classe e idade.
- Extração automatizada de features avançadas, como `Title` (extraído de `Name`) e `FamilySize`.
- Tratamento de variáveis com alto índice de missing values, como `Cabin`.
- Pré-processamento robusto para garantir qualidade na entrada do modelo.
- Normalização com `StandardScaler` e codificação via **One-Hot Encoding**.
- Validação cruzada estratificada (Stratified K-Fold 5-fold).

---

## 🚀 Tecnologias e ferramentas

- **Linguagem:** Python 3.10
- **Bibliotecas:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Plataforma:** Kaggle
- **Algoritmo principal:** Random Forest Classifier

---

## 📊 Resultados obtidos

- **Acurácia média (cross-validation):** 82.9% ± 1.5%
- **Ranking competitivo na leaderboard Kaggle**
- Submissão oficial formatada e validada conforme o desafio

---

## 📂 Estrutura do projeto

- `Kaggle_0_8.ipynb` — Código completo em Jupyter Notebook.
- `Previsao-de-Sobrevivencia-no-Titanic-Desafio-Kaggle.pptx` — Apresentação resumida do projeto.
- `Relatorio_Final_Titanic.docx` — Relatório técnico completo documentando todo o processo.

---

## 📚 Contexto acadêmico

- Universidade Católica de Brasília – UCB  
- Ciência de Dados / Aprendizado de Máquina — 2025  
- Projeto de aplicação prática em plataformas de competição de dados.

---

## 📝 Licença

Projeto acadêmico desenvolvido exclusivamente para fins de aprendizado e avaliação educacional na área de Ciência de Dados.
