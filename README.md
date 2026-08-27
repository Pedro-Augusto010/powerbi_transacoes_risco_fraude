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

## 🗺️ Insights explorados

O dashboard foi construído para permitir a identificação de perguntas estratégicas como:

* Qual canal concentra o maior volume financeiro?
* Quais canais apresentam maior taxa de fraude?
* Existe relação entre **valor da transação** e ocorrência de fraude?
* Quais estados ou cidades apresentam maior concentração de eventos de risco?
* Em quais horários ocorrem mais falhas e pendências?
* Quais dias da semana apresentam maior volume de problemas operacionais?
* Quais merchants concentram maior valor transacionado?
* Quais merchants apresentam maiores taxas de estorno?
* Quais MCCs possuem maior ticket médio?
* Quais subcategorias apresentam maior utilização de parcelamento?
* Como volume, valor e risco se comportam ao longo do tempo?

---

## 🛠️ Tecnologias utilizadas

* **Power BI**
* **Power Query**
* **DAX**
* **Modelagem de dados**
* **Visualização de dados**
* **Análise exploratória de dados (EDA)**

---

## 🧠 Competências demonstradas

Este projeto demonstra conhecimentos em:

**Data Analytics**

* Análise exploratória;
* Identificação de padrões;
* Segmentação de dados;
* Análise temporal;
* Análise geográfica.

**Business Intelligence**

* Construção de dashboards;
* Definição de KPIs;
* Storytelling com dados;
* Desenvolvimento de filtros e segmentações;
* Construção de visualizações interativas.

**Power BI**

* Modelagem de dados;
* DAX;
* Power Query;
* Criação de medidas;
* Design e organização de dashboards.

**Risk Analytics**

* Análise de fraude;
* Chargeback;
* Taxa de estorno;
* Segmentação por faixa de valor;
* Identificação de hotspots de risco.

---

## 🖥️ Dashboard

### Visão Executiva

![Dashboard — Visão Executiva](images/dashboard_executivo.png)

### Comportamento por Canal

![Dashboard — Canais](images/dashboard_canais.png)

### Risco e Fraude

![Dashboard — Risco e Fraude](images/dashboard_risco.png)

### Cartão e Parcelamento

![Dashboard — Parcelamento](images/dashboard_parcelamento.png)

### Análise Operacional

![Dashboard — Operacional](images/dashboard_operacional.png)

> **Nota:** substitua os caminhos acima pelos nomes das imagens exportadas do seu Power BI.

---

## 📁 Estrutura do repositório

```text
📦 projeto-power-bi
│
├── 📊 dashboard/
│   └── dashboard.pbix
│
├── 🖼️ images/
│   ├── dashboard_executivo.png
│   ├── dashboard_canais.png
│   ├── dashboard_risco.png
│   ├── dashboard_parcelamento.png
│   └── dashboard_operacional.png
│
├── 📂 data/
│   └── dataset.csv
│
└── 📄 README.md
```

---

## 🚀 Objetivo do projeto

Mais do que apresentar indicadores, o projeto busca demonstrar como dados transacionais podem ser transformados em **informações acionáveis para negócio**, conectando performance financeira, comportamento por canal, eficiência operacional e gestão de risco.

O dashboard foi desenvolvido com foco em **clareza visual, interatividade e capacidade de exploração dos dados**, permitindo que diferentes perspectivas sejam analisadas a partir de filtros e segmentações.

---

## 👨‍💻 Projeto

**Análise de Transações, Risco e Fraude**

**Ferramenta principal:** Power BI
**Área:** Data Analytics | Business Intelligence | Risk Analytics

---

⭐ Se este projeto foi útil ou interessante, considere deixar uma estrela no repositório!
