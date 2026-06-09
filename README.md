# English Version

## Overview

This project presents a Business Intelligence solution developed in Power BI to monitor logistics operations, track order performance, and audit freight costs and service-level agreements (SLAs) across national and international supply chain activities. The dashboard ecosystem transforms operational data into strategic insights that help organizations improve delivery performance, optimize logistics costs, and strengthen decision-making throughout the order fulfillment process.

The solution combines operational visibility, historical performance analysis, and carrier management into an integrated analytical environment designed to support both tactical execution and strategic planning.

## Objectives

* Monitor the end-to-end order fulfillment process.
* Identify operational bottlenecks affecting delivery performance.
* Evaluate carrier performance through SLA indicators.
* Analyze freight costs and identify optimization opportunities.
* Support logistics planning using historical performance data.
* Improve operational decision-making through data-driven insights.

## Business Context

In e-commerce and supply chain environments, monitoring the entire order lifecycle—from warehouse picking to final delivery—is essential to maintaining high service levels while controlling operational expenses.

This project was developed to provide end-to-end visibility into logistics operations through three complementary analytical perspectives: real-time operational monitoring, historical performance analysis, and logistics partner auditing.

## Dashboard Structure & Analytical Views

### 1. Active Order Monitoring

An operational view designed to support day-to-day management by enabling the rapid identification of bottlenecks within shipping and invoicing processes.

#### Key Metrics

* Total number of active orders.
* Monitoring of the logistics funnel:

  * Picking Requests;
  * In Picking;
  * Picked Awaiting Invoicing;
  * Awaiting Carrier Pickup;
  * In Transit.

#### Features

* Dynamic filters by carrier.
* Billing status segmentation.
* Monitoring of invoice issuance and tax-related issues.
* Immediate identification of operational delays.
* Enhanced visibility into the order fulfillment pipeline.

### 2. Order Performance History

A strategic view focused on time-series analysis to identify trends, seasonality patterns, and recurring operational issues.

#### Key Metrics

* Monthly evolution of orders:

  * Created;
  * Invoiced;
  * Packed;
  * Delivered.
* Monitoring of:

  * Lost Shipments;
  * Incomplete Orders;
  * Delivery Failures.

#### Features

* Year-over-year performance comparisons.
* Trend analysis for operational efficiency.
* Assessment of seasonal impacts on logistics capacity.
* Early identification of recurring fulfillment issues.

### 3. Carrier SLA & Cost Analysis

An executive-level view focused on evaluating logistics providers' performance and freight cost efficiency.

#### Key Metrics

* SLA compliance rate by carrier.
* Average delivery time (Lead Time).
* Comparison between:

  * Freight charges billed to customers;
  * Actual freight costs.
* Failure rates by logistics provider.

#### Features

* Geographic analysis by state and carrier.
* Identification of regional bottlenecks.
* Benchmarking of logistics partners.
* Decision support for carrier contract negotiations.
* Monitoring of logistics service quality.

## Technologies & Tools

* **Power BI:** Dashboard development and interactive data visualization.
* **DAX:** Creation of advanced measures, SLA indicators, and Time Intelligence calculations.
* **Power Query (M Language):** Data extraction, cleansing, transformation, and standardization.
* **Data Integration:** Consolidation of information from ERP systems, tax invoices (DANFE), and carrier tracking platforms.
* **Dimensional Modeling:** Structuring analytical models to support scalability and performance.

## Technical Challenges Overcome

* **Unified Data Pipeline:**

  * Consolidation of multiple carrier statuses into a standardized logistics funnel to ensure consistency across operational analyses.

* **Dynamic SLA Calculations:**

  * Implementation of carrier-specific business rules to accurately measure service-level compliance.

* **Freight Cost Analysis:**

  * Development of analytical indicators capable of identifying discrepancies between actual shipping costs and customer charges.

* **Scalable Analytical Modeling:**

  * Design of optimized data models capable of supporting large datasets and historical analyses while maintaining high performance.

## Key Insights

* **Operational Bottleneck Reduction:**

  * Identification of invoicing-stage bottlenecks, contributing to shorter overall order Lead Times.

* **Carrier Performance Management:**

  * Early detection of underperforming logistics partners, supporting contract reviews and logistics network optimization.

* **Cost Optimization:**

  * Identification of carriers offering the best balance between cost efficiency, delivery speed, and service quality.

* **Enhanced Decision-Making:**

  * Delivery of reliable KPIs that support continuous monitoring and data-driven operational decisions.

## Repository Structure

```text
logistics-supply-chain-operations-dashboard/
├── Logistics-Supply-Chain-Operations-Dashboard.pbix
├── README.md
└── images/
    ├── active-order-monitoring.png
    ├── order-performance-history.png
    └── carrier-sla-cost-analysis.png
```

---

*This project is part of my portfolio in Business Intelligence, Logistics Analytics, and Supply Chain Management, demonstrating my ability to transform complex operational data into actionable insights that support operational excellence and data-driven decision-making.*

---

# Versão em Português

## Overview

Este projeto apresenta uma solução de Business Intelligence desenvolvida em Power BI para monitorar operações logísticas, acompanhar o desempenho dos pedidos e auditar custos de frete e acordos de nível de serviço (SLAs) em operações nacionais e internacionais. O ecossistema de dashboards transforma dados operacionais em insights estratégicos que auxiliam na melhoria da performance logística, na otimização de custos e no fortalecimento da tomada de decisão ao longo de todo o processo de atendimento dos pedidos.

