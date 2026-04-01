# 🐶 Dog API Data Pipeline

Projeto simples de engenharia de dados consumindo uma API pública de raças de cães.

---

## 📌 Objetivo

Simular um pipeline de dados passando pelas etapas de:

- Extração de dados via API
- Transformação e estruturação
- Preparação para consumo analítico

---

## 🔧 Tecnologias utilizadas

- Python
- Pandas
- Requests

---

## ⚙️ Etapas do pipeline

### 1. Extração
Consumo de dados da Dog API utilizando requisições HTTP.

### 2. Transformação
- Seleção de colunas relevantes
- Padronização de estrutura
- Adição de timestamp (`collected_at`)
- Validação de duplicidade

### 3. Carga
Armazenamento dos dados em formato CSV.

---

## 📊 Exemplo de saída

| id | name | origin | breed_group |
|----|------|--------|------------|
| 1  | Affenpinscher | Germany | Toy |

---

## 🚀 Como executar

```bash
pip install -r requirements.txt
python pipeline.py
