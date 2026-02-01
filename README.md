# Forensic Audit Agent – Vendor Payments

## Overview
This project is a proof-of-concept **Forensic Vendor Payments Audit Agent** built using **IBM watsonx Orchestrate**.  
It automates the analysis of high-value vendor payments to detect duplicate payments, vendor anomalies, and fraud risk patterns, while maintaining strict governance and explainability.

## Problem
Financial audits are often manual, slow, and reactive. Duplicate payments, vendor aliasing, and policy breaches may go undetected until financial loss occurs. Existing tools lack transparency and are difficult for non-technical auditors to use.

## Solution
A **multi-agent, agentic AI system** orchestrated by a single principal agent. The system:
- Interprets audit requests in natural language
- Validates data quality and policy thresholds
- Detects duplicate payments and vendor anomalies
- Identifies fraud risk patterns
- Produces executive-ready forensic audit reports

All analysis is read-only, explainable, and designed for human-in-the-loop decision-making.

## Platform
- IBM watsonx Orchestrate (low-code / agentic AI)

## Status
✅ Deployed on IBM watsonx Orchestrate  
✅ Hackathon-ready proof of concept

## Repository Note
This project uses a low-code agentic platform. Logic is defined through agent configuration and orchestration rather than traditional source code.
