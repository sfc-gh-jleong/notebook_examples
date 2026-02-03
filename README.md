# Notebook Examples

This repository contains example Jupyter notebooks demonstrating various Snowflake integrations and data quality workflows.

## Notebooks

| Notebook | Description |
|----------|-------------|
| [Great_Expectations_Demo.ipynb](Great_Expectations_Demo.ipynb) | Data quality validation using Great Expectations with Snowflake |
| [langchain_artifact_demo.ipynb](langchain_artifact_demo.ipynb) | Using external PyPI packages (LangChain) with Snowflake Container Runtime |

### Great Expectations Demo

Demonstrates how to use **Great Expectations (GX)** for data quality validation with Snowflake:
- Installing and configuring Great Expectations
- Connecting to Snowflake
- Creating an Expectation Suite
- Validating data against expectations
- Viewing validation results
- Comparison with Snowflake's native DMFs

### LangChain Artifact Demo

Demonstrates how to use external PyPI packages (like LangChain) directly in Python code using Snowflake's **Container Runtime** with **Artifact Repository** integration.

**Prerequisites:**
- Container Runtime enabled
- External Access Integration configured for PyPI access
- Artifact Repository set up (optional, for caching packages)

## Requirements

- Snowflake account with appropriate permissions
- Snowflake Notebooks environment
