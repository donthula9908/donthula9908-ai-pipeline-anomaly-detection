# ai-pipeline-anomaly-detection
AI-based anomaly detection for enterprise data pipelines using Isolation Forest (Databricks + Python)
# AI-Powered Pipeline Anomaly Detection

This project demonstrates how Machine Learning (Isolation Forest) can be used to detect abnormal ingestion patterns in enterprise data engineering pipelines.

## Architecture Overview

![AI Pipeline Architecture](image.png)
> End-to-end Azure-inspired anomaly detection workflow using Databricks and Isolation Forest.
## Problem

Traditional monitoring relies on static thresholds:

- Alert if row_count > X
- Alert if row_count < Y

However, real enterprise pipelines are dynamic and pattern-based.

This project introduces ML-driven anomaly detection to identify:

- Sudden row count spikes
- Unexpected data drops
- Ingestion pattern deviations

## Approach

1. Simulate historical ingestion data
2. Apply Isolation Forest for anomaly detection
3. Visualize abnormal behavior
4. Outline production-ready Azure architecture

## Tech Stack

- Python
- scikit-learn
- Databricks (Community Edition)
- Azure-inspired pipeline architecture

## Production Architecture Concept

In an enterprise Azure setup:

1. Azure Data Factory logs ingestion metrics
2. Metrics stored in Delta table
3. Databricks scheduled job runs anomaly detection
4. Results written to anomaly_alert table
5. Logic App triggers alert if anomaly detected

## Why This Matters

AI in Data Engineering should strengthen pipeline reliability — not replace ETL.

This project explores how ML can enhance monitoring and operational intelligence.

---

Author: Naveen Donthula
