# 📊 Análise de Transações, Risco e Fraude — Power BI

> Dashboard analítico desenvolvido em **Power BI** para exploração de transações financeiras, comportamento por canal, risco/fraude, parcelamento e indicadores operacionais. 

---

## 🎯 Sobre o projeto

Este projeto apresenta uma análise exploratória e estratégica de um conjunto de **transações financeiras**, utilizando o Power BI para transformar dados transacionais em indicadores capazes de apoiar a tomada de decisão.

A análise foi estruturada para responder perguntas relacionadas a:

* Volume e valor movimentado;
* Performance das transações;
* Comportamento dos clientes por canal;
* Distribuição de valores transacionados;
* Fraudes e chargebacks;
* Parcelamento e comportamento por MCC;
* Performance de merchants;
* Identificação de períodos com maior concentração de falhas e pendências;
* Distribuição geográfica das transações e dos eventos de risco.

---

## 🧩 Estrutura da análise

O dashboard foi dividido em cinco grandes perspectivas:

### 1. 📈 Visão Executiva

A visão executiva concentra os principais KPIs do negócio:

* **Volume de transações**
* **Valor total transacionado**
* **Ticket médio**
* **% de transações aprovadas**
* **% de transações pendentes/falhas**
* **% de transações estornadas**

Também são apresentados:

* Distribuição por **canal**;
* Distribuição por **categoria**;
* Evolução temporal de **volume e valor**;
* Identificação de padrões de sazonalidade.

---

### 2. 💳 Comportamento por Canal

Nesta etapa, o objetivo é compreender como as transações se distribuem entre os diferentes canais.

Principais análises:

* Distribuição de `amount_brl` por canal;
* Histograma/boxplot dos valores transacionados;
* Comparação entre **cartão presente** e **transações online**;
* Taxa de **chargeback**;
* Taxa de **fraude** por canal;
* Identificação de canais com maior exposição a risco.

Essa análise permite comparar não apenas o volume financeiro, mas também a qualidade e o risco associado a cada canal.

---

### 3. 🛡️ Risco e Fraude

A análise de risco busca identificar padrões relacionados a transações fraudulentas e chargebacks.

Foram considerados:

* **Taxa de fraude por canal**;
* Fraude por **status da transação**;
* Fraude por **faixa de valor**;
* Distribuição geográfica das ocorrências;
* Identificação de **hotspots por estado e cidade**;
* Comparação entre volume transacionado e exposição ao risco.

A segmentação por faixa de valor ajuda a identificar se eventos de fraude estão concentrados em transações de baixo, médio ou alto valor.

---

### 4. 💰 Cartão e Parcelamento

Esta visão explora o comportamento relacionado ao uso de cartão e parcelamento.

Indicadores analisados:

* **% de transações parceladas**;
* Número médio de parcelas;
* Número médio de parcelas por subcategoria;
* Ticket médio por **MCC (Merchant Category Code)**;
* Relação entre ticket médio e quantidade de parcelas.

O objetivo é entender quais categorias e segmentos apresentam maior utilização de parcelamento e como isso se relaciona com o valor das transações.

---

### 5. ⚙️ Análise Operacional

A perspectiva operacional busca identificar padrões temporais e merchants com maior impacto financeiro.

Foram analisados:

* Falhas por **hora do dia**;
* Pendências por **hora do dia**;
* Comportamento por **dia da semana**;
* Merchants com maior volume de transações;
* Merchants com maior valor transacionado;
* Taxa de estorno por merchant.

Esses indicadores podem auxiliar na identificação de períodos críticos e na priorização de análises sobre merchants com maior exposição operacional.

---

## 🔎 Filtros disponíveis

O dashboard permite realizar análises segmentadas através de filtros como:

| Filtro                  | Objetivo                              |
| ----------------------- | ------------------------------------- |
| 📅 Período              | Analisar diferentes janelas temporais |
| 📱 Canal                | Comparar canais de transação          |
| 🏷️ Categoria           | Avaliar diferentes categorias         |
| 📍 Estado               | Análise geográfica                    |
| 🔄 Status               | Aprovadas, pendentes, falhas, etc.    |
| 💰 Faixa de valor       | Segmentar transações por valor        |
| 🛡️ Fraude / Chargeback | Isolar eventos de risco               |

---

## 📊 Principais indicadores

| Indicador                   | Descrição                                                |
| --------------------------- | -------------------------------------------------------- |
| **Volume de transações**    | Quantidade total de transações                           |
| **Valor total**             | Soma dos valores transacionados                          |
| **Ticket médio**            | Valor médio por transação                                |
| **Taxa de aprovação**       | Percentual de transações aprovadas                       |
| **Taxa de falha/pendência** | Percentual de transações não concluídas                  |
| **Taxa de estorno**         | Percentual de transações estornadas                      |
| **Taxa de fraude**          | Percentual de transações identificadas como fraudulentas |
| **Taxa de chargeback**      | Percentual de transações associadas a chargeback         |
| **Média de parcelas**       | Número médio de parcelas por transação parcelada         |

---

## 🛠️ Tecnologias utilizadas

* **Power BI**
* **Excel**
* **Power Query**
* **DAX**
* **Modelagem de dados**
* **Visualização de dados**
* **Análise exploratória de dados (EDA)**

---

## 📁 Estrutura do repositório

```text
📦 powerbi_transacoes_risco_fraude
│
├── 📊 dashboard_em_pdf/
│   └── Analise BI - Universal Bank.pdf
│
├── 🖼️ dashboard_pbix/
│   ├── transacoes_risco_fraude.pbix
│
├── 📂 data/
│   └── Dicionario de Dados.txt
│   └── bank_transactions_10000_br.csv
│
└── 📄 README.md
```

---
