# Trabalho de Introdução à Ciência de Dados - Turismo Internacional

## 11/04

---

## Etapas de Tratamento Realizadas

* **Limpeza de Entidades:** Remoção de países com valores nulos em toda a série e exclusão de agregados não nacionais (ex: OECD, World, Low Income, Regiões geográficas).
* **Merge:** Integração dos datasets principais com metadados globais para a inclusão da coluna de **Continente**.
* **Validação de Dados:** Filtragem de valores negativos e remoção de colunas redundantes ou descritivas que não agregavam valor.
* **Tratamento de Outliers:** Exclusão de países com baixa densidade de dados para evitar distorções na série temporal.
* **Série Temporal Contínua:** Identificação da maior sequência contínua de anos sem valores nulos, priorizando a manutenção de países importantes.

## Ainda falta :(

Padronizar os datasets para conter:
1.  **Exatamente os mesmos países em todos os datasets.**
2.  **A mesma janela temporal**.
3.  **Dados 100% íntegros** (sem valores nulos) o dataset departures tinha mais de 100 países com quase nenhum ou nenhum dado.

---
