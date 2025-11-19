# 🚀 Pipeline ETL com Python e Regras Inteligentes de Recomendação

Este projeto foi desenvolvido como parte do desafio da DIO no lab **"Explorando IA Generativa em um Pipeline de ETL"**, mas com uma adaptação importante: em vez de usar uma API externa ou modelos de IA generativa, optei por criar um pipeline totalmente **local**, utilizando **Python**, **Pandas** e **lógica própria de recomendação**.

O objetivo foi manter a essência do ETL — **Extrair, Transformar e Carregar** — criando algo simples, eficiente e aplicável em vários cenários reais.

---

## 🧠 Visão Geral do Projeto

### ✔ **Extract (Extração)**

Para a etapa de extração, gerei um conjunto de dados diretamente no próprio notebook, simulando uma pequena base de usuários contendo:

* nome
* interesse de estudo
* nível de conhecimento

Essa abordagem permite reproduzir facilmente o processo sem depender de arquivos externos ou APIs.

---

### ✔ **Transform (Transformação com Regras Customizadas)**

A etapa de transformação foi totalmente personalizada.
Criei um sistema de recomendações que analisa o interesse e o nível de conhecimento do usuário para gerar automaticamente uma sugestão de curso adequada.

Exemplos:

* Usuários iniciantes recebem recomendações introdutórias.
* Usuários intermediários recebem recomendações práticas.
* Usuários avançados recebem recomendações de especialização.

Esse tipo de lógica é muito usado em pipelines reais, onde regras de negócio substituem modelos de IA quando o objetivo é simplicidade, velocidade ou independência de serviços externos.

---

### ✔ **Load (Carregamento dos Dados Transformados)**

Após gerar as recomendações, os dados transformados são carregados novamente em novos formatos que podem ser facilmente reutilizados em outros sistemas, análises ou integrações.

O carregamento demonstra como dados processados podem retornar para o fluxo de trabalho de forma organizada e estruturada.

---

## 🎯 Objetivo do Projeto

O objetivo principal foi mostrar que é possível construir um pipeline ETL completo, robusto e útil mesmo sem depender de IA ou APIs externas.
A ideia central do desafio — pensar como um cientista de dados e criar um fluxo de dados funcional — foi totalmente preservada.

---

## 🛠 Tecnologias e Conceitos Aplicados

* Python
* Pandas
* ETL (Extract, Transform, Load)
* Regras de Negócio
* Automação de Recomendações
* DataFrames
* Exportação de dados

---

## 💡 Possíveis Extensões Futuras

* Adicionar análise estatística dos usuários
* Gerar gráficos de interesse por área
* Criar novas regras de recomendação por perfil
* Integrar com API própria usando FastAPI
* Criar um dashboard em Streamlit
* Aumentar o dataset com mais usuários e atributos
* Adicionar sistema de pontuação e priorização

---

## 🧑‍💻 Autor

**Lucas Gabriel (Oreki)**
Cientista de Dados Jr
Apaixonado por dados, automação e soluções inteligentes 💙