A solução combina visibilidade operacional, análise histórica de desempenho e gestão de transportadoras em um ambiente analítico integrado, projetado para apoiar tanto a execução tática quanto o planejamento estratégico.

## Objetivo

* Monitorar o fluxo completo dos pedidos, desde a separação até a entrega.
* Identificar gargalos operacionais que impactam o desempenho logístico.
* Avaliar a performance das transportadoras por meio de indicadores de SLA.
* Analisar custos de frete e identificar oportunidades de otimização.
* Apoiar o planejamento logístico com base em dados históricos.
* Melhorar a tomada de decisão por meio de insights orientados por dados.

## Business Context

Em operações de e-commerce e supply chain, acompanhar o fluxo dos pedidos — desde a separação no estoque até a entrega ao cliente final — é essencial para garantir níveis elevados de serviço e controlar custos operacionais.

Este projeto foi desenvolvido para proporcionar visibilidade completa da operação logística por meio de três perspectivas analíticas complementares: monitoramento operacional em tempo real, análise histórica de desempenho e auditoria de fornecedores logísticos.

## Dashboard Structure & Analytical Views

### 1. Monitoramento Ativo de Pedidos

Visão operacional voltada ao acompanhamento diário da operação, permitindo a identificação rápida de gargalos nos processos de expedição e faturamento.

#### Principais Métricas

* Quantidade total de pedidos ativos.
* Monitoramento do funil logístico:

  * Picking Requests;
  * In Picking;
  * Picked Awaiting Invoicing;
  * Awaiting Carrier Pickup;
  * In Transit.

#### Funcionalidades

* Filtros dinâmicos por transportadora.
* Segmentação por status de faturamento.
* Monitoramento de emissão de DANFE e pendências fiscais.
* Identificação imediata de atrasos operacionais.
* Maior visibilidade sobre o fluxo operacional dos pedidos.

### 2. Histórico de Desempenho de Envios

Visão estratégica focada na análise temporal da operação para identificar tendências, sazonalidades e recorrência de falhas.

#### Principais Métricas

* Evolução mensal de pedidos:

  * Criados;
  * Faturados;
  * Embalados;
  * Entregues.
* Monitoramento de:

  * Lost Shipments (Extravios);
  * Incomplete Orders (Pedidos Incompletos);
  * Delivery Failures (Falhas de Entrega).

#### Funcionalidades

* Comparativos anuais entre períodos distintos.
* Análise de tendências operacionais.
* Avaliação do impacto de variações sazonais na capacidade logística.
* Identificação antecipada de falhas recorrentes.

### 3. Auditoria de Transportadoras & SLA

Visão executiva destinada à avaliação da performance dos parceiros logísticos e à gestão dos custos de transporte.

#### Principais Métricas

* Percentual de cumprimento de SLA por transportadora.
* Tempo médio de entrega (Lead Time).
* Comparação entre:

  * Valor cobrado do cliente;
  * Custo real do frete.
* Taxa de falhas por operador logístico.

#### Funcionalidades

* Análise geográfica por estado e transportadora.
* Identificação de gargalos regionais.
* Comparação de eficiência entre fornecedores.
* Apoio à tomada de decisão para renegociação contratual.
* Monitoramento contínuo da qualidade dos serviços logísticos.

## Tecnologias e Ferramentas

* **Power BI:** Desenvolvimento dos dashboards e construção das visualizações interativas.
* **DAX:** Criação de medidas avançadas, indicadores de SLA e cálculos de inteligência temporal.
* **Power Query (M Language):** Extração, transformação e padronização dos dados logísticos.
* **Integração de Dados:** Consolidação de informações provenientes de ERP, DANFE e plataformas de rastreamento de transportadoras.
* **Modelagem Dimensional:** Estruturação de modelos analíticos visando desempenho e escalabilidade.

## Desafios Técnicos Superados

* **Pipeline de Dados Unificado:**

  * Consolidação de múltiplos status operacionais em um funil logístico padronizado.

* **Cálculo Dinâmico de SLA:**

  * Implementação de regras específicas por transportadora para mensurar corretamente o cumprimento dos prazos acordados.

* **Análise Financeira de Fretes:**

  * Desenvolvimento de indicadores capazes de identificar divergências entre o custo real do transporte e os valores cobrados dos clientes.

* **Modelagem Analítica para Grandes Volumes:**

  * Estruturação de modelos otimizados para suportar análises históricas extensas com alto desempenho.

## Principais Insights

* **Redução de Gargalos Operacionais:**

  * Identificação de acúmulos na etapa de faturamento, contribuindo para a redução do Lead Time total dos pedidos.

* **Gestão de Performance de Transportadoras:**

  * Diagnóstico de parceiros com baixo desempenho em SLA, fornecendo subsídios para revisão de contratos e redefinição da malha logística.

* **Otimização de Custos:**

  * Identificação das transportadoras com melhor equilíbrio entre custo, prazo e qualidade de entrega.

* **Melhoria na Tomada de Decisão:**

  * Disponibilização de indicadores confiáveis para acompanhamento contínuo da operação logística.

## Estrutura do Repositório

```text
logistics-supply-chain-operations-dashboard/
├── Logistics-Supply-Chain-Operations-Dashboard.pbix
├── README.md
└── images/
    ├── active-order-monitoring.png
    ├── order-performance-history.png
    └── carrier-sla-cost-analysis.png
```

---

*Este projeto integra meu portfólio em Business Intelligence, Analytics Aplicado à Logística e Supply Chain, demonstrando minha capacidade de transformar dados operacionais complexos em insights acionáveis para apoiar a excelência operacional e a tomada de decisão baseada em dados.*
