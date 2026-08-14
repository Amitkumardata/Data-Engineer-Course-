# Azure Data Engineering Course Projects

Hands-on notes and artifacts for building reliable batch data workflows on Azure.

## What this repository demonstrates

- Data lake organization with raw, bronze, silver, and gold layers.
- Azure Data Factory datasets, linked services, pipelines, and triggers.
- Partitioning and star-schema concepts for analytics-ready data.
- PySpark cleaning and standardization patterns.
- Documentation of business context, assumptions, and access boundaries.

## Repository map

| Path | Purpose |
| --- | --- |
| [dataset](./dataset) | Dataset definitions used by the ADF exercises. |
| [linkedService](./linkedService) | Connection configuration examples. |
| [factory](./factory) | Factory-level Azure Data Factory artifacts. |
| [pipeline](./pipeline) | Ingestion and transformation pipeline definitions. |
| [trigger](./trigger) | Trigger configuration examples. |
| [1. Data lake folder design](./1.%20Data%20lake%20folder%20design) | Raw-to-gold folder design for an e-commerce scenario. |
| [2. Azure Data Factory](./2.%20Azure%20Data%20Factory) | ADF-focused notes and walkthroughs. |
| [Partitioning](./Partitioning) | Partitioning strategy notes for event data. |
| [PySpark Sales Cleaning Project](./PySpark%20Sales%20Cleaning%20Project) | Cleaning and validation exercise. |
| [Star schema](./Star%20schema) | Dimensional modeling notes for sales analytics. |

## Mini-project: e-commerce data lake

The scenario combines orders, customers, products, payments, and website events. The design preserves raw inputs, supports reprocessing, and publishes cleaned data for analysts and business users.

## How to review it

1. Start with the data lake folder design.
2. Open the ADF artifact folders to review the JSON configuration.
3. Compare the partitioning and star-schema notes with the pipeline flow.
4. Review the PySpark exercise for transformation and validation logic.

## Status

Active learning portfolio. The examples are designed for repeatable practice and documentation; they are not presented as a production deployment.
