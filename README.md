# 🐶 Dog API Data Pipeline

Projeto simples de engenharia de dados consumindo uma API pública de raças de cães.

---

## 📌 Objetivo

Simular um pipeline de dados passando pelas etapas de extração, transformação e estruturação de dados para consumo analítico.

---

## 🔧 Tecnologias utilizadas

- Python
- Pandas
- Requests
- Google Colab

---

## ⚙️ Etapas do pipeline

### 1. Extração
Consumo de dados da Dog API via requisição HTTP.

### 2. Transformação
- Conversão dos dados para DataFrame
- Seleção de colunas relevantes
- Padronização da estrutura
- Adição de coluna de controle (`collected_at`)
- Verificação de duplicidade

### 3. Estruturação
Organização dos dados para facilitar consumo analítico posterior.

---

## 📊 Exemplo de saída

Dataset estruturado com informações como:

- ID da raça  
- Nome  
- Origem  
- Grupo da raça  
- Expectativa de vida  
- Timestamp de coleta  

---

## 🚀 Como executar

1. Abrir o notebook no Google Colab  
2. Executar as células em sequência  
3. Visualizar os dados transformados  

---

## 🔗 API utilizada

https://api.thedogapi.com/

---

## 🧠 Observações

- Projeto desenvolvido com foco em aprendizado de engenharia de dados  
- Pipeline simples, mas baseado em etapas comuns do mundo real  
- Não utiliza autenticação, mas preparado para cenários onde isso seria necessário  

---

## 📎 Próximos passos

- Estruturar o pipeline em script Python (.py)  
- Adicionar orquestração (ex: Airflow)  
- Integrar com Data Warehouse (ex: BigQuery)  
