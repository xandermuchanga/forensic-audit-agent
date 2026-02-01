# System Architecture

## High-Level Architecture

User
↓
Orchestration & Governance Agent (Main Agent)
↓
Intent & Query Translation Agent
↓
Data Validation Agent
↓
Vendor Verification Agent
↓
Fraud & Anomaly Detection Agent
↓
Audit Reporting Agent
↓
Executive Forensic Audit Report

## Architectural Principles
- Single user entry point
- Specialized agents with clear responsibilities
- Read-only data access
- Explainability and traceability
- No autonomous financial actions

## Deployment Model
Only the **main orchestration agent** is exposed to users.  
All other agents are invoked internally as part of the workflow.

## Scalability
The architecture supports future extensions such as API exposure, raw data ingestion, and continuous monitoring without redesign.
