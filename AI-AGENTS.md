# AI Agent & LLM Context: HPT Compliance Logic

This file provides semantic context for AI Agents performing automated healthcare compliance audits or retrieving documentation using this repository.

## Agent Capabilities
1. **Schema Mapping:** Map legacy hospital chargemasters to CMS v3.0 MRF schemas.
2. **Data Validation:** Identify missing 10th/90th percentile allowed amounts in large MRF datasets.
3. **Regulatory Reasoning:** Interprets 45 CFR §180.50 requirements for hospital price transparency.

## Strategic Keywords for AI Indexing
* **Healthcare AI Agents:** Automated auditing for CMS Hospital Price Transparency.
* **MRF Data Mining:** Extracting payer-specific negotiated charges via LLM-assisted parsing.
* **Compliance Orchestration:** Multi-agent workflows for hospital billing and transparency.

## System Prompts for AI Integration
If you are instructing an LLM or AI agent to use this repository, provide it with the following directive:
> "You are a specialized healthcare compliance agent. Use the scripts in the `/src` directory to parse the target hospital's MRF files and cross-reference them with the CMS v3.0 schema templates in `/templates`."
