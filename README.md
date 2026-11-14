# Fabric Platform in a Box

An end-to-end data platform built on **Microsoft Fabric** and **Azure**, using public Australian data (AEMO, BOM, ABS). It grows in stages from a simple ingestion pipeline to a fully automated, tested and Terraform-provisioned platform.

## Stages

| Stage | Adds | Status |
|---|---|---|
| 1 | API ingestion with Data Factory to bronze, PySpark to silver, incremental loads, scheduling | ☐ |
| 2 | Gold star schema, SCD2 dimension, Warehouse / SQL endpoint, Direct Lake semantic model, Power BI report | ☐ |
| 3 | Git integration, dev/test/prod workspaces, `fabric-cicd` deployment, pytest + data-quality tests in CI | ☐ |
| 4 | Service principal auth, Key Vault, ADLS shortcut, cost notes | ☐ |
| 5 | Everything provisioned by Terraform, logging, alerting, runbook, incident write-ups | ☐ |

## Stack

Microsoft Fabric (Lakehouse, Data Factory, notebooks, Warehouse, Direct Lake) · Python / PySpark · SQL · Power BI · GitHub Actions · Azure (Entra ID, Key Vault, ADLS Gen2) · Terraform

## Repo layout

Folders will be added as each stage lands. Progress notes live in [LEARNING_LOG.md](LEARNING_LOG.md).
