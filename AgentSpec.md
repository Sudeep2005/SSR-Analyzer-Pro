Purpose: Document detailed specs of all agents — roles, responsibilities, tools, communication patterns.
# Agent Specification - SSR Analyzer Pro

## Overview
SSR Analyzer Pro is composed of multiple modular agents...

## Agents

### Planner Agent
- Role: Orchestrates planning and task delegation
- Responsibilities: Clarify requirements, invoke other agents, error handling
- Tools: LLM (GPT-4o), Pre-curated plans

### Requirement Parser Agent
- Role: Extracts and structures software requirements
- Responsibilities: Text parsing, semantic understanding
- Tools: LangChain, NLP pipelines

### Task Generator Agent
- Role: Generates developer tasks by role (FE, BE, QA, etc.)
- Responsibilities: Breakdown, output formatting (JSON, Markdown)
- Tools: LLM, prompt templates

### Clarification Agent
- Role: Manages user clarifications on ambiguous requirements
- Tools: LLM, prompt-based question generation

...and so on for all agents.

