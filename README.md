# CareerMatch-AI-Agent_AAI_510# CareerMatch AI

An AI-powered career recommendation and workforce intelligence system built using Databricks, Vector Search, Unity Catalog Functions, and Large Language Models (LLMs).

## Project Overview

CareerMatch AI helps connect users with relevant job opportunities by combining semantic search, structured retrieval, and AI reasoning. The system analyzes job postings, identifies skill gaps, and provides personalized recommendations to support career development and workforce planning.

This project demonstrates an end-to-end AI agent workflow, from data engineering and retrieval infrastructure to agent development, evaluation, and business impact analysis.

---

## Key Features

- Semantic job search using Vector Search
- AI-powered job recommendations
- Skill gap identification
- Structured retrieval through Unity Catalog Functions
- Tool-calling agent architecture
- MLflow tracing and evaluation
- Business impact and ROI analysis

---

## Project Architecture

```text
Job Postings Data
        ↓
Data Engineering Pipeline
        ↓
Vector Search Index
        ↓
Unity Catalog Functions
        ↓
AI Agent
        ↓
Evaluation & Business Analysis
```

---

## Technologies

- Databricks
- Python
- SQL
- Unity Catalog
- Databricks Vector Search
- MLflow
- Large Language Models (LLMs)
- Retrieval-Augmented Generation (RAG)

---

## Repository Structure

### 00_data_engineering.ipynb
Data ingestion, cleaning, validation, feature engineering, and exploratory data analysis.

### 01_setup_vector_index.ipynb
Creation and validation of the Vector Search index used for semantic retrieval.

### 02_create_uc_functions.ipynb
Development of Unity Catalog Functions used as tools within the agent workflow.

### 03_agent.ipynb
Implementation of the CareerMatch AI agent, including tool integration, prompting, guardrails, and tracing.

### 04_evaluation.ipynb
Agent evaluation using MLflow, custom judges, trace analysis, and model comparisons.

### 05_ROI_Business_Case.ipynb
Business value assessment, ROI estimation, and deployment recommendations.

---

## Results

The project successfully demonstrates:

- End-to-end AI agent development
- Semantic retrieval over job postings
- Tool-calling workflows
- Automated and human-in-the-loop evaluation
- Practical business applications of AI agents

---

## Team Members

- Gerek Jordan
- Lashana Narayan
- Zinah Othman
- Deepika Shrestha


---

## Academic Context

Developed as part of the Master of Science in Applied Artificial Intelligence (MS-AAI) program at the University of San Diego.
