# Data Pipeline with Microsoft Fabric- for customer and sales table 

## Overview
This repository demonstrates an end-to-end data engineering pipeline built on **Microsoft Fabric** using **PySpark**, **Lakehouse**, and Fabric Pipelines.

The solution ingests multiple CSV datasets into a Lakehouse using a **metadata-driven pipeline** (Get Metadata + ForEach), processes data through **parameterized notebooks**, and writes curated **Delta tables** for analytics.

Downstream, **dimension tables** (Date and Customer) and a **Sales fact table** are created using Spark SQL, followed by a **semantic model** to support reporting.

## Tech Stack
- Microsoft Fabric
- PySpark & Spark SQL
- Delta Lake
- Fabric Pipelines
- Lakehouse Architecture

## Contents
- PySpark notebooks for ingestion and transformation  
- Pipeline JSON for orchestration  
- Dimensional model (star schema) implementation

Detailed implementation and notebooks are provided in this repository.
