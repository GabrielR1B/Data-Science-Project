# Data-Science-Project

## O Cenário do Turismo Global nos últimos anos


## Sobre o Projeto
Este repositório contém a análise consolidada do comportamento do turismo internacional ao longo da última década. O projeto foi desenvolvido de forma colaborativa, onde cada membro da equipe conduziu experimentos em *branches* separadas, sendo unificadas nesta *branch* `main` para compor o pipeline de dados completo.

O objetivo principal foi entender tendências de crescimento, concentração de mercado, eficiência econômica e prever cenários futuros usando dados globais de chegadas (*Arrivals*), receitas (*Receipts*) e despesas (*Expenditures*).

---

## Estrutura de Pastas e Arquivos

O projeto foi organizado da seguinte maneira:

```text

 ┣ dados/
 ┃ ┗ Tourism Quantity Data.csv
 ┃ ┗ Tourism Quantity Data Imputed.csv
 ┣ perguntas/
 ┃ ┗ Pergunta_1.ipynb
 ┃ ┗ Pergunta_2.ipynb
 ┃ ┗ Pergunta_3.ipynb
 ┃ ┗ Pergunta_4.ipynb
 ┣ modelo preditivo/
 ┃ ┗ modelo_preditivo.ipynb
 ┗ README.md

```

---

## Metodologia

Nosso pipeline de análise foi dividido nas seguintes etapas:

### 1. Tratamento de Dados

* Tratamento de nulo e padronização.
* Tratamento de outliers e inconsistências temporais.
* *Técnicas de imputação de dados para preenchimento de séries históricas incompletas.* Foi feito uma análise nas duas bases de dados.

### 2. Análise Exploratória (EDA)

* Visualização das tendências macroeconômicas globais.
* Mapeamento da distribuição geográfica.
* Identificação de impactos de crises históricas (ex: Crise de 2008/2009).

### 3. Testes de Hipótese

Ao longo do projeto foram aplicados vários metodos:

* **Testes de Permutação e Correlação:** Para atestar concentrações de mercado.
* **Teste Binomial & Normal:** Para validar o crescimento estrutural do setor.
* **Bootstrap:** Para confirmar a robustez de várias métricas.

### 4. Modelo Preditivo

* modelo.

---

## Resultados Finais

O projeto responde 4 perguntas Sobre o turismo. Abaixo, o resumo das descobertas:

### 1. O turismo cresceu ou encolheu na última década?

>Ao analisar os dados da última década, observa-se que o turismo internacional apresentou um crescimento consistente e significativo. Esse avanço foi percebido tanto no número de chegadas de turistas quanto nas receitas e nos gastos relacionados ao setor. Embora tenha ocorrido uma queda temporária durante a crise de 2009, a recuperação foi rápida e a tendência geral permaneceu positiva. Além disso, os resultados se mostraram estáveis independentemente do uso da base original ou da base com dados imputados, indicando que as conclusões não foram influenciadas pelos métodos de tratamento dos dados. As simulações realizadas também demonstraram que esse crescimento não depende de poucos países específicos, mas representa um fenômeno global e robusto.


### 2. Como foi a distribuição do turismo global na última década?

> A análise da distribuição do turismo global na última década mostra que a atividade turística esteve fortemente concentrada em poucos países e regiões. A Europa e os países de alta renda lideraram consistentemente o setor, enquanto a Ásia se destacou como o segundo principal polo turístico. Apesar dessa concentração, houve uma leve descentralização ao longo do período, indicando que outros destinos começaram a ganhar maior participação no mercado. Os testes estatísticos confirmaram que essa desigualdade na distribuição do turismo não ocorreu ao acaso e que a predominância desses grupos é robusta. Além disso, países menores e mais dependentes do turismo apresentaram maior vulnerabilidade a oscilações econômicas. Por fim, a utilização de dados imputados não alterou as conclusões gerais do estudo, embora possa influenciar rankings específicos de alguns países com muitos dados ausentes.


### 3. Mais turistas necessariamente significam melhor desempenho?

> **Resposta:**

### 4. Como foi o desempenho turístico do Brasil na última década?

> **Resposta:**

---

## Equipe

Este projeto foi construído colaborativamente por:

* **Marcos Aurelio** - Pergunta 1
* **Yuri** - Pergunta 2
* **Gabriel Martins** - Pergunta 3
* **Gabriel Coelho** - Pergunta 4

A branch main reúne apenas a versão final do trabalho, com a pipeline principal, os dados tratados e os resultados consolidados. Já as demais branches possuem o histórico de desenvolvimento de cada integrante, incluindo análises exploratórias, testes, experimentos e diferentes abordagens adotadas ao longo do projeto. Confira abaixo os links para cada branch:

* [branch gabriel-coelho](https://github.com/GabrielR1B/Data-Science-Project/tree/gabriel-coelho)
* [branch gabriel-martins](https://github.com/GabrielR1B/Data-Science-Project/tree/gabriel-martins)
* [branch marcos](https://github.com/GabrielR1B/Data-Science-Project/tree/marcos)
* [branch yuri](https://github.com/GabrielR1B/Data-Science-Project/tree/yuri)
