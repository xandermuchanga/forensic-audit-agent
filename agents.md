# Agent Definitions

## 1. Orchestration & Governance Agent (Main)
- User interaction point
- Interprets audit intent
- Orchestrates all downstream agents
- Enforces execution order and governance
- Consolidates final response

## 2. Intent & Query Translation Agent
- Converts natural language into read-only SQL
- Prevents data modification
- Enables non-technical auditors

## 3. Data Validation Agent
- Checks data completeness and consistency
- Flags missing fields and policy breaches
- Ensures clean input for fraud analysis

## 4. Vendor Verification Agent
- Detects exact duplicate payments
- Identifies fuzzy-matched vendor names
- Flags potential vendor aliasing

## 5. Fraud & Anomaly Detection Agent
- Detects repeated invoice patterns
- Analyzes high-risk payment behavior
- Reports limitations when raw data is unavailable

## 6. Audit Reporting Agent
- Synthesizes findings into a forensic narrative
- Produces executive summaries, evidence, and recommendations
