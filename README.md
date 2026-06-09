# Logistics & Supply Chain Operations Dashboard 

This repository showcases an ecosystem of dashboards designed for operational monitoring, order tracking, and freight and SLA auditing across national and international logistics operations. The project's objective is to transform operational data into strategic insights that help reduce delivery failures, improve supply chain efficiency, and optimize carrier-related costs.

## Business Context

In e-commerce and supply chain environments, monitoring the entire order lifecycle — from warehouse picking to final delivery — is essential to maintaining high service levels while controlling operational expenses.

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

---

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

---

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

## Technologies & Tools

* **Power BI:** Dashboard development and data visualization.
* **DAX:** Creation of advanced measures, SLA indicators, and Time Intelligence calculations.
* **Power Query (M Language):** Data extraction, transformation, and standardization.
* **Data Integration:** Consolidation of information from ERP systems, tax invoices (DANFE), and carrier tracking platforms.

## Technical Challenges Overcome

* **Unified Data Pipeline:**

  * Consolidation of multiple carrier statuses into a standardized logistics funnel.

* **Dynamic SLA Calculations:**

  * Implementation of carrier-specific business rules to accurately measure service-level compliance.

* **Freight Cost Analysis:**

  * Development of analytical indicators to identify discrepancies between actual shipping costs and customer charges.

* **Scalable Analytical Modeling:**

  * Design of optimized data models capable of supporting large datasets and historical analysis with high performance.

## Key Insights

* **Operational Bottleneck Reduction:**

  * Identification of invoicing-stage bottlenecks, contributing to shorter overall order Lead Times.

* **Carrier Performance Management:**

  * Early detection of underperforming logistics partners, supporting contract reviews and logistics network optimization.

* **Cost Optimization:**

  * Identification of carriers offering the best balance between cost efficiency, delivery speed, and service quality.

* **Improved Decision-Making:**

  * Delivery of reliable KPIs that support continuous monitoring and data-driven operational decisions.

---

*This project is part of my portfolio in Business Intelligence, Logistics Analytics, and Supply Chain Management, demonstrating my ability to transform complex operational data into actionable business insights.*

_________________________________
# Logistics & Supply Chain Operations Dashboard 📊🚚

Este repositório apresenta um ecossistema de dashboards desenvolvido para monitoramento operacional, rastreamento de pedidos e auditoria de fretes e SLAs em operações logísticas nacionais e internacionais. O objetivo do projeto é transformar dados operacionais em informações estratégicas, permitindo reduzir falhas de entrega, aumentar a eficiência da cadeia logística e otimizar custos com transportadoras.

## Contexto do Negócio

Em operações de e-commerce e supply chain, acompanhar o fluxo dos pedidos — desde a separação no estoque até a entrega ao cliente final — é essencial para garantir níveis elevados de serviço e controlar custos operacionais.

Este projeto foi desenvolvido para proporcionar visibilidade completa da operação logística por meio de três perspectivas analíticas complementares: monitoramento operacional em tempo real, análise histórica de desempenho e auditoria de fornecedores logísticos.

## Estrutura dos Dashboards & Visões Analíticas

### 1. Monitoramento Ativo de Pedidos (Active Order Monitoring)

Visão operacional voltada ao acompanhamento diário da operação, permitindo a identificação rápida de gargalos nos processos de expedição e faturamento.

#### Principais Métricas

* Quantidade total de pedidos ativos.
* Monitoramento do funil logístico:

  * Picking Requests
  * In Picking
  * Picked Awaiting Invoicing
  * Awaiting Carrier Pickup
  * In Transit

#### Funcionalidades

* Filtros dinâmicos por transportadora.
* Segmentação por status de faturamento.
* Monitoramento de emissão de DANFE e pendências fiscais.
* Identificação imediata de atrasos operacionais.

---

### 2. Histórico de Desempenho de Envios (Order Performance History)

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

---

### 3. Auditoria de Transportadoras & SLA (Carrier SLA & Cost Analysis)

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

## Tecnologias e Ferramentas

* **Power BI:** Desenvolvimento dos dashboards e construção das visualizações.
* **DAX:** Criação de medidas avançadas, indicadores de SLA e inteligência temporal (Time Intelligence).
* **Power Query (M Language):** Extração, transformação e padronização dos dados logísticos.
* **Integração de Dados:** Consolidação de informações provenientes de ERP, documentos fiscais (DANFE) e sistemas de rastreamento de transportadoras.

## Desafios Técnicos Superados

* **Pipeline de Dados Unificado:**

  * Consolidação de múltiplos status operacionais em um funil logístico padronizado.

* **Cálculo Dinâmico de SLA:**

  * Implementação de regras específicas por transportadora para mensurar corretamente o cumprimento dos prazos acordados.

* **Análise Financeira de Fretes:**

  * Desenvolvimento de indicadores capazes de identificar divergências entre o custo real do transporte e os valores cobrados dos clientes.

* **Modelagem Analítica para Grandes Volumes:**

  * Estruturação de modelos otimizados para suportar consultas rápidas e análises históricas extensas.

## Principais Insights Obtidos

* **Redução de Gargalos Operacionais:**

  * Identificação de acúmulos na etapa de faturamento, contribuindo para a redução do Lead Time total dos pedidos.

* **Gestão de Performance de Transportadoras:**

  * Diagnóstico de parceiros com baixo desempenho em SLA, fornecendo subsídios para revisão de contratos e redefinição da malha logística.

* **Otimização de Custos:**

  * Identificação das transportadoras com melhor equilíbrio entre custo, prazo e qualidade de entrega.

* **Melhoria na Tomada de Decisão:**

  * Disponibilização de indicadores confiáveis para acompanhamento contínuo da operação logística.

---

*Este projeto faz parte do meu portfólio em Business Intelligence, Analytics Aplicado à Logística e Supply Chain, demonstrando minha capacidade de transformar dados operacionais complexos em insights acionáveis para o negócio.*

