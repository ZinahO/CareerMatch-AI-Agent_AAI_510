# CareerMatch-AI-Agent_AAI_510# 

### AI-Powered Career Recommendation and Workforce Intelligence Agent

## Project Overview

CareerMatch AI is an intelligent career guidance and job recommendation system designed to help job seekers discover relevant opportunities, identify skill gaps, and make informed career decisions.

The project combines Data Engineering, Retrieval-Augmented Generation (RAG), Vector Search, Unity Catalog Functions, LLM-powered reasoning, and automated evaluation to create an end-to-end AI agent capable of matching users with jobs based on their skills, experience, and career goals.

The solution leverages LinkedIn Job Postings data and Databricks AI capabilities to provide personalized recommendations, explain job matches, identify missing skills, and support workforce intelligence use cases.

---

## Business Problem

Searching for jobs can be time-consuming and overwhelming. Job seekers often struggle to:

- Find positions that match their skills and experience
- Understand required qualifications
- Identify skill gaps
- Prioritize opportunities aligned with their career goals

CareerMatch AI addresses these challenges by combining semantic search, structured retrieval, and LLM reasoning to deliver personalized and explainable job recommendations.

---

## Project Objectives

- Build an AI-powered career recommendation agent
- Prepare and organize job posting data for AI applications
- Enable semantic search across job listings
- Support skill matching and career guidance workflows
- Provide explainable recommendations and skill-gap analysis
- Evaluate multiple LLMs within an agent workflow
- Demonstrate both technical and business value

---

# Architecture

```text
LinkedIn Job Postings Dataset
                │
                ▼
      Data Engineering Pipeline
                │
                ▼
        Agent-Ready Tables
                │
                ▼
      Databricks Vector Search
                │
                ▼
      Unity Catalog Functions
                │
                ▼
        CareerMatch AI Agent
                │
                ▼
       MLflow Evaluation &
         Trace Analysis
                │
                ▼
        ROI Business Case
```

---

# Technologies Used

- Databricks
- Unity Catalog
- Delta Tables
- Databricks Vector Search
- Databricks Foundation Models
- MLflow
- Python
- SQL
- Retrieval-Augmented Generation (RAG)
- Tool Calling Agents
- Large Language Models (LLMs)

---

# Dataset

### LinkedIn Job Postings Dataset

The project uses the LinkedIn Job Postings dataset containing information such as:

- Job Titles
- Company Names
- Job Descriptions
- Locations
- Salary Information
- Work Types
- Skills
- Application Details

The dataset serves as the foundation for job matching, semantic retrieval, and recommendation generation.

---

# Project Structure

## 00_data_engineering.ipynb

Data Engineering pipeline responsible for:

- Loading raw LinkedIn job posting data
- Data quality assessment
- Missing value analysis
- Feature engineering
- Exploratory Data Analysis (EDA)
- Creation of agent-ready search text
- Creation of clean Delta tables

Key outputs:

- Cleaned job posting tables
- Search-ready text fields
- Agent-ready datasets

---

## 01_setup_vector_index.ipynb

Vector Search infrastructure notebook.

Responsibilities:

- Configure Databricks Vector Search
- Enable Change Data Feed
- Create Delta Sync Index
- Validate index creation
- Test semantic retrieval
- Prepare retrieval infrastructure for the agent

Key outputs:

- Vector Search Endpoint
- Delta Sync Vector Index
- Semantic retrieval validation

---

## 02_create_uc_functions.ipynb

Creates Unity Catalog Functions used as agent tools.

Responsibilities:

- Structured job retrieval
- Salary lookups
- Job detail retrieval
- Location-based filtering
- Additional deterministic agent tools

Key outputs:

- Unity Catalog Functions
- Tool interfaces for the AI agent

---

## 03_agent.ipynb

Defines the CareerMatch AI Agent.

Responsibilities:

- Prompt engineering
- Tool integration
- Agent orchestration
- Guardrails
- Tool-calling workflows
- MLflow tracing

Key features:

- ReAct-style workflow
- Tool calling
- Structured retrieval
- Semantic retrieval
- Explainable recommendations

---

## 04_evaluation.ipynb

Evaluates agent performance.

Responsibilities:

- Evaluation dataset creation
- Custom LLM judges
- MLflow evaluations
- Trace analysis
- Model comparisons
- Human review

Evaluation Areas:

- Tool usage
- Grounding
- Skill-gap analysis
- Guardrail compliance
- Recommendation quality

Models Evaluated:

- Llama 3.3 70B
- GPT-OSS 120B

---

## 05_ROI_Business_Case.ipynb

Business impact and ROI analysis.

Responsibilities:

- Business value assessment
- Workforce intelligence use cases
- ROI estimation
- Strategic recommendations
- Deployment justification

---

# Agent Capabilities

CareerMatch AI can:

- Recommend jobs based on skills and experience
- Perform semantic job search
- Identify skill gaps
- Explain recommendation reasoning
- Retrieve job details
- Filter jobs by location and criteria
- Support workforce planning discussions
- Provide grounded responses using retrieved data

---

# Evaluation Highlights

The agent was evaluated using:

- MLflow tracing
- Custom LLM judges
- Human review
- Multi-model comparisons
- Structured evaluation scenarios

Evaluation dimensions included:

- Tool Usage Accuracy
- Grounding Quality
- Skill Gap Identification
- Recommendation Relevance
- Guardrail Compliance

---

# Business Value

CareerMatch AI provides value through:

- Improved candidate-role matching
- Reduced hiring inefficiencies
- Better workforce planning
- Skill-gap identification
- Career guidance support
- Improved employee development strategies

The project demonstrates how AI agents can combine retrieval, structured tools, and reasoning to create actionable workforce intelligence solutions.

---

# Team Contributions

### Data Engineering
- Data ingestion and preparation
- Data quality validation
- Feature engineering
- Exploratory Data Analysis
- Agent-ready dataset creation
- Vector Search infrastructure

### AI Engineering
- Agent development
- Tool integration
- Prompt engineering
- MLflow tracing
- Evaluation workflows

### Product & Business Analysis
- Business case development
- ROI analysis
- Use case design
- Presentation and documentation

---

# Future Improvements

- Enhanced skill extraction
- More advanced ranking algorithms
- Resume upload integration
- Multi-agent workflows
- Additional evaluation scenarios
- Real-time job posting updates
- Expanded workforce analytics

---

## Team Members

- Gerek Jordan
- Lashana Narayan
- Zinah Othman
- Deepika Shrestha

MS-AAI Final Project  
University of San Diego

CareerMatch AI – Intelligent Career Recommendation and Workforce Intelligence Agent
